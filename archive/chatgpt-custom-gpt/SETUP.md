# Set up Career Kit as a Custom GPT (outdated)

> **Outdated (Nov 2026):** OpenAI no longer lets personal ChatGPT accounts (Free, Go, Plus, Pro) create GPTs, and existing GPTs are scheduled to retire on Dec 11, 2026. Use a ChatGPT Project instead: paste `instructions.md` or the copy-paste prompt into the project's instructions. Kept here for reference.

Creating a GPT needs a paid ChatGPT plan. Sharing it by link lets others use it. ChatGPT's menus change, so if a step looks different, look for "GPTs" then "Create" and the "Configure" tab.

## 1. Create the GPT

In ChatGPT, open **GPTs**, choose **Create**, then switch to the **Configure** tab (skip the chat builder).

## 2. Fill in the fields

**Name**
```
Career Kit
```

**Description**
```
Recruiter-eye resume review, job-posting decoding, honest tailoring, LinkedIn rewrites, and step-by-step interview prep. Never invents your experience.
```

**Instructions**
Paste the full contents of `instructions.md` (about 4,700 characters, under the 8,000 limit).

**Conversation starters**
```
Here's my resume. Why am I not getting interviews?
```
```
Tailor my resume to this job posting.
```
```
I have an interview this week. Help me prepare.
```
```
Set up my Candidate Profile.
```

## 3. Upload Knowledge files

Upload these 10 files from the repo:

| File | Location in the repo |
|---|---|
| candidate-profile-template.md | skills/career-kit/assets/ |
| 1-judge.md | skills/career-kit/references/ |
| 2-target.md | skills/career-kit/references/ |
| 3-produce.md | skills/career-kit/references/ |
| 5-interview.md | skills/career-kit/references/ |
| 6-after.md | skills/career-kit/references/ |
| study-deck.md | skills/career-kit/references/ |
| ats-specs.md | skills/career-kit/references/recruiter-lens/ |
| recruiter-criteria.md | skills/career-kit/references/recruiter-lens/ |
| rejection-patterns.md | skills/career-kit/references/recruiter-lens/ |

The `knowledge/` folder next to this file has all 10 in one place.

## 4. Capabilities

- Web Search: **on** (company research for interviews)
- Code Interpreter & Data Analysis: **on** (reads PDFs and DOCX, builds .docx resumes)
- Image Generation: **off**

## 5. Test before sharing

Try each conversation starter with a sample resume (not a real person's unless they agreed). Check that it:
- asks for missing numbers instead of making them up
- runs one phase per reply
- waits for "done" before grading the mock interview

## 6. Share

Choose **Create** or **Update**, then set visibility to **Anyone with the link** and copy the link. Add it to the repo README.

## Privacy note for users

Anyone using the GPT uploads their own resume to their own ChatGPT account. The GPT builder does not see their chats. Remind users not to paste ID numbers or bank details.
