# Resume Keyword Checker

[![Live demo](https://devilking7x.github.io/resume-keyword-checker/badge.svg)](https://devilking7x.github.io/resume-keyword-checker/) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> Compare your resume and a job description without sending either anywhere.

Resume Keyword Checker extracts meaningful words from resume and job-description text, shows a lightweight match percentage, and highlights terms worth considering. It is designed as an editing aid, not an employment prediction.

## Features

- Two-pane resume and job description editor.
- Local keyword extraction with common-word filtering.
- Match percentage and matched terms.
- Missing-keyword checklist.
- Copyable report.
- No account, upload, analytics, or backend.
- Responsive interface.

## Getting started

```bash
git clone https://github.com/devilking7x/resume-keyword-checker.git
cd resume-keyword-checker
pnpm install
pnpm dev
```

```bash
pnpm check
pnpm build
```

## Responsible use

Keyword matching is only a rough editing signal. Add a keyword only when it accurately represents your experience. Do not use this tool to fabricate qualifications or make automated hiring decisions.

## Privacy

Text is processed in browser memory. The project does not intentionally upload resume content or job descriptions.

## License

MIT — see [LICENSE](LICENSE).

## Demo

Try the live app: https://devilking7x.github.io/resume-keyword-checker/

## Who it is for

This project is designed for **job seekers**. Its narrow first release focuses on helping them compare resume language with a job description locally. The interface uses realistic synthetic fixtures so the value is understandable without connecting a production account.

## Privacy and safety

The default experience is local-first: inputs are processed in the browser or in the user's own development environment, with no required account, API key, payment flow, or remote storage. Fixtures contain synthetic data only. Review a fork's hosting and analytics configuration before using it with sensitive information.

## Validation

The release workflow is intentionally reproducible. Run `pnpm install --frozen-lockfile`, `pnpm check`, and `pnpm build` before submitting a change. Manual review should cover keyboard operation, visible focus, mobile layout, empty states, and both successful and error paths.

## Limitations

This is a focused open-source MVP rather than a hosted replacement for a production system. It does not guarantee business, legal, financial, medical, accessibility, or security compliance by itself. Validate outputs against the context in which you plan to use them.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for setup, code style, privacy expectations, and pull-request guidance.

## License

Released under the [MIT License](LICENSE).
