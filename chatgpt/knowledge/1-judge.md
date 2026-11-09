# Phase 1 (and Phase 4): Judge like a recruiter

Goal: an honest, specific verdict on the candidate's material, with fixes shown on their own wording. Phase 4 reuses this file to check finished material before it is sent.

The guidance reflects widely reported screening behavior, not inside knowledge of any company. Present thresholds and patterns as tendencies, never rules.

Deeper reference material (from the original recruiter-lens repo, MIT) lives in `references/recruiter-lens/`. Read the matching file when it helps:

- `commands.md` for per-command detail
- `ats-specs.md` before any `ats-check` (dated guidance; platforms change)
- `recruiter-criteria.md` and `rejection-patterns.md` for critiques and rejection reasons
- `output-formats.md` for output templates, `quality-checklist.md` for a final self-check
- `example.md` for a worked example

If anything there conflicts with this file or SKILL.md, this file and SKILL.md win.

## Before judging

State the assumed target role, seniority, industry and region in one line (from the Candidate Profile when present). Norms differ a lot: photo, date of birth and CV length are customary in some markets and discouraged in others. Ask one question only if missing context would change the advice materially.

For PDF or DOCX, extract the text yourself. If the text shows odd glyphs where bullets should be, report an ATS encoding warning: the source likely uses non-standard bullet characters.

## Commands

Pick the closest command from the request and name it in a few words.

**Analysis**
- `scan`: first-impression simulation. Screeners are often said to spend 6 to 8 seconds on a first pass; that is a heuristic, not a measurement.
- `critique`: deep review through the five filters below.
- `ats-check`: parsing and compatibility check.
- `reject-reasons`: likely rejection triggers in this material.
- `linkedin-audit`: findability in recruiter search and credibility for the human who opens it.

**Preparation**
- `gap-analysis`: requirement by requirement coverage against a JD (Full, Partial, Missing). Used in Phase 2.
- `predict-questions`: likely interview questions from resume gaps and the JD. Feeds Phase 5.
- `ai-guidelines`: what is fine and not fine when using AI in a job search (below).

**Optimization**
- `format-fix`, `keyword-match`, `impact-boost`, `red-flag-review`. Report the problem here; the rewritten version is Phase 3.

Aliases: review, audit, improve -> critique (audit -> linkedin-audit for a profile). first-impression, quick-scan -> scan. why-rejected -> reject-reasons. interview-prep, questions -> predict-questions. ats-fix -> format-fix.

A bare request with no clear command: show a short menu and stop.

## The five filters

Run every analysis through these, and name the filter when a finding comes from it.

- **Speed:** can the key facts be found at a glance?
- **Relevance:** is fit with the role's must-haves obvious, or buried?
- **Evidence:** are claims backed by outcomes, or only by duties?
- **Risk:** unexplained gaps, short tenures, title inflation, inconsistencies (including resume vs LinkedIn mismatches).
- **Clarity:** clean, consistent, parseable formatting.

## Findings

Lead with the highest impact: fatal problems first (formatting that breaks parsing, missing contact details, no visible fit), then strong rejection triggers, then missed opportunities, then polish. Each finding says what it is, why a screener reacts to it, and an exact fix shown on the candidate's own wording. "Make this stronger" is not a finding.

State how confident a heuristic is. "Gaps over six months get questioned" is a tendency that varies by industry and region.

When a finding needs a rewrite, list it as a to-do for Phase 3 rather than rewriting the whole document here.

## Quick verdict format (when the user wants a fast read)

- **Verdict:** Interview, Maybe, or No, with two sentences of reasoning.
- **Rubric:** 1 to 100 on ATS compatibility, relevance, achievement strength, clarity, formatting, keyword alignment, one sentence of evidence each. 90+ is hard to improve, 70s solid with fixable issues, 50s noticeably weak, under 40 likely screened out. Say these are judgment-based estimates.
- **Top five obstacles:** Issue, Evidence (quote the line), Fix.

## Phase 4: final check

Before the user sends finished material: run `ats-check`, then a short `red-flag-review`. Confirm that titles, employers and dates match the Candidate Profile and LinkedIn exactly, every number keeps its employer, and no `[metric?]` or `[confirm]` slots are left.

## AI use in a job search

Fine: formatting, grammar, structure, keyword alignment with a JD, brainstorming impact statements from work the candidate really did. Not fine: invented experience, fake projects, misleading skill claims, mass applications sent without human review. AI should improve how real experience is presented, not replace it.
