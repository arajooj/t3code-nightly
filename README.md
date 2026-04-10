# T3 Code - Nightly Builds

Automated daily builds of [T3 Code](https://github.com/pingdotgg/t3code) — a minimal web GUI for coding agents.

## About

This repository provides **unofficial nightly builds** of T3 Code for Windows, macOS, and Linux. Builds are generated automatically every day at 04:00 UTC from the latest `main` branch of the upstream repository.

### What is T3 Code?

T3 Code is a minimal web GUI for coding agents (Codex, Claude, and more) created by [T3 Tools Inc.](https://github.com/pingdotgg). Visit the [official repository](https://github.com/pingdotgg/t3code) for more information.

## Downloads

Check the [Releases](https://github.com/arajooj/t3code-nightly/releases) page for the latest nightly builds.

| Platform | Formats |
|----------|---------|
| Windows  | `.exe` (NSIS installer) |
| macOS    | `.dmg`, `.zip` |
| Linux    | `.AppImage`, `.deb`, `.rpm` |

## Important Notices

- These are **automated, unsigned** nightly builds
- They may be **unstable** and are **NOT officially supported** by the T3 Code team
- Use at your own risk
- For stable releases, visit the [official repository](https://github.com/pingdotgg/t3code)
- Builds only happen when there are new commits upstream (no redundant builds)
- Only the last **7 nightly releases** are kept

## How it works

1. A GitHub Actions workflow runs daily at 04:00 UTC
2. It checks if there are new commits upstream since the last build
3. If so, it clones the upstream repo, builds desktop apps for all platforms
4. Artifacts are uploaded as a pre-release with the build date and commit SHA

## License

T3 Code is licensed under the **MIT License**.

```
Copyright (c) 2026 T3 Tools Inc.
```

See [LICENSE](./LICENSE) for the full license text.

This is an **unofficial redistribution**. All credit goes to the original authors at [pingdotgg/t3code](https://github.com/pingdotgg/t3code).

---

*This repository is not affiliated with or endorsed by T3 Tools Inc.*
