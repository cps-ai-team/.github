# Knowledge-Library Template

This folder contains the standard templates for creating a new CPS AI information library repository.

## When to use this template

Copy this template whenever the team decides to create a new knowledge library — a repository whose primary purpose is to hold reference material, guidance, or reusable content (rather than code or a delivered solution).

## How to use it

1. **Create the new repository** under the `cps-ai-team` organisation on GitHub.
2. **Copy `README-template.md`** to the root of the new repository and rename it `README.md`.  
   Fill in every section — delete placeholder text and replace it with content specific to the new library.
3. **Copy `CONTENT-GUIDE-template.md`** to the root of the new repository and rename it `CONTENT-GUIDE.md`.  
   Update the taxonomy table rows if the library has its own specific content types.
4. **Add a link to the new library** in the organisation landing page (`profile/README.md` in this repository) with a one-line description.
5. **Assign an owner** and record the review cadence in the new README before merging the first PR.

## Files in this template

| File | Purpose |
|---|---|
| `README-template.md` | Standard structure for a library README — purpose, audience, content rules, navigation, owner, and contribution guide |
| `CONTENT-GUIDE-template.md` | Taxonomy decision guide — helps contributors choose the right library for new content |

## Keeping the template up to date

If the team agrees a new mandatory section or changes the taxonomy, update the files in this folder and raise a PR against this repository. Existing library READMEs do not need to be updated automatically, but owners should review them at their next scheduled cadence.
