<a name="1.6.0"></a>
# [1.6.0](https://github.com/lbwa/set/compare/v1.5.0...v1.6.0) (2018-08-27)


### Bug Fixes

* **axios:** correct assets remote service ([16555df](https://github.com/lbwa/set/commit/16555df))
* **axios:** correct server ip in dev mode ([1da49c1](https://github.com/lbwa/set/commit/1da49c1))
* **DEV mode:** correct dev request address ([c6e28d2](https://github.com/lbwa/set/commit/c6e28d2))
* **home scrolling:** correct scrolling behavior from home to other pages ([25281cf](https://github.com/lbwa/set/commit/25281cf))
* cancel background fixed ([0acdc10](https://github.com/lbwa/set/commit/0acdc10))
* table cell wrap ([0a678b3](https://github.com/lbwa/set/commit/0a678b3))
* **markdown-parser:** correct response schema ([3f40ee1](https://github.com/lbwa/set/commit/3f40ee1))
* **scrolling:** correct `triggerScroll` event completely ([e40222e](https://github.com/lbwa/set/commit/e40222e))


### Features

* **link:** ensure internal links is handled by vue-router rather than browser ([d3a42dd](https://github.com/lbwa/set/commit/d3a42dd))
* **request module:** add error handles for request module ([735447f](https://github.com/lbwa/set/commit/735447f))
* **writings_id:** build converting internal links module ([a740f4b](https://github.com/lbwa/set/commit/a740f4b))



<a name="1.5.0"></a>
# [1.5.0](https://github.com/lbwa/set/compare/v1.4.0...v1.5.0) (2018-08-10)


### Bug Fixes

* blog header will hidden when scroll bar in screen top in IOS browser ([517fda9](https://github.com/lbwa/set/commit/517fda9))
* **arrow-container:** horizontal alignment of arrow-container in home page ([ae3f343](https://github.com/lbwa/set/commit/ae3f343))
* **tags & tags_id:** blog-header showup problem ([34e3a75](https://github.com/lbwa/set/commit/34e3a75))
* **writings_page:** blog header display problem ([7e03b4c](https://github.com/lbwa/set/commit/7e03b4c))


### Features

* new background opacity at home page ([72669cc](https://github.com/lbwa/set/commit/72669cc))
* **writings_id:** transform tags links to SPA links rather than MPA links ([027fe07](https://github.com/lbwa/set/commit/027fe07))


### Performance Improvements

* change home-nav bg image format to svg for lower weight ([49968d7](https://github.com/lbwa/set/commit/49968d7))



<a name="1.4.0"></a>
# [1.4.0](https://github.com/lbwa/set/compare/v1.3.0...v1.4.0) (2018-08-08)


### Bug Fixes

* adjust API based on docs-server ([d06f1bd](https://github.com/lbwa/set/commit/d06f1bd))
* restore vertical alignment by flex-box, fix a bug when no specified height make vertical alignm ([1d5c55b](https://github.com/lbwa/set/commit/1d5c55b))


### Features

* **nav and recent section:** new alignment for logo component, new ([cfb623c](https://github.com/lbwa/set/commit/cfb623c))
* **recent-posts section:** new style ([d438ffa](https://github.com/lbwa/set/commit/d438ffa))
* **writings & projects:** add a shadow wrapper ([db675fd](https://github.com/lbwa/set/commit/db675fd))
* add layout &  page transitions ([2f58b12](https://github.com/lbwa/set/commit/2f58b12))


### Performance Improvements

* **blog & floating btn:** use throttle rather than debounce for better user experience ([38b5908](https://github.com/lbwa/set/commit/38b5908))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/lbwa/set/compare/v1.2.0...v1.3.0) (2018-08-03)


### Bug Fixes

* **home:** add icon height for compatibility ([482faf6](https://github.com/lbwa/set/commit/482faf6))


### Features

* define viewport for svg icon ([cd1370c](https://github.com/lbwa/set/commit/cd1370c))
* home bg-image with a grey wrapper and used to be a backup option ([e0ee1c9](https://github.com/lbwa/set/commit/e0ee1c9))
* **home:** add homeheader animation and optimize scrolling callback destruction ([d3ffaa3](https://github.com/lbwa/set/commit/d3ffaa3))
* **homeheader:** a functionality for scorlling ([feb1140](https://github.com/lbwa/set/commit/feb1140))
* **lib/utils:** add requestAnimationFrame to lib/utils ([e91639d](https://github.com/lbwa/set/commit/e91639d))


### Performance Improvements

* **blog,baseFBtn:** optimize scrolling callback destruction ([b73545c](https://github.com/lbwa/set/commit/b73545c))
* **throttle:** optimize requestAnimationFrame ([a6e6974](https://github.com/lbwa/set/commit/a6e6974))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/lbwa/set/compare/v1.1.0...v1.2.0) (2018-07-31)


### Bug Fixes

* compatible with scroll behavior on IOS browser ([c417063](https://github.com/lbwa/set/commit/c417063))
* **floatingBtn:** a scrolling bug on desktop Chrome 68 ([e6ba784](https://github.com/lbwa/set/commit/e6ba784))
* **home:** correct center layout for arrow ([972c388](https://github.com/lbwa/set/commit/972c388))
* **recent-section:** correct recentPosts default value ([9c334e7](https://github.com/lbwa/set/commit/9c334e7))


### Features

* add floating button for going back to top ([0b96f8c](https://github.com/lbwa/set/commit/0b96f8c))
* add language head tag for every unique page ([941dd58](https://github.com/lbwa/set/commit/941dd58))
* add x-ua-compatile meta tag ([8a1eddf](https://github.com/lbwa/set/commit/8a1eddf))
* **home-footer:** add home footer ([7833106](https://github.com/lbwa/set/commit/7833106))
* support beginning animations in home page ([8816e5c](https://github.com/lbwa/set/commit/8816e5c))
* **blog:** new layout for blog page ([b0b218e](https://github.com/lbwa/set/commit/b0b218e))
* **home:** add background color of recent section ([40184b8](https://github.com/lbwa/set/commit/40184b8))
* **home:** add readmore button ([2dc82fd](https://github.com/lbwa/set/commit/2dc82fd))
* **home:** add recent posts section ([b520dfd](https://github.com/lbwa/set/commit/b520dfd))
* **home:** new layout for home page ([ea03899](https://github.com/lbwa/set/commit/ea03899))
* **home-header:** add home header components ([a2e208e](https://github.com/lbwa/set/commit/a2e208e))
* **style:** add style primary color shade ([8e3dbd6](https://github.com/lbwa/set/commit/8e3dbd6))


### Performance Improvements

* resize avatar in first screen ([e5bd839](https://github.com/lbwa/set/commit/e5bd839))
* use `ele.matches` rather than `[...ele.classList].indexOf` ([da7a003](https://github.com/lbwa/set/commit/da7a003))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/lbwa/set/compare/v1.0.2...v1.1.0) (2018-07-17)


### Bug Fixes

* restore correct axios base url ([5ed34b1](https://github.com/lbwa/set/commit/5ed34b1))


### Features

* add service-worker for building PWA ([eb8e43f](https://github.com/lbwa/set/commit/eb8e43f))


### Performance Improvements

* revise tags detail page and writings catalog style ([3bfc8e9](https://github.com/lbwa/set/commit/3bfc8e9))



<a name="1.0.2"></a>
## [1.0.2](https://github.com/lbwa/set/compare/v1.0.1...v1.0.2) (2018-07-16)


### Bug Fixes

* fix wrong path which is used to read cache from local storage ([d3b11ad](https://github.com/lbwa/set/commit/d3b11ad))
* **CI:** fix menu request link when bundler generate static page ([8faa86d](https://github.com/lbwa/set/commit/8faa86d))
* pages should scroll to target element when user input hash url ([f5983e7](https://github.com/lbwa/set/commit/f5983e7))
* pages should scroll to top by default when clicking title in catalog ([ddad664](https://github.com/lbwa/set/commit/ddad664))


### Features

* **projects page:** add skeleton screen for prejects page ([f913553](https://github.com/lbwa/set/commit/f913553))
* **writings_id:** implement local storage without window.sessionStorage even if disable cache ([5a3c557](https://github.com/lbwa/set/commit/5a3c557))
* store menu list to local ([d08ba8e](https://github.com/lbwa/set/commit/d08ba8e))
* use event bus to implement local storage like vuex in projects page ([63755b1](https://github.com/lbwa/set/commit/63755b1))


### Performance Improvements

* expend hover style scale in app header ([6d33ec2](https://github.com/lbwa/set/commit/6d33ec2))


### Reverts

* deprecated pages skeleton component because of suitability ([965002b](https://github.com/lbwa/set/commit/965002b))



<a name="1.0.1"></a>
## [1.0.1](https://github.com/lbwa/set/compare/v0.1.0...v1.0.1) (2018-07-12)


### Bug Fixes

* fix app header animation in writings page ([f295753](https://github.com/lbwa/set/commit/f295753))
* **tags_id page:** fix a bug which can be caused by clicking one of `a.tag-list` link margin ([f8bc4fe](https://github.com/lbwa/set/commit/f8bc4fe))


### Performance Improvements

* remove markdown meta parser module for decreasing chunk weight ([09816f3](https://github.com/lbwa/set/commit/09816f3))



<a name="0.1.0"></a>
# [0.1.0](https://github.com/lbwa/set/compare/40294e1...v0.1.0) (2018-07-11)


### Bug Fixes

* debug wrong import link in components ([26382ff](https://github.com/lbwa/set/commit/26382ff))
* fix date presentation error (month number should be plus 1) ([8a0f4e3](https://github.com/lbwa/set/commit/8a0f4e3))
* fix links in article ([14f962f](https://github.com/lbwa/set/commit/14f962f))
* fix problem that will generate wrong index link ([fb66e27](https://github.com/lbwa/set/commit/fb66e27))
* fix problem with generating wrong static link ([f4ab606](https://github.com/lbwa/set/commit/f4ab606))
* fix problem with html tag highlight ([b523c93](https://github.com/lbwa/set/commit/b523c93))
* refresh filename in `_posts` files, prevent uppercase problem in node js ([90a27e8](https://github.com/lbwa/set/commit/90a27e8))
* refresh filename in `_posts` files, prevent uppercase problem in node js ([e03a495](https://github.com/lbwa/set/commit/e03a495))
* reivse underline style of header button when it is selected on mobile device ([0541539](https://github.com/lbwa/set/commit/0541539))


### Features

* `fs` module has been replace by `axios` module ([a6c1261](https://github.com/lbwa/set/commit/a6c1261))
* add app footer component ([c42334c](https://github.com/lbwa/set/commit/c42334c))
* add app header animation ([e3d60ef](https://github.com/lbwa/set/commit/e3d60ef))
* add article page css ([d235920](https://github.com/lbwa/set/commit/d235920))
* add initial tags page ([6d2db8f](https://github.com/lbwa/set/commit/6d2db8f))
* add meta information css ([7c37c5d](https://github.com/lbwa/set/commit/7c37c5d))
* add mobile header ([b127ceb](https://github.com/lbwa/set/commit/b127ceb))
* add tag route from article to tags page ([9f5382e](https://github.com/lbwa/set/commit/9f5382e))
* add tags page ([fb37b78](https://github.com/lbwa/set/commit/fb37b78))
* build blog catalog generator ([61360c4](https://github.com/lbwa/set/commit/61360c4))
* build sass variables ([2903dba](https://github.com/lbwa/set/commit/2903dba))
* complete mobile header animations ([c3e109f](https://github.com/lbwa/set/commit/c3e109f))
* complete tags  system ([f1d010c](https://github.com/lbwa/set/commit/f1d010c))
* construct writing index page ([162ca18](https://github.com/lbwa/set/commit/162ca18))
* dynamic title in client tab, refactor sass ([46a6aa9](https://github.com/lbwa/set/commit/46a6aa9))
* extract meta (yaml) from single markdown file ([33bc59f](https://github.com/lbwa/set/commit/33bc59f))
* inject scoped css to child component and build projects page ([2e3093d](https://github.com/lbwa/set/commit/2e3093d))
* parse markdown and highlight code ([40294e1](https://github.com/lbwa/set/commit/40294e1))
* responsive web design ([2db4741](https://github.com/lbwa/set/commit/2db4741))
* support loading animation in tags page ([334b832](https://github.com/lbwa/set/commit/334b832))
* tags system prototype ([be26a4d](https://github.com/lbwa/set/commit/be26a4d))


### Performance Improvements

* avatar deoubce and reset h tag sass in article ([68cfaa8](https://github.com/lbwa/set/commit/68cfaa8))
* new highlight strategy ([aa69124](https://github.com/lbwa/set/commit/aa69124))
* optimize app header animation(remove $refs), writings page link(by vue router, not default bro ([b542b70](https://github.com/lbwa/set/commit/b542b70))
* optimize components according to lighthouse ([e499e47](https://github.com/lbwa/set/commit/e499e47))



