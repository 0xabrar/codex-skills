# Codex Skills

This repo contains Codex CLI skills. Each skill lives in its own folder with a `SKILL.md` file and optional reference docs under `references/`.

## Skills by area

### Expo and app delivery

| Skill | Description | Path |
| --- | --- | --- |
| building-ui | Complete guide for building beautiful apps with Expo Router. Covers fundamentals, styling, components, navigation, animations, patterns, and native tabs. | `building-ui/SKILL.md` |
| deployment | Deploying Expo apps to iOS App Store, Android Play Store, web hosting, and API routes | `deployment/SKILL.md` |
| dev-client | Build and distribute Expo development clients locally or via TestFlight | `dev-client/SKILL.md` |
| upgrading-expo | Guidelines for upgrading Expo SDK versions and fixing dependency issues | `upgrading-expo/SKILL.md` |
| use-dom | Use Expo DOM components to run web code in a webview on native and as-is on web. Migrate web code to native incrementally. | `use-dom/SKILL.md` |

### Data and APIs

| Skill | Description | Path |
| --- | --- | --- |
| api-routes | Guidelines for creating API routes in Expo Router with EAS Hosting | `api-routes/SKILL.md` |
| data-fetching | Use when implementing or debugging ANY network request, API call, or data fetching. Covers fetch API, axios, React Query, SWR, error handling, caching strategies, offline support. | `data-fetching/SKILL.md` |

### iOS UX and accessibility

| Skill | Description | Path |
| --- | --- | --- |
| ios-accessibility-audit | Audit iOS accessibility for React Native + Expo screens and flows. Use to check Dynamic Type, VoiceOver, touch targets, contrast, focus order, and reduced motion. | `ios-accessibility-audit/SKILL.md` |
| ios-hig-rn-basics | Core iOS HIG guidance mapped to React Native + Expo. Use when designing or reviewing iOS UI/UX for layout, typography, color, spacing, controls, and iconography. | `ios-hig-rn-basics/SKILL.md` |
| ios-motion-feedback | iOS motion and haptics guidance for React Native + Expo. Use when designing animations, transitions, or feedback states. | `ios-motion-feedback/SKILL.md` |
| ios-navigation-architecture | Choose and review iOS navigation patterns for React Native + Expo (tabs, stacks, modals, sheets, deep links). Use when designing app structure or refactoring navigation. | `ios-navigation-architecture/SKILL.md` |
| ios-screen-review | Structured UX/UI review checklist for iOS screens in React Native + Expo. Use to critique hierarchy, spacing, affordances, copy, and states and output prioritized fixes. | `ios-screen-review/SKILL.md` |

### Git and GitHub workflows

| Skill | Description | Path |
| --- | --- | --- |
| git-commit-workflow | Git branch and commit workflow with conventional commits. Use when asked to create/switch branches, stage changes, write commit messages, or manage commits in multi-worktree setups. | `git-commit-workflow/SKILL.md` |
| git-pr-workflow | Git workflows for feature branches and GitHub CLI pull requests. Use when asked to manage branches, push to remotes, create PRs, or generate PR titles/descriptions, including multi-worktree setups. | `git-pr-workflow/SKILL.md` |

### Codex system skills

| Skill | Description | Path |
| --- | --- | --- |
| skill-creator | Create or update skills that extend Codex with specialized knowledge, workflows, or tool integrations. | `.system/skill-creator/SKILL.md` |
| skill-installer | Install skills into `~/.codex/skills` from the curated list or another repo. | `.system/skill-installer/SKILL.md` |
