# Contributing guide

This guide is for maintainers responsible for reviewing and applying changes to this repository.

---

## Who this repo is for

This repository holds the guidelines and content templates for the content team. It is the single source of truth for all guidance.

---

## Maintainer responsibilities

As a maintainer you are responsible for:

- Reviewing suggested changes from colleagues (submitted via Confluence)
- Applying approved changes to the relevant files in GitHub
- Ensuring `main` always reflects the current agreed guidelines
- Keeping files clearly named, consistently structured, and free of duplication

---

## How to apply a change

1. Go to the relevant file in the repo
2. Click the pencil icon to edit
3. Make the change
4. Add a short, descriptive commit message, for example: `Update ai-instructions — add new tone guidance`
5. Select **Create a new branch and start a pull request**
6. Submit the pull request and merge once reviewed

For straightforward, low-risk edits (fixing a typo, updating a word limit) you may commit directly to `main`. For anything structural or significant, always use a pull request.

---

## Commit message conventions

Keep commit messages short and specific. Use the format:

`[Action] [file name] — [brief reason]`

For example:
- `Update ai-instructions — remove duplicate rule`
- `Add audience-guidance — postgrad section expanded`
- `Fix qualification-template — corrected word limit for overview`

---

## Reviewing suggested changes

Colleagues submit change suggestions via the Confluence page [add link]. When reviewing a suggestion:

- Check whether the change is consistent with the existing guidelines
- Consider whether it affects any other files (for example, a tone change may need updating in both `ai-instructions.md` and `audience-guidance.md`)
- Apply the change in GitHub and note on the Confluence page that it has been actioned

---

## Branch protection

The `main` branch is protected. All significant changes should go through a pull request and be approved before merging. Do not bypass this for anything other than minor fixes.

---

## Questions or decisions beyond your remit

If a suggested change would significantly alter the guidelines, escalate to Lucy or the Web Team before actioning.
