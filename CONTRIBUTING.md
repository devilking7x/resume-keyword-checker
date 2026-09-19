# Contributing to Resume Keyword Checker

Contributions are welcome across parsing quality, accessibility, responsible-use copy, tests, and documentation.

Run before opening a pull request:

```bash
pnpm install
pnpm check
pnpm build
pnpm format
```

Test punctuation, hyphenated terms, acronyms, numbers, empty text, very long text, and non-English input before changing extraction behavior. Keep the tool local-only and never add tracking to resume content.

Do not include real resumes, personal information, credentials, or employer-confidential text in issues or fixtures. Use synthetic examples.

Use focused commits such as `fix: preserve product-design terms` or `docs: explain responsible keyword use`.
