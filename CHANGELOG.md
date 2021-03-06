### 5.3.0

* apply === rule with null expection - **[@dbushong](https://github.com/dbushong)** [#25](https://github.com/groupon/javascript/pull/25)
  - [`c727390`](https://github.com/groupon/javascript/commit/c72739026db07af40b79849a1f80ef7082984f3c) **feat:** apply === rule with null expection


### 5.2.1

* Apply latest nlm generator - **[@markowsiak](https://github.com/markowsiak)** [#24](https://github.com/groupon/javascript/pull/24)
  - [`c6a3316`](https://github.com/groupon/javascript/commit/c6a3316472d23ce6ca801c09ef4a4230dd496c07) **chore:** apply latest generator


### 5.2.0

* resurrect `no-console` as `error` - **[@dbushong](https://github.com/dbushong)** [#23](https://github.com/groupon/javascript/pull/23)
  - [`f66914e`](https://github.com/groupon/javascript/commit/f66914e8b3770d6c2538cb2af1a41cf19ee1b22c) **feat:** resurrect `no-console` as `error`
  - [`57a5ff9`](https://github.com/groupon/javascript/commit/57a5ff94e63fe99e8d60174228779d583eace481) **chore:** add nvmrc for node8 dev compliance


### 5.1.1

* fix: set prefer-template to off for es5 - **[@markowsiak](https://github.com/markowsiak)** [#22](https://github.com/groupon/javascript/pull/22)
  - [`fb601e6`](https://github.com/groupon/javascript/commit/fb601e612117e262695386ab40f0cc63a15aaac1) **fix:** set prefer-template to off for es5


### 5.1.0

* feat: support object spread and mjs - **[@jkrems](https://github.com/jkrems)** [#21](https://github.com/groupon/javascript/pull/21)
  - [`344fe64`](https://github.com/groupon/javascript/commit/344fe6447c9b284d7d6edb7e088d98ae59342e33) **feat:** support object spread and mjs


### 5.0.0

#### Breaking Changes

This switches our linting to an entirely new
set of rules. For the most part we're trying to stay consistent
with the old format to reduce churn but it explicitly is a departure.

*See: [`559c99f`](https://github.com/groupon/javascript/commit/559c99f6d3c153ca13d78aaed164a7a73e3c48e7)*

#### Commits

* Simplify package structure and decouple from Airbnb - **[@jkrems](https://github.com/jkrems)** [#20](https://github.com/groupon/javascript/pull/20)
  - [`559c99f`](https://github.com/groupon/javascript/commit/559c99f6d3c153ca13d78aaed164a7a73e3c48e7) **refactor:** Drop dependency on lerna & airbnb
  - [`98ce778`](https://github.com/groupon/javascript/commit/98ce778b0ded4438f10461f4b7d519e55a8c8eba) **feat:** Add prettier for node 6 config
  - [`15b1ec6`](https://github.com/groupon/javascript/commit/15b1ec6ec3b386fe399c3287e3cac61d4d3209f9) **feat:** Bring back basic bug prevention rules
  - [`5c3d500`](https://github.com/groupon/javascript/commit/5c3d500b33717beb0f2decbbbd7c321786d4c6dc) **fix:** Use proper import syntax
  - [`f849bdc`](https://github.com/groupon/javascript/commit/f849bdcee338a835f2b5006c203144be53cd4b7d) **feat:** Add import checks
  - [`366813b`](https://github.com/groupon/javascript/commit/366813bc72b71b9fe3a2bb12f83f766921e80f3a) **fix:** Add missing test file pattern
  - [`94d539c`](https://github.com/groupon/javascript/commit/94d539c48aad5de230301e5489e31cc18566f526) **refactor:** Run tests on node 8
  - [`f898741`](https://github.com/groupon/javascript/commit/f898741f09ef28f74c5b862334feb1118dcefa6f) **refactor:** Reuse rule list
  - [`1396cb1`](https://github.com/groupon/javascript/commit/1396cb18d1d2a08fa35bb0d57742d4b999fedaaf) **test:** Verify ES5 vs. ES6 behavior
  - [`5eff6a0`](https://github.com/groupon/javascript/commit/5eff6a053f1c9b032a2808d30b40b3da422dd172) **test:** Enable coffee tests
  - [`ef674e4`](https://github.com/groupon/javascript/commit/ef674e431544a0ef247c3a8f1315de2af5c617b3) **feat:** Bring back style linting
  - [`c42aeb7`](https://github.com/groupon/javascript/commit/c42aeb7213795f96ea9de14cc1d06a061c57d35d) **fix:** Add more --fix test cases
  - [`f4d8eb6`](https://github.com/groupon/javascript/commit/f4d8eb69593c8c94a6bf6a2bd78a7f1801a4452d) **test:** Add test case of newline after import
  - [`f9cdaaf`](https://github.com/groupon/javascript/commit/f9cdaafa737eee65a9743b40bdc1dfd4f5859ab4) **docs:** Add links to opinion rules
  - [`ff1ddca`](https://github.com/groupon/javascript/commit/ff1ddca281790b84cd2822cb057ad3635e5b1087) **fix:** Remove console.log
  - [`38d19d3`](https://github.com/groupon/javascript/commit/38d19d3998353cef2248c3c611647baee40114f8) **style:** Self-lint with latest deps
  - [`6dc9135`](https://github.com/groupon/javascript/commit/6dc9135e1d5ef3f7280a056bc22f2ed956ef27b6) **fix:** Lint self for node 4
  - [`74df77c`](https://github.com/groupon/javascript/commit/74df77c63147ea18754c7b8f41ed3ff9877326de) **docs:** Update readme with updated overview
  - [`decdae0`](https://github.com/groupon/javascript/commit/decdae0c02340c8f6a03cd3be918595d0629ed27) **docs:** Elaborate on rule categories
  - [`b8c7123`](https://github.com/groupon/javascript/commit/b8c71238e8722d1f72147f8b9f92084ce36da272) **chore:** Include stylint config in package
  - [`7951d90`](https://github.com/groupon/javascript/commit/7951d90b874f18fc9edbd988a8ee17dba66ff12b) **feat:** Port more airbnb rules
  - [`7041f12`](https://github.com/groupon/javascript/commit/7041f121035b67d6b15c9d38c1ab83d3776da745) **feat:** Cover more variable conventions
  - [`3a93a0c`](https://github.com/groupon/javascript/commit/3a93a0c0b249c12263513fcc6632b87ee127abad) **chore:** Add nlm & license headers
  - [`3a9e573`](https://github.com/groupon/javascript/commit/3a9e5735f302a581a8d1bbdfc8f576c6d68ff1e0) **chore:** Ignore package-lock.json since it's not stable
  - [`2952567`](https://github.com/groupon/javascript/commit/2952567090982a54af18f95646ea3c22cc98b9ed) **chore:** Rename and clean up dependencies
  - [`64630f8`](https://github.com/groupon/javascript/commit/64630f802ff3a0da665c065460d3b91b4a1af0be) **refactor:** Back out coffee & stylus linting
  - [`4d86376`](https://github.com/groupon/javascript/commit/4d863762efc21e3e843cd29de0afb3875a9b20ff) **chore:** Apply latest generator
  - [`4270b97`](https://github.com/groupon/javascript/commit/4270b97bd791cc8c6a09e27c8264256b1d80866f) **docs:** Clarify our lack of compliance with airbnb
