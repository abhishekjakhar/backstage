# @backstage/plugin-scaffolder-backend

## 0.2.0
### Minor Changes

- 3e254503d: Add Azure DevOps support to the scaffolder backend
  
  This adds support for Azure DevOps to the scaffolder (preparer & publisher). I thought I should get this in there now since #2426 has been merged. I had a previous PR with only the preparer but I closed that in favor of this one.
  
  I stayed with the 'azure/api' structure but I guess we should try and go the same way as with GitHub here #2501

### Patch Changes

- 0c370c979: Update SSR template to pass CI
- c926765a2: Allow templates to be located on non-default branch
- 6840a68df: Add authentication token to Scaffolder GitHub Preparer
- Updated dependencies [3a4236570]
- Updated dependencies [e0be86b6f]
- Updated dependencies [f70a52868]
- Updated dependencies [12b5fe940]
- Updated dependencies [5249594c5]
- Updated dependencies [56e4eb589]
- Updated dependencies [e37c0a005]
- Updated dependencies [a768a07fb]
- Updated dependencies [f00ca3cb8]
- Updated dependencies [440a17b39]
- Updated dependencies [8afce088a]
  - @backstage/catalog-model@0.2.0
  - @backstage/backend-common@0.2.0
