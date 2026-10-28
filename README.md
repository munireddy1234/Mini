# MINI — AI Code Verifier

**AI suggests. MINI verifies.**

MINI is an AI coding verification tool designed to test proposed code fixes and identify potential regressions using automated tests.

## 🎯 Problem

AI coding assistants can suggest code fixes that appear correct but may introduce new bugs or break existing functionality.

## 💡 Solution

MINI aims to run automated tests before and after a code change, compare the results, and highlight potential regressions.

## ✨ Planned Features

- Run automated tests on existing code.
- Test code after a proposed fix.
- Compare before-and-after test results.
- Identify potential regressions.
- Display test failures and error details.
- Generate a verification report.

## 🛠️ Technology Stack

- **Python** — verification logic
- **pytest** — automated testing
- **TypeScript** — VS Code extension
- **VS Code Extension API** — editor integration
- **Git** — code change comparison

## 🚧 Project Status

**Currently in development.**

The initial goal is to build a working prototype that runs tests and compares results before and after a code change.

## 🗺️ Roadmap

- [ ] Set up the project structure.
- [ ] Build a basic test runner.
- [ ] Capture baseline test results.
- [ ] Compare test results after code changes.
- [ ] Report potential regressions.
- [ ] Integrate with VS Code.
- [ ] Add isolated test execution for improved safety.

## 🎯 Vision

Help developers validate AI-generated code fixes before accepting them into their projects.

**Note:** Passing tests cannot guarantee that code is completely bug-free. MINI provides additional verification, not a replacement for code review or comprehensive testing.

## 📄 License

License to be decided.
