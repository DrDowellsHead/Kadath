# Kadath

**Kadath** is an offline-first, cross-platform training platform for the C programming language.

> The path to mastery.

## Project status

Project initialization. The existing C21 Dojo prototype will be migrated and audited before the first stable release.

## Target platforms

- Windows
- macOS
- Linux
- Android (Termux / TermuC)

The goal is to run a local web interface and compile/test C submissions on the **user's own device**, without a cloud service.

## Development model

- `main`: stable, released and verified code only.
- `develop`: active development, integration and pre-release testing.
- Short-lived feature/fix branches only when a separate review is justified.
- Release to `main` through a pull request from `develop`, after platform tests pass.

## Planned scope

- 200 original or independently adapted C challenges, inspired by publicly accessible learning and examination exercises.
- Explicit per-task input/output contracts and invalid-input behavior.
- Functional, boundary, adversarial, and regression tests with transparent results.
- Optional compiler sanitizers (ASan / UBSan) where supported.
- Clear distinction between *correct output* and *memory safety*.
- Responsive mobile-first offline UI; progression and practice exams.

This project is independent and is **not** affiliated with, endorsed by or an official exam simulator of School 21.

## Security

Solutions are compiled and executed locally with the user's OS permissions. Timeouts and resource limits do **not** constitute a sandbox. Do not run untrusted submissions or expose the local API to a network.

## License

A license will be chosen before the first public code release.
