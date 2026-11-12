# Contributing

Thanks for wanting to make this better. Settings menus move and products change, so corrections are the most useful help.

## What helps most

- Corrections when a phone, router, or service changes where a setting lives. Link to the vendor's own help page.
- Tips that worked in your household, especially for kids' devices and helping older relatives.
- Translations, accessibility fixes, and printable versions.

## How to write here

- **Write for the family's tech lead**, who's capable but busy.
- **Give the reason before the steps.** People skip steps they don't understand.
- **Name tools when it helps, and give more than one,** including free options and the ones already built into phones.
- **Never ask readers to write down passwords** in a template that could be lost or shared.
- Use the serial comma.

## Checking your change

```
node tools/check.mjs
```

## Branches and commits

Name branches `feat/`, `fix/`, `docs/`, or `chore/` plus a short hyphenated description. Use [Conventional Commits](https://www.conventionalcommits.org/), for example `feat(handbook): add a chapter on gaming consoles` or `fix(handbook): update the Screen Time steps`. Merge with `git merge --no-ff`, and never rewrite history on `main`.
