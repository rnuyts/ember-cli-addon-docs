Deprecated as of 10.7.0. highlight(lang, code, ...args) has been deprecated.
Deprecated as of 10.7.0. Please use highlight(code, options) instead.
https://github.com/highlightjs/highlight.js/issues/2277






## v5.0.0 (2022-06-30)

#### :boom: Breaking Change
* [#1219](https://github.com/ember-learn/ember-cli-addon-docs/pull/1219) Drop Node.js 12 support ([@SergeAstapov](https://github.com/SergeAstapov))
* [#1134](https://github.com/ember-learn/ember-cli-addon-docs/pull/1134) update docs viewer ([@miguelcobain](https://github.com/miguelcobain))
* [#1133](https://github.com/ember-learn/ember-cli-addon-docs/pull/1133) update markdown rendering approach ([@miguelcobain](https://github.com/miguelcobain))
* [#1128](https://github.com/ember-learn/ember-cli-addon-docs/pull/1128) update docs header ([@miguelcobain](https://github.com/miguelcobain))
* [#1130](https://github.com/ember-learn/ember-cli-addon-docs/pull/1130) update docs-link ([@miguelcobain](https://github.com/miguelcobain))
* [#1126](https://github.com/ember-learn/ember-cli-addon-docs/pull/1126) delete docs-svg-icon component ([@miguelcobain](https://github.com/miguelcobain))
* [#1120](https://github.com/ember-learn/ember-cli-addon-docs/pull/1120) Update to glimmer components ([@miguelcobain](https://github.com/miguelcobain))

#### :rocket: Enhancement
* [#1218](https://github.com/ember-learn/ember-cli-addon-docs/pull/1218) Remove extra whitespace in `<DocsLink />` component ([@SergeAstapov](https://github.com/SergeAstapov))
* [#1164](https://github.com/ember-learn/ember-cli-addon-docs/pull/1164) Support v2 addon format ([@SergeAstapov](https://github.com/SergeAstapov))
* [#1125](https://github.com/ember-learn/ember-cli-addon-docs/pull/1125) update docs-logo component ([@miguelcobain](https://github.com/miguelcobain))
* [#1124](https://github.com/ember-learn/ember-cli-addon-docs/pull/1124) update docs-keyboard-shortcuts ([@miguelcobain](https://github.com/miguelcobain))

#### :bug: Bug Fix
* [#1137](https://github.com/ember-learn/ember-cli-addon-docs/pull/1137) fix(config): use runtime config instead of embroider generated one ([@jkeen](https://github.com/jkeen))

#### :memo: Documentation
* [#1123](https://github.com/ember-learn/ember-cli-addon-docs/pull/1123) update docs hero docs ([@miguelcobain](https://github.com/miguelcobain))

#### :house: Internal
* [#1143](https://github.com/ember-learn/ember-cli-addon-docs/pull/1143) chore(config): remove all usage of ember-get-config ([@anehx](https://github.com/anehx))
* [#1135](https://github.com/ember-learn/ember-cli-addon-docs/pull/1135) Remove ember-decorators and ember-component-css ([@rwwagner90](https://github.com/rwwagner90))
* [#955](https://github.com/ember-learn/ember-cli-addon-docs/pull/955) Ember and dep updates ([@rwwagner90](https://github.com/rwwagner90))
* [#1129](https://github.com/ember-learn/ember-cli-addon-docs/pull/1129) update modal dialog ([@miguelcobain](https://github.com/miguelcobain))
* [#1127](https://github.com/ember-learn/ember-cli-addon-docs/pull/1127) update api components ([@miguelcobain](https://github.com/miguelcobain))
* [#1117](https://github.com/ember-learn/ember-cli-addon-docs/pull/1117) update controllers syntax ([@miguelcobain](https://github.com/miguelcobain))
* [#1118](https://github.com/ember-learn/ember-cli-addon-docs/pull/1118) update services ([@miguelcobain](https://github.com/miguelcobain))
* [#1116](https://github.com/ember-learn/ember-cli-addon-docs/pull/1116) update ember-data related syntax ([@miguelcobain](https://github.com/miguelcobain))

#### Committers: 5
- Jeff Keen ([@jkeen](https://github.com/jkeen))
- Jonas Metzener ([@anehx](https://github.com/anehx))
- Miguel Andrade ([@miguelcobain](https://github.com/miguelcobain))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))

## v4.2.2 (2022-02-08)

#### :bug: Bug Fix
* [#1108](https://github.com/ember-learn/ember-cli-addon-docs/pull/1108) Fix no implicit this deprecation in docs-demo component ([@nickschot](https://github.com/nickschot))
* [#1045](https://github.com/ember-learn/ember-cli-addon-docs/pull/1045) Fix typo in <DocsKeyboardShortcuts /> component ([@SergeAstapov](https://github.com/SergeAstapov))

#### :memo: Documentation
* [#1083](https://github.com/ember-learn/ember-cli-addon-docs/pull/1083) Consolidate some docs ([@rwwagner90](https://github.com/rwwagner90))

#### :house: Internal
* [#1084](https://github.com/ember-learn/ember-cli-addon-docs/pull/1084) ember-get-config 1.0.0, force embroider < 0.50 ([@rwwagner90](https://github.com/rwwagner90))
* [#1019](https://github.com/ember-learn/ember-cli-addon-docs/pull/1019) Set default CI config blueprints to run all builds ([@SergeAstapov](https://github.com/SergeAstapov))

#### Committers: 3
- Nick Schot ([@nickschot](https://github.com/nickschot))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))

## v4.2.1 (2021-12-02)

## v4.2.0 (2021-12-02)

#### :rocket: Enhancement
* [#1016](https://github.com/ember-learn/ember-cli-addon-docs/pull/1016) Closes [#195](https://github.com/ember-learn/ember-cli-addon-docs/issues/195) use angle bracket component names ([@miguelcobain](https://github.com/miguelcobain))

#### :house: Internal
* [#1031](https://github.com/ember-learn/ember-cli-addon-docs/pull/1031) Add babel.config.js to .npmignore ([@SergeAstapov](https://github.com/SergeAstapov))

#### Committers: 2
- Miguel Andrade ([@miguelcobain](https://github.com/miguelcobain))
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))

## v4.1.0 (2021-12-01)

#### :bug: Bug Fix
* [#1021](https://github.com/ember-learn/ember-cli-addon-docs/pull/1021) Fix LinkTo usage and explicitly provide `@route` and `@models` arguments ([@SergeAstapov](https://github.com/SergeAstapov))
* [#978](https://github.com/ember-learn/ember-cli-addon-docs/pull/978) Fixes broken deployment with ember-auto-import@2 ([@scalvert](https://github.com/scalvert))

#### :memo: Documentation
* [#1017](https://github.com/ember-learn/ember-cli-addon-docs/pull/1017) Fix typo in addon status callout ([@SergeAstapov](https://github.com/SergeAstapov))
* [#981](https://github.com/ember-learn/ember-cli-addon-docs/pull/981) Fix typo at navigation ([@brkn](https://github.com/brkn))

#### :house: Internal
* [#1010](https://github.com/ember-learn/ember-cli-addon-docs/pull/1010) Update linting, bump deps ([@rwwagner90](https://github.com/rwwagner90))
* [#1015](https://github.com/ember-learn/ember-cli-addon-docs/pull/1015) chore: import LinkComponent from `ember/legacy-built-in-components` ([@gilest](https://github.com/gilest))
* [#1006](https://github.com/ember-learn/ember-cli-addon-docs/pull/1006) chore(deps): drop ember-href-to ([@gilest](https://github.com/gilest))

#### Committers: 5
- Berkan Ünal ([@brkn](https://github.com/brkn))
- Giles Thompson ([@gilest](https://github.com/gilest))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))
- Steve Calvert ([@scalvert](https://github.com/scalvert))

## v4.0.3 (2021-10-07)

## v4.0.2 (2021-09-20)

#### :bug: Bug Fix
* [#940](https://github.com/ember-learn/ember-cli-addon-docs/pull/940) fix: yarn.lock with ember-modal-dialog commit ([@ndekeister-us](https://github.com/ndekeister-us))

#### Committers: 1
- Nathanaël Dekeister ([@ndekeister-us](https://github.com/ndekeister-us))

## v4.0.1 (2021-09-17)

#### :bug: Bug Fix
* [#939](https://github.com/ember-learn/ember-cli-addon-docs/pull/939) fix: move @glimmer/component and @glimmer/tracking in dependencies ([@ndekeister-us](https://github.com/ndekeister-us))

#### Committers: 1
- Nathanaël Dekeister ([@ndekeister-us](https://github.com/ndekeister-us))

## v4.0.0 (2021-09-15)

#### :boom: Breaking Change
* [#933](https://github.com/ember-learn/ember-cli-addon-docs/pull/933) Require ember-auto-import 2 ([@rwwagner90](https://github.com/rwwagner90))

#### :rocket: Enhancement
* [#932](https://github.com/ember-learn/ember-cli-addon-docs/pull/932) Ember 4 support ([@rwwagner90](https://github.com/rwwagner90))
* [#923](https://github.com/ember-learn/ember-cli-addon-docs/pull/923) Bump some deps, update Ember to 3.28 ([@rwwagner90](https://github.com/rwwagner90))
* [#890](https://github.com/ember-learn/ember-cli-addon-docs/pull/890) Remove liquid fire ([@rwwagner90](https://github.com/rwwagner90))

#### :bug: Bug Fix
* [#921](https://github.com/ember-learn/ember-cli-addon-docs/pull/921) Resolve issue with sidebar showing incorrectly on mobile ([@jkeen](https://github.com/jkeen))

#### :house: Internal
* [#934](https://github.com/ember-learn/ember-cli-addon-docs/pull/934) Use colocated components ([@rwwagner90](https://github.com/rwwagner90))
* [#891](https://github.com/ember-learn/ember-cli-addon-docs/pull/891) Fix highlightjs deprecation ([@rwwagner90](https://github.com/rwwagner90))
* [#887](https://github.com/ember-learn/ember-cli-addon-docs/pull/887) Bump some deps, fix some lint ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 4
- Jeff Keen ([@jkeen](https://github.com/jkeen))
- Nathanaël Dekeister ([@ndekeister-us](https://github.com/ndekeister-us))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v3.0.0 (2021-05-31)

#### :boom: Breaking Change
* [#854](https://github.com/ember-learn/ember-cli-addon-docs/pull/854) Drop ember-concurrency 1.x support, fix ember-keyboard deprecations ([@rwwagner90](https://github.com/rwwagner90))

#### :house: Internal
* [#855](https://github.com/ember-learn/ember-cli-addon-docs/pull/855) Ember 3.26 ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 2
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v2.0.0 (2021-05-25)

#### :boom: Breaking Change
* [#842](https://github.com/ember-learn/ember-cli-addon-docs/pull/842) ember-modal-dialog 4.0.0-alpha.0, Drop support for <=Ember 3.19, Node 10 ([@elwayman02](https://github.com/elwayman02))
* [#693](https://github.com/ember-learn/ember-cli-addon-docs/pull/693) Remove pods support ([@rwwagner90](https://github.com/rwwagner90))
* [#692](https://github.com/ember-learn/ember-cli-addon-docs/pull/692) Remove ESDoc support ([@rwwagner90](https://github.com/rwwagner90))

#### :rocket: Enhancement
* [#767](https://github.com/ember-learn/ember-cli-addon-docs/pull/767) Update to ember-router-scroll v4 ([@Windvis](https://github.com/Windvis))
* [#747](https://github.com/ember-learn/ember-cli-addon-docs/pull/747) Remove brand bg color ([@rwwagner90](https://github.com/rwwagner90))

#### :house: Internal
* [#831](https://github.com/ember-learn/ember-cli-addon-docs/pull/831) Fixed deprecations this.property-fallback, with, and positional linkt… ([@bgantzler](https://github.com/bgantzler))
* [#727](https://github.com/ember-learn/ember-cli-addon-docs/pull/727) Update html-entities ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 5
- Jordan Hawker ([@elwayman02](https://github.com/elwayman02))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- Sam Van Campenhout ([@Windvis](https://github.com/Windvis))
- [@bgantzler](https://github.com/bgantzler)
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v1.0.0 (2020-12-10)

#### :boom: Breaking Change
* [#668](https://github.com/ember-learn/ember-cli-addon-docs/pull/668) Use postcss for sass, convert to angle brackets, update highlight.js ([@rwwagner90](https://github.com/rwwagner90))
* [#553](https://github.com/ember-learn/ember-cli-addon-docs/pull/553) Minimum 3.x series for ember-data addon ([@snewcomer](https://github.com/snewcomer))

#### :house: Internal
* [#671](https://github.com/ember-learn/ember-cli-addon-docs/pull/671) Start converting to native classes ([@rwwagner90](https://github.com/rwwagner90))
* [#585](https://github.com/ember-learn/ember-cli-addon-docs/pull/585) Add test for both ember-concurrency v1 and v2 ([@maxfierke](https://github.com/maxfierke))

#### Committers: 5
- Isaac Lee ([@ijlee2](https://github.com/ijlee2))
- Max Fierke ([@maxfierke](https://github.com/maxfierke))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v0.10.0 (2020-09-08)

#### :rocket: Enhancement
* [#552](https://github.com/ember-learn/ember-cli-addon-docs/pull/552) Add ember-data as a peer dep ([@snewcomer](https://github.com/snewcomer))
* [#516](https://github.com/ember-learn/ember-cli-addon-docs/pull/516) ember-href-to 4.0.0 ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 3
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v0.9.0 (2020-08-10)

#### :boom: Breaking Change
* [#495](https://github.com/ember-learn/ember-cli-addon-docs/pull/495) Ember 3.20, update ember-fetch, bump deps ([@rwwagner90](https://github.com/rwwagner90))

#### :rocket: Enhancement
* [#496](https://github.com/ember-learn/ember-cli-addon-docs/pull/496) Update ember-cli-clipboard ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 2
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v0.8.0 (2020-08-01)

#### :boom: Breaking Change
* [#475](https://github.com/ember-learn/ember-cli-addon-docs/pull/475) ember-cli 3.18, some lint fixes ([@rwwagner90](https://github.com/rwwagner90))
* [#474](https://github.com/ember-learn/ember-cli-addon-docs/pull/474) Remove ember-component-css, drop Ember 2.18 support ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 1
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))

## v0.7.0 (2020-05-05)

#### :boom: Breaking Change
* [#466](https://github.com/ember-learn/ember-cli-addon-docs/pull/466) Ember 3.17 updates, drop node 8 support ([@rwwagner90](https://github.com/rwwagner90))

#### :rocket: Enhancement
* [#472](https://github.com/ember-learn/ember-cli-addon-docs/pull/472) Adds tailwind list style classes ([@rwwagner90](https://github.com/rwwagner90))
* [#469](https://github.com/ember-learn/ember-cli-addon-docs/pull/469) [feature] be able to render tables from markdown ([@gabrielcsapo](https://github.com/gabrielcsapo))
* [#444](https://github.com/ember-learn/ember-cli-addon-docs/pull/444) Use Tailwind's scrolling-touch instead of custom overflow-momentum ([@josemarluedke](https://github.com/josemarluedke))

#### :bug: Bug Fix
* [#451](https://github.com/ember-learn/ember-cli-addon-docs/pull/451) fix deprecation computed-property.override by adding setters ([@kturney](https://github.com/kturney))
* [#450](https://github.com/ember-learn/ember-cli-addon-docs/pull/450) fix deprecation ember-data:default-serializer ([@kturney](https://github.com/kturney))
* [#452](https://github.com/ember-learn/ember-cli-addon-docs/pull/452) fix array helper clobbering built in helper ([@kturney](https://github.com/kturney))
* [#443](https://github.com/ember-learn/ember-cli-addon-docs/pull/443) Fix docs heading styles due to Tailwind's v1 preflight ([@josemarluedke](https://github.com/josemarluedke))

#### :memo: Documentation
* [#461](https://github.com/ember-learn/ember-cli-addon-docs/pull/461) Use section instead of item for Introduction ([@elwayman02](https://github.com/elwayman02))
* [#449](https://github.com/ember-learn/ember-cli-addon-docs/pull/449) tip: Visual Studio Code addon-docs integration ([@lifeart](https://github.com/lifeart))
* [#459](https://github.com/ember-learn/ember-cli-addon-docs/pull/459) Fix file extension in docs ([@elwayman02](https://github.com/elwayman02))
* [#456](https://github.com/ember-learn/ember-cli-addon-docs/pull/456) Fix doc typo ([@elwayman02](https://github.com/elwayman02))
* [#448](https://github.com/ember-learn/ember-cli-addon-docs/pull/448) Document using standalone apps ([@rwwagner90](https://github.com/rwwagner90))

#### Committers: 6
- Alex Kanunnikov ([@lifeart](https://github.com/lifeart))
- Gabriel Csapo ([@gabrielcsapo](https://github.com/gabrielcsapo))
- Jordan Hawker ([@elwayman02](https://github.com/elwayman02))
- Josemar Luedke ([@josemarluedke](https://github.com/josemarluedke))
- Kyle Turney ([@kturney](https://github.com/kturney))
- Robert Wagner ([@rwwagner90](https://github.com/rwwagner90))

# Change log

Releases (along with upgrade instructions) are documented on the Github [Releases](https://github.com/ember-learn/ember-cli-addon-docs/releases) page.
