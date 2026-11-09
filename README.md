# Career Kit

A free job-search assistant for Claude. It walks through a job search in the order it happens:

| Phase | What you get |
|---|---|
| 0. Intake | A Candidate Profile you fill in once and reuse |
| 1. Judge | A recruiter's read of your resume or LinkedIn: 6-second scan, ATS check, critique, rejection reasons |
| 2. Target | A job posting decoded, plus requirement-by-requirement gap analysis |
| 3. Produce | Tailored resume, stronger bullets, keyword map, five summaries, LinkedIn rewrite |
| 4. Final check | One more pass before you hit send |
| 5. Interview prep | Company cheat sheet, honest gap lines, story bank, question bank, mock interview, questions to ask, pay talk |
| 6. After | Reflection, recruiter confirmation, thank-you note, next-round prep |

You can start at any phase. It only asks for what that phase needs.

**It never invents anything about you.** Every employer, title, date and number comes from your profile or from you. When a line would be stronger with a number you have not given, it asks or leaves a visible blank.

## Two ways to use it

### Option A: Install the skill (Claude apps and Claude Code)

The skill lives in [`skills/career-kit/`](skills/career-kit/).

- **Claude Code:** copy the `skills/career-kit` folder into `~/.claude/skills/` (personal) or `.claude/skills/` in a project.
- **Claude apps:** download this repo as a ZIP, zip just the `skills/career-kit` folder, and upload it as a custom skill. Check Claude's help center for where custom skills are uploaded on your plan.

Then just talk normally: "here's my resume, why am I not getting interviews?" or "I have an interview Thursday, here's the job posting."

### Option B: No install (any AI chat)

Open [`prompt/career-kit-prompt.md`](prompt/career-kit-prompt.md), copy everything below the line, and paste it as the first message of a new chat. Works with Claude on any plan and with other assistants.

## Start here

1. Fill in [`candidate-profile-template.md`](skills/career-kit/assets/candidate-profile-template.md), or just attach your resume and let the assistant fill it in and ask for the rest.
2. Save the filled profile. Attach it at the start of every new session so you never retype your history.
3. Tell it what you need right now.

## Privacy

Your profile contains personal information. Keep it in your own files. Do not commit a filled-in profile to a public repo.

## Credits

- Phase 1 adapts [recruiter-lens](https://github.com/arm-pz/recruiter-lens) by Abdul Rahman P Z (MIT). Its reference files are included unmodified.
- Phase 3 adapts workflow patterns from a public prompt thread by @codeby_abir on X.
- Combined and generalized by Scott Sheffield.

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). Licensed under MIT.

*This is not legal or financial advice, and no tool can guarantee an interview or an offer.*
