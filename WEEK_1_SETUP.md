# Mastering AI for Finance — Week 1 setup

**Purpose:** Prepare for the first hands-on session. Bring what is working and the exact error text for anything that is not. Session 1 begins Thursday, October 22, 2026. The partner check is ungraded.

## Current setup snapshot

Checked October 19, 2026 on this Mac:

| Requirement | Status | Evidence / next step |
|---|---|---|
| Python 3.11+ available from terminal | **Ready** | Installed Python 3.12.14 with `uv`. Verified in an Orca terminal using `python3.12 --version`. The macOS system `python3` remains 3.9.6; use `python3.12` or `uv run --python 3.12 python` for this course. |
| OpenAI Codex CLI | **Ready** | Running in Orca on this folder; Codex CLI 0.163.0 displayed. |
| Google Antigravity `agy` CLI | **Ready** | Running in Orca's second terminal pane on this folder; CLI 1.2.16 displayed and signed in. |
| Orca installed and running on this folder | **Ready** | `/Applications/Orca.app` is running with this course folder open and two side-by-side terminal panes. |
| Provider API key created in a developer console | **Still needed** | No key has been created or stored in this folder. Antigravity's Google account sign-in is not the same as an API key. Create one at a provider developer console; `.env.example` has placeholders. Never put the real key in Git. |
| Public GitHub repository | **Ready** | Created at https://github.com/shashankgopalakrishnan-dotcom/mastering-ai-for-finance-fall-2026. Six reviewed Week 1 files published; no professor invited. `.gitignore` excludes `.env`, `.venv`, raw data, and exports. |
| Francis & Zhang (2026), assigned sections | **Partially read / full text needed** | Citation, public abstract, and introduction takeaways are recorded in `WEEK_1_READING_NOTES.md`. The assigned Section 3.1 and Section 4 still need to be read from the full text. |
| Costco latest earnings release and 10-K | **Complete** | SEC EDGAR source links and the exact total-revenue figures are in `COSTCO_SEC_NOTES.md`. FY 2026 total revenue is $303,154 million in both. |
| Anthropic, “Building effective agents” | **Complete to assigned point** | Read through the end of “Workflow: Prompt chaining.” Notes on model, harness, agent, and prompt chaining are in `WEEK_1_READING_NOTES.md`. |
| Purdue data access | **Check prior account status** | Existing Purdue access has been used for WRDS, LSEG Workspace, and Capital IQ in prior work. Confirm each account is active and registration uses your Purdue email; LSEG approval can take days. Course instructions are at the data page linked below. |

## First-session checklist

- [x] Install Python 3.11+ and verify it from an Orca terminal.
- [x] Run Codex CLI and `agy` side by side in Orca on this folder.
- [ ] Create one API key in a provider developer console and configure it locally in `.env`.
- [x] Create a public GitHub repository and confirm the public page works. Do not invite the professor.
- [ ] Read Francis & Zhang (2026), Introduction, Section 3.1, and Section 4 from the full text.
- [x] Locate Costco's latest SEC earnings release and 10-K; record total revenue and source links.
- [x] Read Anthropic's “Building effective agents” through the end of the Prompt chaining workflow section.
- [ ] Confirm active LSEG Workspace, WRDS, and Capital IQ accounts registered with Purdue email.
- [ ] Bring exact error text for anything that fails.

## Error log

Paste exact error text here (remove any secrets, tokens, or personal account details):

| Date | Requirement / command | Exact error | What I tried / result |
|---|---|---|---|
| | | | |

## Working notes

- **Python command:** `python3.12` (3.12.14); `uv run --python 3.12 python` also works.
- **Orca:** installed and open; this folder is the active project; Codex and `agy` are running side by side.
- **Provider configured (provider name only):**
- **GitHub repository URL:** https://github.com/shashankgopalakrishnan-dotcom/mastering-ai-for-finance-fall-2026
- **Purdue data access:** LSEG / WRDS / Capital IQ account status

## Course references

- Prerequisites and setup: https://cinderzhang.github.io/FIN67110-Fall2026/grading.html#prerequisites--your-setup-is-yours
- Course data instructions: https://cinderzhang.github.io/FIN67110-Fall2026/reference/data.html
