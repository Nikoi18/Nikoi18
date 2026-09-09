# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is the **GitHub profile README repository** of **Nikoidev LLC**, a software development company
(Domestic Limited Liability Company registered in New Mexico, USA, since 2026). Its single `README.md`
renders on the GitHub profile page at **https://github.com/nikoidev**.

The account was originally a personal profile aimed at recruiters; it is now the **commercial shop
window of the company**. Every content decision should serve one goal: convincing a *potential client*
to hire a project — not convincing a *recruiter* to hire a person.

There is no build system, test suite, or application code — the entire repository is the `README.md` file itself.

## Account naming (important)

The account was renamed `Nikoi18` → `nikoidev`. The user `Nikoi18` no longer exists and
`github.com/Nikoi18/Nikoi18` is a **permanent GitHub redirect** to `nikoidev/nikoidev` (same repo,
id `1067008131`). The local folder name and any old remote URL are historical only. Always use
`nikoidev` in links, widgets and documentation.

## Content Structure

The README is written in Markdown with light HTML (`<div align="center">`, `<p align="center">`), in **Spanish**:

1. **Header** — Company name, tagline, contact badges, `New Mexico, USA · LLC desde 2026` badge
2. **Qué hacemos** — Services table, described by *business outcome*, not by technology
3. **Cómo trabajamos** — 4-phase process table + technical commitments
4. **Proyectos de referencia** — Public, auditable repos owned by the company
5. **Experiencia del equipo fundador** — Founder's prior professional work (Oficomputer + private platforms)
6. **Stack tecnológico** — Compact 5-row table of `flat-square` badges
7. **Fundador** — Short bio of Nicolas A. Urbaez A., education compressed to one line
8. **¿Hablamos de tu proyecto?** — Call to action and contact badges
9. **Actividad** — `github-readme-activity-graph` + legal footer

## Content Rules

- **Never attribute Oficomputer work to Nikoidev LLC.** Projects built for Oficomputer's clients
  (transport ERP, VB6 migration, CSV importer, license issuer) and the private platforms (SGE, SED, Nimiq)
  belong in *Experiencia del equipo fundador*, explicitly framed as the founder's prior work with code
  owned by third parties. Company-owned public repos go in *Proyectos de referencia*.
- **No job-seeking signals.** Avoid "¿Qué puedo aportar?", "actualmente trabajo en …", "dale una estrella
  a mis repositorios", profile-view counters and motivational quotes.
- **Company voice** ("construimos", "trabajamos"), with the founder visible in his own section.
- Keep claims verifiable: coverage figures (78 % vimes, 86 % Usuarios), CI/CD and production deployments
  are stated because the public repos back them up.

## Key Details

- GitHub username in links and widgets: `nikoidev`
- Portfolio / company site: `https://nikoidev.com`
- Badge style: `shields.io` — `for-the-badge` for header and CTA, `flat-square` inside the stack table
- Activity graph theme: `tokyo-night`, background `#0d1117`, accent `#58a6ff`
- Language: Spanish

## Profile Settings (outside this repo)

The README is only half of the profile. These values are the approved configuration for
**Settings -> Public profile** at https://github.com/settings/profile. They cannot be changed from
this repository (and `gh api -X PATCH user` needs the `user` token scope, which the local token lacks):

| Field | Value |
|---|---|
| Name | Nikoidev LLC |
| Bio | Software a medida para empresas - Web - ERP - Modernizacion de sistemas |
| Company | Nikoidev LLC |
| Email | info@nikoidev.com |
| Location | Remoto - Espana / Venezuela / EE.UU. |
| Website | https://nikoidev.com |

## Repository Hygiene

`.gitignore` excludes `*.pdf`: the company's legal documentation (certificate of organization, EIN,
operating agreement, contracts) lives in this folder locally and **must never be committed**.
