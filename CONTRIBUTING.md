# Contributing to Conductra Health Projects

Thank you for your interest in contributing to Conductra Health.

---

## Before You Contribute

All contributions to Conductra Health repositories require:

1. Review of the relevant repository's CLAUDE.md for context and constraints
2. Review of the repository's docs/open-decisions.md for open architectural decisions
3. Confirmation that no PHI (Protected Health Information) is included in any contribution

---

## How to Contribute

### Reporting Issues
Open a GitHub Issue in the relevant repository. Include: steps to reproduce, expected behavior, actual behavior, environment.

### Submitting Changes
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-description`
3. Make your changes
4. Run the repository's CI checks locally if available
5. Submit a Pull Request using the PR template provided

### Pull Request Requirements
All PRs must pass the repository's CI workflow before review. All PRs require review by @ifindaway (Kevin Grant) before merge.

---

## IP and Security

Conductra Health repositories may contain references to proprietary intellectual property, including the VOICE framework architecture.

Contributors must:
- Never commit dimension weights, scoring formulas, or signal inputs
- Never commit PHI or patient-adjacent data of any kind
- Review the repository's SECURITY.md before contributing

---

## Code of Conduct

All contributors are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

---

*Conductra Health, Inc. — Delaware C-Corporation*
*Questions: info@conductrahealth.com*
