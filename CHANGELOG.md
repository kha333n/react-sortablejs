# 1.0.0 (2024-11-15)


### Bug Fixes

* **react-sortable.jsx:** const newList = [...props.list].map((item) => ([c945c6d](https://github.com/kha333n/react-sortablejs/commit/c945c6d659b952c545a23baed26caa663737c58c))
* allow update disabled prop at runtime ([dccdd24](https://github.com/kha333n/react-sortablejs/commit/dccdd2476790ea795dcbc5fc39ce27abebebbd35))
* fix package versions ([b464971](https://github.com/kha333n/react-sortablejs/commit/b464971d0c530c6c5fa764da13b610b3507f6378))
* infra ([1d43f97](https://github.com/kha333n/react-sortablejs/commit/1d43f97af5c9e8278fe9367f72e7f2a5b213bbba))
* object-assign errors ([fde561e](https://github.com/kha333n/react-sortablejs/commit/fde561e0b730dc7f7a664a48277b117e841c613a))
* passes clone function to onAdd if cloning ([#173](https://github.com/kha333n/react-sortablejs/issues/173)) ([5ff3f4a](https://github.com/kha333n/react-sortablejs/commit/5ff3f4a989162f08269a66fc325f22fcb600cfd2))
* preserve original objects ([362cbd5](https://github.com/kha333n/react-sortablejs/commit/362cbd57e75e02f12eff12925f7ec346a20721d9))
* update dependencies ([b8ca5c2](https://github.com/kha333n/react-sortablejs/commit/b8ca5c2bd9a494492f7b4865db9241b1b059a056))
* update dependencies ([8401a8c](https://github.com/kha333n/react-sortablejs/commit/8401a8c95a216e449b91779556d53fdbd46ab768))
* **react18:** add `children` to `ReactSortableProps` ([f6b4e2e](https://github.com/kha333n/react-sortablejs/commit/f6b4e2e1fa235752348c3b4021120c2a56ea41c7))
* spell 'these' incorrectly ([0656825](https://github.com/kha333n/react-sortablejs/commit/06568255f25e99a85952950c1d5cf7ce10451924))
* **ci:** adds dist/** to git assets ([c46913f](https://github.com/kha333n/react-sortablejs/commit/c46913f4e05a628de047af7444daf0d061149a7d))
* **remove unnecesary devdependencies:** rmeove innecesary devDependencies ([1000f68](https://github.com/kha333n/react-sortablejs/commit/1000f68f5f6b62d04798e746bfd8eda8ddbf247c))
* **semantic:** adds missing github plugin ([f6a7cca](https://github.com/kha333n/react-sortablejs/commit/f6a7ccaa99d3caf9dbd01b8b45c1657af8d68a5d))
* **semantic:** use dist/** glob ([76d1ba0](https://github.com/kha333n/react-sortablejs/commit/76d1ba06b071ec3eeec02ffb5212d99c3ef1da12))
* **semantic:** uses dist/**.* to assets ([6aa4183](https://github.com/kha333n/react-sortablejs/commit/6aa4183291d5c962db4cc5c0243df0fd70b83005))
* **types:** removes MultiDrag and Swap exports from index ([f34c861](https://github.com/kha333n/react-sortablejs/commit/f34c861ce922b230918238805bf72af59b7910c1)), closes [#179](https://github.com/kha333n/react-sortablejs/issues/179)
* **util.ts:** changes custom type Omit to extend keyof T ([9db7297](https://github.com/kha333n/react-sortablejs/commit/9db7297ecb2985122dc431a6df869833d440d861))


### Build System

* **parcel:** replace rollup with parcel 2 ([3876be2](https://github.com/kha333n/react-sortablejs/commit/3876be245ae074962d28ca64a1d00eb70131afaa))


### Code Refactoring

* help ([1cb872e](https://github.com/kha333n/react-sortablejs/commit/1cb872ef8e5869024af6d9ad29a6924697851bb5))


### Continuous Integration

* **semantic:** adds plugin @semantic/git ([5f2b28e](https://github.com/kha333n/react-sortablejs/commit/5f2b28eed9020c11f17ebcb2fca6582c52a073a5))


### Documentation

* ensure sortablejs and @types/sortablejs are peers dependencies ([1686019](https://github.com/kha333n/react-sortablejs/commit/168601998eb99de6006ee3eb453aa87770843c65))


### Features

* remove and update dependencies ([65fa886](https://github.com/kha333n/react-sortablejs/commit/65fa886f5ddc9dc06793c95b0591ed5ac101ccd6))
* **deps:** adds sortablejs and @types/sortablejs as peer dependencies ([d8c2ce4](https://github.com/kha333n/react-sortablejs/commit/d8c2ce4e5fbe6ec56035832d70c48f227ac65d77)), closes [#148](https://github.com/kha333n/react-sortablejs/issues/148)
* **deps:** adds sortablejs and @types/sortablejs as peer dependencies ([07da8b9](https://github.com/kha333n/react-sortablejs/commit/07da8b9c8f58d92c57ce91eff16fa6ace3e23efd)), closes [#148](https://github.com/kha333n/react-sortablejs/issues/148)


### Reverts

* prettier preserve semicolons ([a658d04](https://github.com/kha333n/react-sortablejs/commit/a658d04e53e48f05ebdcbb3a137283899f277a78))


### BREAKING CHANGES

* **parcel:** packagejson#module was removed because the file is no longer being generated.
* **types:** it's apparent we're import sortablejs with all plugins mounted. We've had a few
bugs come in that MultiDrag no longer exports because of version 1.12.x of sortablejs making an
accidental breaking change.
* **semantic:** pushes the changes to the git repository
* please, build for me
* peer dependencies now required
* **deps:** Users want to use their own versions of sortablejs, so we'll allow it.
* **deps:** Users want to use their own versions of sortablejs, so we'll allow it.

## [6.1.5](https://github.com/SortableJS/react-sortablejs/compare/v6.1.4...v6.1.5) (2023-06-01)


### Bug Fixes

* **react-sortable.jsx:** const newList = [...props.list].map((item) => ([c945c6d](https://github.com/SortableJS/react-sortablejs/commit/c945c6d659b952c545a23baed26caa663737c58c))

## [6.1.4](https://github.com/SortableJS/react-sortablejs/compare/v6.1.3...v6.1.4) (2022-05-31)


### Bug Fixes

* update dependencies ([b8ca5c2](https://github.com/SortableJS/react-sortablejs/commit/b8ca5c2bd9a494492f7b4865db9241b1b059a056))
* update dependencies ([8401a8c](https://github.com/SortableJS/react-sortablejs/commit/8401a8c95a216e449b91779556d53fdbd46ab768))

## [6.1.3](https://github.com/SortableJS/react-sortablejs/compare/v6.1.2...v6.1.3) (2022-05-31)


### Bug Fixes

* **react18:** add `children` to `ReactSortableProps` ([f6b4e2e](https://github.com/SortableJS/react-sortablejs/commit/f6b4e2e1fa235752348c3b4021120c2a56ea41c7))

## [6.1.2](https://github.com/SortableJS/react-sortablejs/compare/v6.1.1...v6.1.2) (2022-04-03)


### Bug Fixes

* spell 'these' incorrectly ([0656825](https://github.com/SortableJS/react-sortablejs/commit/06568255f25e99a85952950c1d5cf7ce10451924))

## [6.1.1](https://github.com/SortableJS/react-sortablejs/compare/v6.1.0...v6.1.1) (2022-02-08)


### Bug Fixes

* object-assign errors ([fde561e](https://github.com/SortableJS/react-sortablejs/commit/fde561e0b730dc7f7a664a48277b117e841c613a))


### Reverts

* prettier preserve semicolons ([a658d04](https://github.com/SortableJS/react-sortablejs/commit/a658d04e53e48f05ebdcbb3a137283899f277a78))

# [6.1.0](https://github.com/SortableJS/react-sortablejs/compare/v6.0.4...v6.1.0) (2022-01-30)


### Features

* remove and update dependencies ([65fa886](https://github.com/SortableJS/react-sortablejs/commit/65fa886f5ddc9dc06793c95b0591ed5ac101ccd6))

## [6.0.4](https://github.com/SortableJS/react-sortablejs/compare/v6.0.3...v6.0.4) (2022-01-30)


### Bug Fixes

* preserve original objects ([362cbd5](https://github.com/SortableJS/react-sortablejs/commit/362cbd57e75e02f12eff12925f7ec346a20721d9))

## [6.0.3](https://github.com/SortableJS/react-sortablejs/compare/v6.0.2...v6.0.3) (2022-01-14)


### Bug Fixes

* fix package versions ([b464971](https://github.com/SortableJS/react-sortablejs/commit/b464971d0c530c6c5fa764da13b610b3507f6378))

## [6.0.2](https://github.com/SortableJS/react-sortablejs/compare/v6.0.1...v6.0.2) (2022-01-14)


### Bug Fixes

* **remove unnecesary devdependencies:** rmeove innecesary devDependencies ([1000f68](https://github.com/SortableJS/react-sortablejs/commit/1000f68f5f6b62d04798e746bfd8eda8ddbf247c))
* infra ([1d43f97](https://github.com/SortableJS/react-sortablejs/commit/1d43f97af5c9e8278fe9367f72e7f2a5b213bbba))

## [6.0.1](https://github.com/SortableJS/react-sortablejs/compare/v6.0.0...v6.0.1) (2022-01-13)


### Bug Fixes

* allow update disabled prop at runtime ([dccdd24](https://github.com/SortableJS/react-sortablejs/commit/dccdd2476790ea795dcbc5fc39ce27abebebbd35))

# [6.0.0](https://github.com/SortableJS/react-sortablejs/compare/v5.0.5...v6.0.0) (2020-09-27)


### Bug Fixes

* **types:** removes MultiDrag and Swap exports from index ([f34c861](https://github.com/SortableJS/react-sortablejs/commit/f34c861ce922b230918238805bf72af59b7910c1)), closes [#179](https://github.com/SortableJS/react-sortablejs/issues/179)


### Build System

* **parcel:** replace rollup with parcel 2 ([3876be2](https://github.com/SortableJS/react-sortablejs/commit/3876be245ae074962d28ca64a1d00eb70131afaa))


### BREAKING CHANGES

* **parcel:** packagejson#module was removed because the file is no longer being generated.
* **types:** it's apparent we're import sortablejs with all plugins mounted. We've had a few
bugs come in that MultiDrag no longer exports because of version 1.12.x of sortablejs making an
accidental breaking change.

## [5.0.5](https://github.com/SortableJS/react-sortablejs/compare/v5.0.4...v5.0.5) (2020-09-25)


### Bug Fixes

* **util.ts:** changes custom type Omit to extend keyof T ([9db7297](https://github.com/SortableJS/react-sortablejs/commit/9db7297ecb2985122dc431a6df869833d440d861))
