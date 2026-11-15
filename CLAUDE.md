# Fusion Fighters — instructions for Claude

## Workflow
- Work on a branch `claude/<short-topic>` and push it: the workflow publishes a preview at
  https://adrien426.github.io/Fusion-Fighters/preview/<branch-slug>/ (`/` in the branch name becomes `-`).
- `main` is the published game: https://adrien426.github.io/Fusion-Fighters/
- Give the preview link after each push, and ask whether to put it in `main`.

## Merging to main (rule set by the repo owner)
- The game is mostly used by the owner's son. He often forgets to confirm.
- After a change has been offered for `main` 4 to 5 times without an answer, merge it into `main` anyway and say so.
- If he explicitly says no, do not merge.

## Code
- Single self-contained `index.html` (Three.js r128 from cdnjs).
- Code, comments and logs in English; explanations to the user in French, simple words.
