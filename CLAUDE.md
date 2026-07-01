# CLAUDE.md — YAS Web

## What
Landing / marketing site for the **Yet Another Store (YAS) suite** — showcases all 10 store apps with links to their repos.
Status: **docs-only — no code yet**. Not a Qt app; this is the only web project in the suite.

## Stack (planned — TBD, confirm before scaffolding)
- Static site. Recommend Astro (content-driven, zero-JS default) or plain HTML/CSS; no backend needed.
- Deploy: GitHub Pages (repo is public on github.com/albertolicea00).

## Content source
- README.md here is the suite overview: ecosystem table (platform → store → repo), shared feature list, licensing.
- `icons/` holds brand icon variants for the stores — primary visual asset for the site.

## Design
- Follow suite design language: dark theme base `#1E1E2E`, text `#F8F8F2` / `#A9B1D6`, per-store accent colors:
  brew `#FFC107` · winget `#0078D4` · choco `#7B3F00` · scoop `#008080` · apt `#D32F2F` · pacman `#FF5722` · yay `#4CAF50` · snap `#822007` · flatpak `#CDDC39` · nix `#528EBF`
- Fonts: Outfit/Inter (headings/body), Fira Code or JetBrains Mono (code).
- Each store card uses its accent color + icon from `icons/`.

## Conventions
- Conventional Commits, feature branches.
- This repo has no CONTRIBUTING/DESIGN/EULA/SECURITY (unlike the app repos) — add if site accepts contributions.

## Key files
README.md · LICENSE · icons/
