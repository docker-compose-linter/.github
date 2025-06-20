<!-- markdownlint-disable MD013 MD033 -->
<h1 align="center">
    <img src="../assets/logo-grey.svg" alt="Docker Compose Linter Logo" height="192" width="auto" />
    <br>
    Docker Compose Linter
</h1>
<p align="center">
    <a href="https://github.com/sponsors/docker-compose-linter"><img alt="GitHub Sponsors" src="https://img.shields.io/github/sponsors/docker-compose-linter?style=for-the-badge&logo=github"></a>
    <a href="https://opencollective.com/dclint"><img alt="Open Collective backers and sponsors" src="https://img.shields.io/opencollective/all/dclint?style=for-the-badge&logo=opencollective"></a>
</p>
<!-- markdownlint-enable MD013 MD033 -->

Docker Compose Linter (**DCLint**) is a utility designed to analyze, validate and fix Docker Compose files. It helps
identify errors, style violations, and potential issues, ensuring your configurations are
robust, maintainable, and free from common pitfalls.

## Projects

- **[DCLint](https://github.com/zavoloklom/docker-compose-linter)** – CLI for static analysis of Docker Compose files.
- **[GitHub Action](https://github.com/docker-compose-linter/dclint-github-action)** – GitHub Action for CI integration.
- **[Hook for pre-commit](https://github.com/docker-compose-linter/pre-commit-dclint)** – pre-commit hook.
- **[Gitlab Group](https://gitlab.com/dclint)** – contains GitLab-specific integrations and examples.

## Features

- **Error Detection**: Identifies syntax errors and common issues in Docker Compose files.
- **Style Enforcement**: Enforces best practices and style guidelines for maintainable configurations.
- **Flexible Integration**: Can be used locally, in Docker, or integrated into CI/CD pipelines.
- **Configurable Rules**: Customize the linter's behavior and rules according to your project's needs.
- **Auto-fixable Rules**: Some rules include an auto-fix mode, allowing you to automatically format and correct certain
  issues in your files.
- **Comments Support**: After automated sorting and fixing, comments remain in the correct place, ensuring no important
  information is lost during the formatting process.
- **Anchor Support:** Supports YAML anchors for shared configuration sections, with some limitations.

## Contacts and Support

If you find this project helpful, kindly consider showing your appreciation by giving it a star ⭐.

If you have any questions or suggestions, feel free to reach out:

- **Email**: [s.kupletsky@gmail.com](mailto:s.kupletsky@gmail.com)
- **Х/Twitter**: [zavoloklom](https://x.com/zavoloklom)
- **Instagram**: [zavoloklom](https://www.instagram.com/zavoloklom/)
- **GitHub**: [zavoloklom](https://github.com/zavoloklom)

A detailed devlog and roadmap for DCLint is available on Patreon:
[patreon.com/c/zavoloklom](https://www.patreon.com/c/zavoloklom)

Also, you can support this project with a one-time donation or becoming a sponsor:

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=J8KS3RUFKSHDL)
[![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/c/zavoloklom)
[![GitHub Sponsors](https://img.shields.io/badge/GitHub%20Sponsors-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sponsors/docker-compose-linter)
[![Open Collective](https://img.shields.io/badge/Open%20Collective-3385FF?style=for-the-badge&logo=opencollective&logoColor=white)](https://opencollective.com/dclint)
