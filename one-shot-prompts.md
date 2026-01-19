# Proactive Perfect Prompt — Closing All Gaps For Maximum Ready, Reliable Scripts

Use this template with generative models (e.g., Copilot, ChatGPT) to ensure every script is flawless, fully-ready, and proactively protected against all issues.  
**Just replace `[Brief description of your task]` — the model must deliver a robust, portable script with no possibility for errors or unwanted behavior, even if you give only minimal input.**

---

## UNIVERSAL PROACTIVE SCRIPT PROMPT

**Prompt:**  
Generate a single, portable script in [LANGUAGE] named `[FULL_FILENAME]` to:  
[Brief description of your task]

**Essential Requirements & Proactive Engineering:**

1. **Proactive Gap-Securing:**
    - Analyze, anticipate, and close any possible gap, missing logic, or scenario that could cause failure, error, or undesired output—even if not mentioned in the description.
    - Implement self-checks, sanity validations, and protective error handling at every step.
    - Never rely on user input correctness—always validate and sanitize explicitly.
    - Engineer the solution as if for a critical system where failures are unacceptable.
    - If input is insufficient or vague, add all necessary logic and structure by default using industry standards and common sense.
2. **Start from Final Results (Top-Down, Reverse Engineering):**
    - First, define and guarantee the exact final outputs or results the script should deliver.
    - Build all logic and processing backward from these strict result requirements, ensuring all internal steps serve the final outcome with zero gaps.
3. **Comprehensive Documentation & Auditing:**
    - At the script head, provide a full comment block: filename, reference number, version, model/author, engineering method, date/time, purpose, changelog.
    - Before code, display filename and main result reference.
4. **Arabic Comments, Numbered Steps:**
    - Every logic, block, or critical part in code starts with a reference number.
    - All comments and explanations inside the code are in Arabic, ensuring clarity for Arab users.
5. **Practical Validation & Self-Test:**
    - Integrate real test/demo blocks within the script.  
    - After each critical function, verify actual results and check against all conceivable error cases.
    - Print summary of verification/test results at run-time.
6. **User Experience & Ready-to-Run:**
    - Output must be user-friendly, clear, and never ambiguous.
    - Every error, edge-case, or warning is explained to the user with actionable tips.
    - Script is immediately usable with no manual prep or hidden requirements.
7. **Maintenance, Expansion, and Common Problems:**
    - End with a section detailing how to maintain, extend, or fix the script for future needs.
    - List all likely problems and show precisely how the script prevents/solves them.
8. **Strict Compliance:**
    - Ignore no part—even with minimal user description, infer and supply all necessary safety, completeness, and correctness logic.
    - No shortcuts, gaps, or missing documentation allowed under any circumstances.

---

**How to use:**  
- Put your simple description in `[Brief description of your task]`.
- Change `[LANGUAGE]` and `[FULL_FILENAME]` as you wish.
- Copy+paste the prompt into your model.
- Receive a ready-to-run, fully audited, documented, user-friendly, and totally robust script—with proactive gap-closing and protection.

---

### Example usage

Generate a single portable Python script named `secure_report_v1.0.py` to:
Create a summary report from user-supplied data files.

(The reply will obey the proactive requirements above, closing all gaps and yielding the safest, most reliable script possible.)

---

**Tip:**  
To further ensure safety, add “Force double-checks for any unusual input, and lock out any dangerous or ambiguous behavior.”
