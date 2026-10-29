# Content Guide — where does this belong?

> **Copy this file when creating a new library.**  
> Update the table rows if the library has specific content types. Delete this notice when done.

Use this guide when you are unsure which CPS AI library is the right home for a piece of content. Apply the taxonomy test below before raising a pull request.

---

## The taxonomy decision test

Ask yourself the questions in order. Stop at the first row that matches.

| Is the content… | Where it belongs | Why |
|---|---|---|
| A mandatory process, control, or operating standard? | [`sop-library`](https://github.com/cps-ai-team/sop-library) | SOPs define *how CPS operates*. If non-compliance would be a problem, it is an SOP. |
| Reusable guidance explaining a solution approach, design pattern, or way of solving a technical/delivery problem? | [`pnp-library`](https://github.com/cps-ai-team/pnp-library) | Patterns explain *why* an approach works and *when* to use it. They are not instructions to follow blindly. |
| A copy-and-adapt artefact used directly in a customer engagement (deck, template, email, diagram, workshop pack)? | [`asset-library`](https://github.com/cps-ai-team/asset-library) | Assets are things people *take and use*. They are files, not guidance. |
| A learning link, external documentation reference, or tool-installation guide? | [`useful-resources`](https://github.com/cps-ai-team/useful-resources) | Useful resources point outward to learning material and practical setup steps. |
| Evidence of a published, delivered solution or project output? | [`solution-catalogue`](https://github.com/cps-ai-team/solution-catalogue) or the project repository | The catalogue is automatically indexed. Place project files in the project repo; the catalogue entry is generated. |
| A use-case assessment, prioritisation, or opportunity-sizing artefact? | [`use-case-matrix`](https://github.com/cps-ai-team/use-case-matrix) | The matrix tool supports decision-making about *which* AI use cases to pursue. |

---

## Still unsure?

If content could fit in more than one library, prefer the following tie-breakers:

1. **Mandatory vs optional:** If following the guidance is mandatory or has a governance implication, it is an SOP.
2. **Explain vs deliver:** If the content *explains an approach*, it is a pattern. If it *is the thing you hand to a customer*, it is an asset.
3. **Internal vs external facing:** Internal process and standards go in `sop-library`. Content that leaves the building goes in `asset-library`.
4. **Ask the owner:** Each library has a named owner (see the library README). A quick message is faster than a mis-filed PR.

---

## Changing this guide

If the taxonomy needs to change — for example, a new library is created or a category boundary shifts — raise a PR against this file and the master copy in `.github/templates/knowledge-library/CONTENT-GUIDE-template.md`. Tag the relevant library owners as reviewers.
