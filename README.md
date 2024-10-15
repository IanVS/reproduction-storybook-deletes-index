# Issue Reproduction

Steps:

1. `pnpm install`
2. `pnpm build-storybook` 
3. `git status` should be clean, no changes
4. `pnpm build-storybook` again
5. `git status` shows deleted `index.html` file.
