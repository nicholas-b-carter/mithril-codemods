# Changes

## 3.5.2

- feat: controller.onunload transform should search more aggressively

## 3.5.1

- docs: document latest change

## 3.5.0

- feat: m.route.buildQueryString/parseQueryString rewritten to m.buildQueryString/parseQueryString (#30)

## 3.4.3

- fix: handle more than just m("...") in raw vnode rule
- fix: always rename controller properties to oninit (#25)

## 3.4.2

- fix: don't re-apply view(ctrl) -> view(vnode) transform

## 3.4.1

- docs: use mithril.js.org for links

## 3.4.0

- docs: Readme formatting (#24)
- feat: controller.onunload rewritten to controller.onremove (#23)

## 3.3.1

- fix: Expressions, not statements for m.route()

## 3.3.0

- refactor: use console.warn() instead of comments
- refactor: always run warnings last
- feat: warn about m.redraw.strategy()
- refactor: remove m.route.param rewriting

## 3.2.1

- chore: set up travis publishing
- test: travis tests on node 6/7/4

## 3.2.0

- docs: change-log added
- fix: support more m.route.param() types

## 3.1.0

- Alignment tweak
- Remove unecessary protections
- Not impossible to warn about, fortunately
- Warn about instances of m.deferred
- Sync up w/ work done
- Make sure every transform tracks stats
- Strip m.startComputation/m.endComputation
- Fix mithril documentation links
- Clean up
- Add missing transforms, tweak formatting
- Add issue template

## 3.0.1

- Don't really care about vulns for a CLI tool

## 3.0.0

- Better exclusions
- Warnings
- m.sync -> Promise.all
- Formatting
- Add coverage, rename ospec to tests
- Unused
- Clean up NPM package contents
- execa@0.5.0
- Make package.json match what's on NPM
- Badges! :pager:
- Remove m.request.run stuff
- More arrow-functiony
- m.sync -> Promise.all
- Formatting

## 2.0.2

- Readme updates

## 2.0.1

- ESLint

## 2.0.0

- Bring back safe/unsafe, tweak CLI
- Expand view rewriting to fn(ctrl)
- Clean up event cancelling
- Rework upwards() usage & features
- Use "function" for arrow support
- Use "Function" type in case arrows are involved
- Safer replacement via identifier.replace
- Strip empty config functions after transform
- Try & handle more config init cases (#17)
- Add migration doc link
- Prepend svg element href attr w/ xlink namespace (#16)
- Rename first param in controller functions to vnode (#15)
- Doc update & transform planning

## 1.1.2

- Attempt to fix bin line-endings
- Make m.route.get/set transform safer (#14)

## 1.1.1

- Take advantage of matchNode/j.match (#9)

## 1.1.0

- Fix lint issues
- Add view transform (no migration docs?!?)
- view function rewriting (#7)
- LTS & stable only
- Clean up filtering a bit
- Tests trim input to disparity (just in case)
- Support m.module and use oncreate instead of oninit (#5) (Rasmus Porsager)

## 1.0.2

- Remove a false-positive
- Fix bad check
- Robustify
- Robustify

## 1.0.1

- Minor cleanups

## 1.0.0

- Initial release


