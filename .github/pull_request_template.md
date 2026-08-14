## Summary
- [ ] Dependency maintenance update
- [ ] No intended API changes
- [ ] Linked issue (optional): #

## Update Scope
### Runtime dependencies
- [ ] Updated runtime deps (if any):
  - [ ] `fuse.js`
  - [ ] `nanoid`

### Type/build toolchain
- [ ] Updated type/tooling deps (if any):
  - [ ] `typescript`
  - [ ] `vue-tsc`
  - [ ] `@types/node`
  - [ ] `@vue/tsconfig`

### Vue/Vite toolchain
- [ ] Updated framework/bundler deps (if any):
  - [ ] `vue`
  - [ ] `vite`
  - [ ] `@vitejs/plugin-vue`

### Docs/styling/plugins
- [ ] Updated docs/style/plugin deps (if any):
  - [ ] `sass`
  - [ ] `highlight.js`
  - [ ] `unocss`
  - [ ] `unplugin-icons`
  - [ ] `unplugin-vue-components`
  - [ ] `@iconify/json`

### Packaging/types output
- [ ] Updated packaging deps (if any):
  - [ ] `@microsoft/api-extractor`

## Verification
### Install & build
- [ ] `pnpm install`
- [ ] `pnpm run build:types`
- [ ] `pnpm run build:lib`
- [ ] `pnpm run build:docs`

### Behavior smoke tests
- [ ] Keyboard navigation works (`↑` `↓` `Enter` `Esc`)
- [ ] Focus management works (open/close/focus return)
- [ ] Search/filter behavior unchanged
- [ ] Docs demo renders correctly

### Consumer compatibility
- [ ] ESM import still works
- [ ] CJS import still works (if supported)
- [ ] `exports` / `main` / `module` / `types` still aligned
- [ ] No unintended changes in generated `.d.ts`

## Risk Review
- [ ] No breaking changes found in changelogs
- [ ] Any major-version updates are called out below
- [ ] If breaking changes exist, migration notes added

## Notes for Reviewers
- High-risk updates in this PR:
  - [ ] None
  - [ ] Yes (describe below)

### Additional context
<!-- Paste links to release notes/changelogs for major deps -->
