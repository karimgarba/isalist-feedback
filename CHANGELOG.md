# Changelog

## [4.2.0](https://github.com/karimgarba/isaList/compare/v4.1.7...v4.2.0) (2026-09-07)


### Features

* **discover:** K-drama and Korean film rails ([#189](https://github.com/karimgarba/isaList/issues/189)) ([1225d99](https://github.com/karimgarba/isaList/commit/1225d99da4ffecf1f4ce122f8b83c088337f1799))
* **for-you:** bold refactor — leveled cards, details affordance, sectioned feed ([a09de00](https://github.com/karimgarba/isaList/commit/a09de00c4d72929ba05151e89ff109a1939f975e))
* **for-you:** sectioned feed + leveled cards + details ([063183d](https://github.com/karimgarba/isaList/commit/063183d82592bbe3ed701f04487c0683c19f6b24))
* **library:** make rewatch count visible and editable ([8a21b44](https://github.com/karimgarba/isaList/commit/8a21b44ace6f74bfabf3a3439bfebba95c205e08))
* **library:** make rewatch count visible and editable ([23593b3](https://github.com/karimgarba/isaList/commit/23593b31be49b84b3e5bc21ad54cea636940378b))
* **lists:** attribute each entry to who added it ([f0ad739](https://github.com/karimgarba/isaList/commit/f0ad7395dbbc727baf08c67098c764f9a5abd940))
* **lists:** editable entries + per-list collaborator ratings ([6326e73](https://github.com/karimgarba/isaList/commit/6326e7316a6f0ac0da7df95bab4d398bece8a32a))
* **lists:** editable entries + per-list collaborator ratings ([5a896fe](https://github.com/karimgarba/isaList/commit/5a896fe7a8fa75b7178458d9aa299abf488f0327))
* **onboarding:** stop asking people to rate things they haven't seen ([#172](https://github.com/karimgarba/isaList/issues/172)) ([35973ec](https://github.com/karimgarba/isaList/commit/35973ec29c4780eccb2da9b5f98300ef722aa14b))
* **search:** drive type and year filters server-side (Phase A frontend) ([9ed4778](https://github.com/karimgarba/isaList/commit/9ed477834630e5bf67976999f8e90990662c6332))
* **search:** faceted catalogue search + year-range filters (Phase A) ([8b4b7c0](https://github.com/karimgarba/isaList/commit/8b4b7c0c073efca9e358482eb59758d2d6b2f3a0))
* **search:** server-side genre + language filters via facets vocabulary ([06a6445](https://github.com/karimgarba/isaList/commit/06a644597eb0ce4e7ad9f29fab31fa92831d9c77))
* **stats:** bold visual refresh of the Stats page ([552756c](https://github.com/karimgarba/isaList/commit/552756c030c1571d7103430f44f13c081e892bda))
* **stats:** visual dashboard redesign (charts) ([f2ee3e8](https://github.com/karimgarba/isaList/commit/f2ee3e89442dd7cdfc8cd79a837d248474b3457b))
* **titles:** backfill related recs from catalogue, add rec filters ([c7c154d](https://github.com/karimgarba/isaList/commit/c7c154d65d9a20434fe9db7dcf29441f09b33d86))
* **titles:** catalogue-neighbour backfill + related-recs filtering (Phase D) ([c3d2867](https://github.com/karimgarba/isaList/commit/c3d2867fdcb8cfc6f33f887767abb33685114467))


### Bug Fixes

* **lists:** hide the watched-together toggle while rating/noting an entry ([f36286d](https://github.com/karimgarba/isaList/commit/f36286d1f6f6dea921766a0cee1e4e375c18666d))
* **lists:** hide watched-together toggle while rating an entry ([950c7b1](https://github.com/karimgarba/isaList/commit/950c7b1b5ed374da0dbdd242aef68f1918df2320))
* **lists:** quiet the "added by" attribution row ([32b911a](https://github.com/karimgarba/isaList/commit/32b911a33e029085ea1073d068282cf5181eb604))
* **lists:** rate entries with emoji reactions, not 0–10 ([72c948e](https://github.com/karimgarba/isaList/commit/72c948e71de76322e19a3843dd53393099e7a338))
* **lists:** rate entries with the emoji reactions, not a 0–10 scale ([3de9afe](https://github.com/karimgarba/isaList/commit/3de9afe01cf4fd587cddf06bb338b4951cec3115))
* **title:** don't tell people a title is missing when the request failed ([#186](https://github.com/karimgarba/isaList/issues/186)) ([46ec7f8](https://github.com/karimgarba/isaList/commit/46ec7f8af315fd81e4b4198f40ddc7750d2aa246))
* **ui:** app-wide card/rail/overlap consistency sweep ([fff8b99](https://github.com/karimgarba/isaList/commit/fff8b999d99dcecfe32ec3786495f0d68e4e5de3))
* **ui:** consistent page rhythm + fix edge overlaps across pages ([bdcb2d6](https://github.com/karimgarba/isaList/commit/bdcb2d6899f682f33e84f90959756c105daf98e3))
* **ui:** consistent page spacing + fix edge overlaps across pages ([2e5291b](https://github.com/karimgarba/isaList/commit/2e5291bc84f500349c6f3d5ec81f755b33bd1d3d))
* **ui:** profile stats overflow + consistent rail card size ([323ce16](https://github.com/karimgarba/isaList/commit/323ce16c5fe80b356c0aafa2640597c3237ee42a))
* **ui:** stop profile stat tiles overflowing + unify rail card width ([a866dc2](https://github.com/karimgarba/isaList/commit/a866dc2d7e00c8ac6908df54795a0e2a94733fd9))
* **ui:** unify rail widths, fix mobile toast overlap, fix stat-header overflow ([3d99572](https://github.com/karimgarba/isaList/commit/3d99572b0d9bb42f41ad55f75499906572e13c05))


### Performance Improvements

* **api:** replace axios with fetch, 16.6 kB off first paint ([#178](https://github.com/karimgarba/isaList/issues/178)) ([1a92380](https://github.com/karimgarba/isaList/commit/1a9238000c05c2759f65ffbc510b2e79069b7230))
* **ci:** budget the bytes a first visit has to download ([#175](https://github.com/karimgarba/isaList/issues/175)) ([fe9d2e9](https://github.com/karimgarba/isaList/commit/fe9d2e91558000a284fba9ef0842d2acc77a1328))
* **search:** stop type-ahead calling TMDB and AniList for a half-typed word ([#187](https://github.com/karimgarba/isaList/issues/187)) ([5992359](https://github.com/karimgarba/isaList/commit/599235973da1a6d21bf2a2facb662b9ccf0b032f))

## [4.1.7](https://github.com/karimgarba/isaList/compare/v4.1.6...v4.1.7) (2026-08-29)


### Bug Fixes

* **search:** say why the dropdown is empty instead of not opening ([#169](https://github.com/karimgarba/isaList/issues/169)) ([91e9e87](https://github.com/karimgarba/isaList/commit/91e9e878c3b7c7f481f762163b6891180799250b))

## [4.1.6](https://github.com/karimgarba/isaList/compare/v4.1.5...v4.1.6) (2026-08-29)


### Bug Fixes

* **pwa:** don't precache during load, or reload over what you're typing ([#166](https://github.com/karimgarba/isaList/issues/166)) ([889dad0](https://github.com/karimgarba/isaList/commit/889dad06d68222723630c574a1ea166644b34215))

## [4.1.5](https://github.com/karimgarba/isaList/compare/v4.1.4...v4.1.5) (2026-08-29)


### Bug Fixes

* **search:** stop firing a search on every keystroke ([#165](https://github.com/karimgarba/isaList/issues/165)) ([c039a61](https://github.com/karimgarba/isaList/commit/c039a61e94851d6679852ffe28c62b886b9e5d68))
* **ui:** install prompt had no background, and guard the whole class ([#163](https://github.com/karimgarba/isaList/issues/163)) ([7bae188](https://github.com/karimgarba/isaList/commit/7bae18817c26085efab9779588aa136418674bce))

## [4.1.4](https://github.com/karimgarba/isaList/compare/v4.1.3...v4.1.4) (2026-08-29)


### Bug Fixes

* **pwa:** actually apply updates, instead of serving the previous build ([#162](https://github.com/karimgarba/isaList/issues/162)) ([49fb034](https://github.com/karimgarba/isaList/commit/49fb03450787da1b65a0c8adc36c34a75fd0d143))

## [4.1.3](https://github.com/karimgarba/isaList/compare/v4.1.2...v4.1.3) (2026-08-29)


### Bug Fixes

* **a11y:** give focused fields a visible indicator ([#156](https://github.com/karimgarba/isaList/issues/156)) ([d278b1f](https://github.com/karimgarba/isaList/commit/d278b1fe5620a5004550fe980209531abd994561))

## [4.1.2](https://github.com/karimgarba/isaList/compare/v4.1.1...v4.1.2) (2026-08-28)


### Performance Improvements

* **auth:** load supabase-js on demand, not on every landing hit ([#151](https://github.com/karimgarba/isaList/issues/151)) ([e0669d5](https://github.com/karimgarba/isaList/commit/e0669d5f7b0d09cb8a2fea007faf1865a4db3002))

## [4.1.1](https://github.com/karimgarba/isaList/compare/v4.1.0...v4.1.1) (2026-08-28)


### Bug Fixes

* **for-you:** keep watch media out of the Read feed ([#148](https://github.com/karimgarba/isaList/issues/148)) ([f3c4f7d](https://github.com/karimgarba/isaList/commit/f3c4f7d5f8dffd37da9368ed291cad8864760312))

## [4.1.0](https://github.com/karimgarba/isaList/compare/v4.0.2...v4.1.0) (2026-08-28)


### Features

* **clubs:** Phase 3 — clubs, picks, spoiler-gated threads, leaderboard ([#127](https://github.com/karimgarba/isaList/issues/127)) ([a236c97](https://github.com/karimgarba/isaList/commit/a236c976a95c56bfb80014a7fb30b841d6bfcbdf))

## [4.0.2](https://github.com/karimgarba/isaList/compare/v4.0.1...v4.0.2) (2026-08-28)


### Bug Fixes

* **csp:** allow YouTube in frame-src so trailers actually play ([#145](https://github.com/karimgarba/isaList/issues/145)) ([b7b5794](https://github.com/karimgarba/isaList/commit/b7b5794c31af83a41d37f6bea0447a5e921493b5))

## [4.0.1](https://github.com/karimgarba/isaList/compare/v4.0.0...v4.0.1) (2026-08-26)


### Bug Fixes

* **manga,nav:** ungate the catalog job, finish the reading verbs, declutter filters ([#143](https://github.com/karimgarba/isaList/issues/143)) ([b394e3e](https://github.com/karimgarba/isaList/commit/b394e3edb48db4bbc536d30f88ed94c7d74c73e5))

## [4.0.0](https://github.com/karimgarba/isaList/compare/v3.2.0...v4.0.0) (2026-08-26)


### Features

* isalist 4.0 — manga as a second medium ([d7ea623](https://github.com/karimgarba/isaList/commit/d7ea623d5de3eedc8d27e599d86a7d61f75afe76))

## [3.2.0](https://github.com/karimgarba/isaList/compare/v3.1.1...v3.2.0) (2026-08-26)


### Features

* **stats,nav:** manga stats and a decluttered sidebar ([#138](https://github.com/karimgarba/isaList/issues/138)) ([a0cb5ca](https://github.com/karimgarba/isaList/commit/a0cb5ca348791824ce77a3a925ab5500daed67d3))

## [3.1.1](https://github.com/karimgarba/isaList/compare/v3.1.0...v3.1.1) (2026-08-26)


### Bug Fixes

* **manga:** reading verbs everywhere, plus per-medium hub pages ([#136](https://github.com/karimgarba/isaList/issues/136)) ([5c06822](https://github.com/karimgarba/isaList/commit/5c0682237fc34ed415396aa485cfbb70e9af0a4b))

## [3.1.0](https://github.com/karimgarba/isaList/compare/v3.0.1...v3.1.0) (2026-08-26)


### Features

* **manga:** add manga as a first-class media type ([#134](https://github.com/karimgarba/isaList/issues/134)) ([e41ad8e](https://github.com/karimgarba/isaList/commit/e41ad8ec89447190e0b3683e832c57e9aea04981))

## [3.0.1](https://github.com/karimgarba/isaList/compare/v3.0.0...v3.0.1) (2026-08-26)


### Bug Fixes

* **settings:** pin the save bar to the form so privacy changes persist ([#131](https://github.com/karimgarba/isaList/issues/131)) ([d100589](https://github.com/karimgarba/isaList/commit/d10058948309f2ec6899fb4602e2698d09c55024))

## [3.0.0](https://github.com/karimgarba/isaList/compare/v2.32.1...v3.0.0) (2026-08-08)


### ⚠ BREAKING CHANGES

* SearchResponse.total is renamed to count and now always means the number of results in this response. discover.has_more is false on a partial last page. TitleResponse keywords, studios, networks, production_companies, origin_country, seasons, cast and crew are non-nullable and default to []; score_distribution defaults to {}. POST /library/{id}/rewatch returns 409 with code entry_not_completed instead of 422. TitleResponse.title_type and .source are enums, with unchanged JSON.

### Features

* **blend:** tell the viewer why a private blend is closed ([4d9a180](https://github.com/karimgarba/isaList/commit/4d9a18059a7038b2d5558fbb4e5f718730c5b9a9))
* **for-you:** explainable recommendations from existing signals ([2029806](https://github.com/karimgarba/isaList/commit/2029806921e1ecd52c69d0c75eced03096b156a0))
* **home:** preview trailers on hover, reluctantly ([20bc50f](https://github.com/karimgarba/isaList/commit/20bc50f5605f478249d6ea1d30989cf194ca5b88))
* **import:** review what an import is about to add before it adds it ([c1afbb3](https://github.com/karimgarba/isaList/commit/c1afbb39a586d4c2444ec92e0e78b24e1065629b))
* isalist v3 — watch layer, semantic engine, clubs ([f74d66b](https://github.com/karimgarba/isaList/commit/f74d66b4d3a0e15e57a18aeb00fb4acf7fa4b0d1))
* **library:** filter to titles on your own services ([2ce28ed](https://github.com/karimgarba/isaList/commit/2ce28ed208ffa38702caf7f603759f7efd479bc6))
* **meta:** serve a shareable OG card for public profiles ([5b0eb9f](https://github.com/karimgarba/isaList/commit/5b0eb9f8663c7443257586b56a7f3df8fd4bb637))
* **onboarding:** cold-start rating pass for new accounts ([6080e38](https://github.com/karimgarba/isaList/commit/6080e389c93978a34398ee878dfd792b5efac5f1))
* **push:** web push for airing episodes and premieres ([b9e9c5c](https://github.com/karimgarba/isaList/commit/b9e9c5cf2edce1c1c8b4af022dacacd684956834))
* **ratings:** rate by axis and show axis breakdowns across stats surfaces ([e47a770](https://github.com/karimgarba/isaList/commit/e47a770aa697c39fc880726fda43ba9937bea6bf))
* **reel:** full-screen trailer reel over For-You ([8e0e8ec](https://github.com/karimgarba/isaList/commit/8e0e8ecc0ad866be70fe105c1b71dddf529fd3ae))
* **safety:** require an 18+ confirmation before enabling adult content ([05a4591](https://github.com/karimgarba/isaList/commit/05a459129e62a8459d2e62b44d1c7ac738761c64))
* **stats:** real watch streaks, computed in SQL and in the viewer's timezone ([ddf4b2d](https://github.com/karimgarba/isaList/commit/ddf4b2d9624d5cfa400afb5faf2a3f857536a256))
* **title:** render the trailer that has been ingested all along ([6822536](https://github.com/karimgarba/isaList/commit/682253627cabe77f24a1d7098ac44d7b5bc09f4f))
* **title:** show how long a series has left to run ([7ce8a35](https://github.com/karimgarba/isaList/commit/7ce8a35e8b532a597cc6f8b3299c58960241bacf))
* **tonight:** what you can actually start right now ([be5f6ef](https://github.com/karimgarba/isaList/commit/be5f6ef071f7a09c6c593fcd666f9a7c6fc505f8))
* v3 breaking-change sweep ([7e3e810](https://github.com/karimgarba/isaList/commit/7e3e81037a1bd7841639699c404ca448d6d1d5f0))
* **watch:** render where-to-watch on TitleDetail ([268b514](https://github.com/karimgarba/isaList/commit/268b514dd640fdcfd7b6825e806077279ff4580a))


### Bug Fixes

* **library:** make Rewatch actually start a rewatch ([d62ad7b](https://github.com/karimgarba/isaList/commit/d62ad7b1c180cdb0e3277f96543a6bf9c65122ba))

## [2.32.1](https://github.com/karimgarba/isaList/compare/v2.32.0...v2.32.1) (2026-07-25)


### Bug Fixes

* **lists:** remove the delete control from list grid cards ([c2bd9fe](https://github.com/karimgarba/isaList/commit/c2bd9fe260b664fa27470d6d1045bf1a17d2f48f))
* **lists:** remove the delete control from list grid cards ([7cd005f](https://github.com/karimgarba/isaList/commit/7cd005f0a4918d3928bd162c6f2b9fb8f59785a1))

## [2.32.0](https://github.com/karimgarba/isaList/compare/v2.31.2...v2.32.0) (2026-07-25)


### Features

* **filters:** add list and browse filters, rehaul lists and browse UI ([14eb440](https://github.com/karimgarba/isaList/commit/14eb440efc77c1a1582df00f08b54ce9341cad99))
* **filters:** add list and browse filters, rehaul lists and browse UI ([243b519](https://github.com/karimgarba/isaList/commit/243b51994ee619b7fd1c633198c375c35f350089))

## [2.31.2](https://github.com/karimgarba/isaList/compare/v2.31.1...v2.31.2) (2026-07-25)


### Bug Fixes

* **cards:** give poster titles a fixed two-line box ([535eead](https://github.com/karimgarba/isaList/commit/535eead8f47cb1eaa3c015feaa1bf5f65993c423))
* **cards:** uniform poster card heights regardless of title length ([1a0bbf1](https://github.com/karimgarba/isaList/commit/1a0bbf167fe785f5115dc549c591fc3ae12bbcc9))

## [2.31.1](https://github.com/karimgarba/isaList/compare/v2.31.0...v2.31.1) (2026-07-25)


### Bug Fixes

* **assets:** stop pinning 404s in cache for a year ([719237b](https://github.com/karimgarba/isaList/commit/719237b8823f719dbd8f91172f034f24688ba09b))
* **assets:** stop pinning 404s in cache for a year ([075da74](https://github.com/karimgarba/isaList/commit/075da74628781f4dd3a18d572d04635cf10a2769))

## [2.31.0](https://github.com/karimgarba/isaList/compare/v2.30.1...v2.31.0) (2026-07-25)


### Features

* **feed:** show every event individually instead of grouping ([f48c86a](https://github.com/karimgarba/isaList/commit/f48c86a0f001e6aed1e707265859bd5096d2197a))
* **feed:** show every event individually instead of grouping ([1b01dd0](https://github.com/karimgarba/isaList/commit/1b01dd0a35bd196d62abcc285bf3f03b8eebedd2))

## [2.30.1](https://github.com/karimgarba/isaList/compare/v2.30.0...v2.30.1) (2026-07-25)


### Bug Fixes

* **edge:** correct Cloudflare cache keying, proxy trust and MCP throttle ([8e15683](https://github.com/karimgarba/isaList/commit/8e156837e8fdca29badf22cb9cfb9294d1aade1d))

## [2.30.0](https://github.com/karimgarba/isaList/compare/v2.29.1...v2.30.0) (2026-07-25)


### Features

* **landing:** rebuild the landing page around restraint and cover art ([2af877b](https://github.com/karimgarba/isaList/commit/2af877b7c8ec2bf67a565455a962bb44e900ff43))
* **landing:** rebuild the landing page around restraint and cover art ([54fad4d](https://github.com/karimgarba/isaList/commit/54fad4d74f32f8562f0c67ded86d043511e9057c))
* **ui:** replace decorative emoji with drawn icons ([c823fe4](https://github.com/karimgarba/isaList/commit/c823fe455af61edf69e5c65d7378a2105b3b7443))


### Bug Fixes

* **landing:** tighten the vertical rhythm ([6b7b46f](https://github.com/karimgarba/isaList/commit/6b7b46fa789b126eb87f5f9ab0da332470c5b16e))

## [2.29.1](https://github.com/karimgarba/isaList/compare/v2.29.0...v2.29.1) (2026-07-25)


### Bug Fixes

* **landing:** apply the accent-text tokens to the landing page ([bd0c2a9](https://github.com/karimgarba/isaList/commit/bd0c2a9390e2d3388cc7a0a8d7f342c6c46525b9))
* **landing:** apply the accent-text tokens to the landing page ([cfb4597](https://github.com/karimgarba/isaList/commit/cfb4597ce30fe3ebc7650dac35309a2c1d12cf60))

## [2.29.0](https://github.com/karimgarba/isaList/compare/v2.28.3...v2.29.0) (2026-07-25)


### Features

* **home:** restructure the home page into two bands ([77b4292](https://github.com/karimgarba/isaList/commit/77b42921f7e03ba00c05acb8767edc896572827d))
* **home:** restyle the home page and fix light-mode contrast ([b72ae1e](https://github.com/karimgarba/isaList/commit/b72ae1e76a978957cf046dcd9ec621746f242124))


### Bug Fixes

* **theme:** add readable accent-text tokens and fix light-mode contrast ([15d89e1](https://github.com/karimgarba/isaList/commit/15d89e182bb8a69289a6099024478309d0b84e45))

## [2.28.3](https://github.com/karimgarba/isaList/compare/v2.28.2...v2.28.3) (2026-07-25)


### Bug Fixes

* **collections:** make rails scrollable and add a back button ([59ef221](https://github.com/karimgarba/isaList/commit/59ef22183fef96226986a1e8c7351bd85b76efa5))
* **collections:** make rails scrollable and add a back button ([d148449](https://github.com/karimgarba/isaList/commit/d1484491ea77a74022514bf622ff1ce9c2becda5))

## [2.28.2](https://github.com/karimgarba/isaList/compare/v2.28.1...v2.28.2) (2026-07-24)


### Bug Fixes

* **auth:** keep the session on every sign-in path ([6d37743](https://github.com/karimgarba/isaList/commit/6d37743ddcdcb9597ceeec4d8ca1d1c11eac008d))
* **auth:** keep the session on every sign-in path ([0d5eee0](https://github.com/karimgarba/isaList/commit/0d5eee08fbfc8b540b0dc6f3b5253ad195265a52))

## [2.28.1](https://github.com/karimgarba/isaList/compare/v2.28.0...v2.28.1) (2026-07-24)


### Bug Fixes

* **titles:** make "Add to list" actually add the title ([7582bb7](https://github.com/karimgarba/isaList/commit/7582bb73b7fbc391ce4a53de9e92d9c3325278ff))
* **titles:** make "Add to list" on title pages actually add the title ([a59ff7d](https://github.com/karimgarba/isaList/commit/a59ff7dd41c5769950b847956734e1c5e81ef0d3))

## [2.28.0](https://github.com/karimgarba/isaList/compare/v2.27.0...v2.28.0) (2026-07-24)


### Features

* **lists:** add a watched-together tick with stats ([fb06ebc](https://github.com/karimgarba/isaList/commit/fb06ebc09eb5a86737f9793fc8095af59bd96fc2))
* **lists:** allow owners to delete lists ([4e82218](https://github.com/karimgarba/isaList/commit/4e82218e6e72263f3c0ccb8cf86777aa81c6a73c))
* **lists:** delete lists, watched-together tick, and reaction scores site-wide ([20b2444](https://github.com/karimgarba/isaList/commit/20b2444546f9232efdceb1cea652c8c44a178ce4))
* **lists:** rehaul the list detail page ([5a678fd](https://github.com/karimgarba/isaList/commit/5a678fd9667700f91039ed38c6d23cc1da01467f))


### Bug Fixes

* **ui:** show the reaction icon instead of a raw score number ([ca94641](https://github.com/karimgarba/isaList/commit/ca946416e70b1a941dc40021b8e06bc2e657a3bf))

## [2.27.0](https://github.com/karimgarba/isaList/compare/v2.26.0...v2.27.0) (2026-07-24)


### Features

* **lists:** per-participant status, ratings & progress on collab lists ([3abdf2d](https://github.com/karimgarba/isaList/commit/3abdf2d6969e2f88bebd75140d8f00ec7008eb0b))
* **lists:** show per-participant status, rating, and progress on collab lists ([440f37b](https://github.com/karimgarba/isaList/commit/440f37b2a4616d357da1571e1b9ff2ab29d89f1f))

## [2.26.0](https://github.com/karimgarba/isaList/compare/v2.25.1...v2.26.0) (2026-07-15)


### Features

* **for-you:** freshness overhaul — impression fatigue, rotation, new taste signals, CTR metrics ([b076b36](https://github.com/karimgarba/isaList/commit/b076b3613f12ef16a23772921f74fec39c611815))
* **for-you:** report card clicks on recommendation surfaces as engagement ([8c5cb71](https://github.com/karimgarba/isaList/commit/8c5cb714b4a734be681fcafdb80806a0b5ca77b7))

## [2.25.1](https://github.com/karimgarba/isaList/compare/v2.25.0...v2.25.1) (2026-07-14)


### Bug Fixes

* **api:** bound axios requests with timeouts ([87dbb74](https://github.com/karimgarba/isaList/commit/87dbb74eaa8a7fc22f416b50dac25a7aec1189ec))
* **auth:** clear + purge persisted query cache on sign-out ([56513f4](https://github.com/karimgarba/isaList/commit/56513f49ecc115868a53f24119887efb54f66f12))
* **auth:** honor the remember-me flag via storage backend ([18d20de](https://github.com/karimgarba/isaList/commit/18d20de36aba73e1c60da57223f9c9c78c80a8bf))
* **auth:** reject backslash-prefixed redirect paths ([eae8dfa](https://github.com/karimgarba/isaList/commit/eae8dfaac7660adbb2afc57d80a87669e4c5909f))

## [2.25.0](https://github.com/karimgarba/isaList/compare/v2.24.0...v2.25.0) (2026-07-13)


### Features

* **titles:** title detail QOL overhaul ([7b6dfe8](https://github.com/karimgarba/isaList/commit/7b6dfe8429c88fb9875b6f68138084c91c1dfc6a))
* **titles:** title detail QOL overhaul ([64a884a](https://github.com/karimgarba/isaList/commit/64a884ae96d2dd563a2db2ab93781240bf9eade6))

## [2.24.0](https://github.com/karimgarba/isaList/compare/v2.23.2...v2.24.0) (2026-07-12)


### Features

* **collections:** browse api client, keys, types ([475125e](https://github.com/karimgarba/isaList/commit/475125e051e8a3491c8b763b25e5694258948600))
* **collections:** CollectionCard matching TitleCard frame ([10bec65](https://github.com/karimgarba/isaList/commit/10bec65109388578216a37aab0d2d246d52c2429))
* **collections:** redesign page with hero, rails, browse grid ([8d152ac](https://github.com/karimgarba/isaList/commit/8d152ac34f676ce702028dbe32fb67d8b5ca8df5))
* **library:** grouped collections use CollectionCard for size parity ([7e9d1f4](https://github.com/karimgarba/isaList/commit/7e9d1f4ebd6da9260f415b69bf01c505df281e07))


### Bug Fixes

* **cards:** consistent TitleCard footer across score/vote states ([d197f46](https://github.com/karimgarba/isaList/commit/d197f4697e9ce0f1827af9bf073203f824d9e860))
* **collections:** phase-1 quality — release ordering, detail NSFW gate, counts ([a12f437](https://github.com/karimgarba/isaList/commit/a12f437bcf812194b5eb07bf20cf7fa7c0c87166))

## [2.23.2](https://github.com/karimgarba/isaList/compare/v2.23.1...v2.23.2) (2026-07-06)


### Bug Fixes

* **settings:** correct toggle-switch knob travel, extract reusable Toggle ([3ca5b7e](https://github.com/karimgarba/isaList/commit/3ca5b7e773118f31d3f59e10ff2801918534710a))

## [2.23.1](https://github.com/karimgarba/isaList/compare/v2.23.0...v2.23.1) (2026-07-06)


### Performance Improvements

* **images:** request thumbnail-sized cover art sitewide ([8eb01cd](https://github.com/karimgarba/isaList/commit/8eb01cd667ec51b79fcd504db685f95491fe5acc))

## [2.23.0](https://github.com/karimgarba/isaList/compare/v2.22.2...v2.23.0) (2026-07-06)


### Features

* **seo:** give every route a unique title, description and canonical ([6bf6a35](https://github.com/karimgarba/isaList/commit/6bf6a355e6579dce69364033ed1622d07760f1cf))

## [2.22.2](https://github.com/karimgarba/isaList/compare/v2.22.1...v2.22.2) (2026-07-06)


### Bug Fixes

* **landing:** give headline enough line-height to clear glyph overlap ([4865d22](https://github.com/karimgarba/isaList/commit/4865d222c76dec9754dc6c5ab019061a8cdfc131))

## [2.22.1](https://github.com/karimgarba/isaList/compare/v2.22.0...v2.22.1) (2026-07-06)


### Bug Fixes

* **landing:** stop headline lines overlapping ([49f8866](https://github.com/karimgarba/isaList/commit/49f886694c29dadd37e4351fb450411c4d87b179))

## [2.22.0](https://github.com/karimgarba/isaList/compare/v2.21.0...v2.22.0) (2026-07-06)


### Features

* **lists,stats:** fix list adds + replace mean-score with reaction blend ([fc0d791](https://github.com/karimgarba/isaList/commit/fc0d791b378f5feea11ff28e9e97ac83ebe881e6))

## [2.21.0](https://github.com/karimgarba/isaList/compare/v2.20.0...v2.21.0) (2026-07-06)


### Features

* **ads:** conditional AdSense loader gated on VITE_ADSENSE_CLIENT_ID ([3cdef7b](https://github.com/karimgarba/isaList/commit/3cdef7b7471afcaa3cae959d84683f6865bf01e9))
* **ads:** env-var slot ids + consent-gated AdSense loader + ads.txt ([eb24357](https://github.com/karimgarba/isaList/commit/eb24357dfe63e5fbe590b5d8cad6e6f2043da364))
* **library:** per-collection grouping kebab + migration banner ([6e63b3f](https://github.com/karimgarba/isaList/commit/6e63b3fdfc782808bbdbcbd01cd31805dcc7391d))
* **library:** server-persisted grouping toggle + reset-all banner ([9410880](https://github.com/karimgarba/isaList/commit/9410880944ec705e2d52b9767593b621daf27c9d))
* **library:** typed FE client for group overrides ([8e6d322](https://github.com/karimgarba/isaList/commit/8e6d32281dcef1ec69a533036c6a8f1eeded0f41))
* **lists:** live-poll shared list entries while co-editing ([83cf8ca](https://github.com/karimgarba/isaList/commit/83cf8cab3febe45709947284b88c89835ec5a32e))


### Bug Fixes

* **api:** prefix collections + libraryGrouped routes with /api/v1 ([0dae8af](https://github.com/karimgarba/isaList/commit/0dae8afb185a30a803cb4b3e2e6159336522b916))
* **library:** match group card height to title cards via portrait aspect ([e342766](https://github.com/karimgarba/isaList/commit/e342766bee9f45d70b9738d211d2a28e098c6979))

## [2.20.0](https://github.com/karimgarba/isaList/compare/v2.19.0...v2.20.0) (2026-06-25)


### Features

* **collections:** CollectionDetailPage with bulk add ([6e588b1](https://github.com/karimgarba/isaList/commit/6e588b1b14ee370c289bc037a96a16bb99cf13c8))
* **collections:** CollectionsPage with rails ([d2dd0e5](https://github.com/karimgarba/isaList/commit/d2dd0e5ae319fd29252ed621513613fdbf1ce047))
* **collections:** frontend types + API client ([0ab4b3a](https://github.com/karimgarba/isaList/commit/0ab4b3a57149b67ed2fd0f1ed6d2180ae13838f6))
* **collections:** wire routes and sidebar entry ([4265dfc](https://github.com/karimgarba/isaList/commit/4265dfc4bc85fc6cb93dfe1addb6fd7f5de86f31))
* **library:** default to grid view + paginate (60/page) ([0434173](https://github.com/karimgarba/isaList/commit/043417331cb3836afb2ef9cf536f4e096744e09d))
* **library:** frontend types + client for grouped page ([3275822](https://github.com/karimgarba/isaList/commit/3275822591fb7916513e12237bc2a64fd3905610))
* **library:** render grouped collections in LibraryPage ([d9492df](https://github.com/karimgarba/isaList/commit/d9492dfe6fd33920b96ac54c510b0517a3f5ac92))
* **lists:** mosaic header on ListDetailPage ([6462c94](https://github.com/karimgarba/isaList/commit/6462c945b4db659d504833232bdf4a3d3d04eade))
* **lists:** rehaul ListsPage with AggregatedCard ([5748221](https://github.com/karimgarba/isaList/commit/5748221d0fdc3ef1cd255bc58b5c35b17bcdcce7))
* **ui:** higher-contrast type pill + status badge, card hover lift, real empty-cover state ([90e0e5b](https://github.com/karimgarba/isaList/commit/90e0e5b11256c19318b60941328241fb4dcc11bc))
* **ui:** shared AggregatedCard component ([4f51725](https://github.com/karimgarba/isaList/commit/4f51725f74fdd1d60cade3fce8585b0dcffef85c))


### Bug Fixes

* **collections:** presentational AggregatedCard + docstring + test cleanup ([c885ec3](https://github.com/karimgarba/isaList/commit/c885ec3a800faf9c828b45dae6ceed539333e43e))

## [2.19.0](https://github.com/karimgarba/isaList/compare/v2.18.0...v2.19.0) (2026-06-22)


### Features

* **profile:** add list / grid view toggle on library tab ([f1d92c6](https://github.com/karimgarba/isaList/commit/f1d92c6577be78a044fed7a893ce5c500c41d4e3))
* **ux:** scroll-to-top FAB + tap-top-bar-to-scroll-up ([9bf68fa](https://github.com/karimgarba/isaList/commit/9bf68fa3b30d052520ce4264d17b4c5eda262cdc))


### Bug Fixes

* **blend:** swap unique_for_you / unique_for_them section bindings ([856903e](https://github.com/karimgarba/isaList/commit/856903eec28740e548d4598051e88a5e3b7cbe65))

## [2.18.0](https://github.com/karimgarba/isaList/compare/v2.17.0...v2.18.0) (2026-06-22)


### Features

* **blend:** refuse to show a compatibility number when there isn't one ([eac8e82](https://github.com/karimgarba/isaList/commit/eac8e82c916f50984183d98b62cfe3740de698c0))

## [2.17.0](https://github.com/karimgarba/isaList/compare/v2.16.1...v2.17.0) (2026-06-22)


### Features

* **privacy:** per-section visibility for library / stats / activity ([ee07b7e](https://github.com/karimgarba/isaList/commit/ee07b7ec7018f65be088cc014b317cb9563087ef))
* **profile:** rebuild library tab with status sub-tabs + virtualization ([9904eb4](https://github.com/karimgarba/isaList/commit/9904eb4a659150ec76fdcbfffd715a1593f556eb))


### Bug Fixes

* **score:** unify catalog score display, fix 0-10 vs 0-100 scale bugs ([e348757](https://github.com/karimgarba/isaList/commit/e3487578131b8c918ea5c8d0543469bf12ecfc37))

## [2.16.1](https://github.com/karimgarba/isaList/compare/v2.16.0...v2.16.1) (2026-06-22)


### Bug Fixes

* **agent-discovery:** use Vercel Edge Middleware for markdown negotia… ([68047fb](https://github.com/karimgarba/isaList/commit/68047fbdc74d5740701d5d2379c0aeddb012d043))
* **agent-discovery:** use Vercel Edge Middleware for markdown negotiation ([ecf32d4](https://github.com/karimgarba/isaList/commit/ecf32d4390600d1e05b30a64931db3dd6cefacff))

## [2.16.0](https://github.com/karimgarba/isaList/compare/v2.15.0...v2.16.0) (2026-06-22)


### Features

* **agent-discovery:** Agent Skills index, WebMCP tools, markdown reg… ([9830783](https://github.com/karimgarba/isaList/commit/98307834277740d3f1f8cc148fcf70e9614273f8))
* **agent-discovery:** Agent Skills index, WebMCP tools, markdown regex fix ([a2051d0](https://github.com/karimgarba/isaList/commit/a2051d01cc69ed64ac2940fbc0e7c33ebb7f5126))

## [2.15.0](https://github.com/karimgarba/isaList/compare/v2.14.0...v2.15.0) (2026-06-22)


### Features

* **agent-discovery:** MCP server + well-known docs for agent readiness ([2e9f52e](https://github.com/karimgarba/isaList/commit/2e9f52e61e6f6cf09f059c3dfef57d710c6a4136))
* **agent-discovery:** MCP server + well-known docs for agent readiness ([e7f6172](https://github.com/karimgarba/isaList/commit/e7f61724e1e3bdcf216e1b1c286425a6dd5fe972))

## [2.14.0](https://github.com/karimgarba/isaList/compare/v2.13.1...v2.14.0) (2026-06-21)


### Features

* **frontend:** offline/reconnecting banner ([53f81b7](https://github.com/karimgarba/isaList/commit/53f81b7b531351a547c345302d4fc64412880179))


### Performance Improvements

* **frontend:** cancel abandoned heavy reads via AbortSignal ([fd3fb26](https://github.com/karimgarba/isaList/commit/fd3fb26647154b3013394599bf194c4b79fad4fb))
* **frontend:** lazy-split overlays, retry-owner, prod console strip ([6b97a87](https://github.com/karimgarba/isaList/commit/6b97a879e5d00488642e5fba0260a120fe3fcd0a))
* **frontend:** P0 idle/resource fixes ([4578566](https://github.com/karimgarba/isaList/commit/457856625f2052e02d0d39774e60d0ec1df096f7))
* **frontend:** P1 resource fixes ([0969227](https://github.com/karimgarba/isaList/commit/0969227841bda1317eea925fa140f9e9f22d4a43))
* **frontend:** P2 polish ([1c68648](https://github.com/karimgarba/isaList/commit/1c68648a70e1c883d8a68c081f7b72d23a22ffcd))
* **frontend:** virtualize the ForYou infinite feed ([163a03c](https://github.com/karimgarba/isaList/commit/163a03c15d7e8ea06375ea74322b0bda1ff0a754))
* **frontend:** virtualize the profile library list ([854432d](https://github.com/karimgarba/isaList/commit/854432dcc65225d9838ff92abb40b9e0d2aac3df))
* **frontend:** virtualize the Search infinite grids ([d17fd22](https://github.com/karimgarba/isaList/commit/d17fd2289b82d0bdf0f1c427fcf284d45f539c78))

## [2.13.1](https://github.com/karimgarba/isaList/compare/v2.13.0...v2.13.1) (2026-06-19)


### Bug Fixes

* **ui:** batch A — hide dev hints in prod, keep error toasts longer, surface list mutation failures ([97c9565](https://github.com/karimgarba/isaList/commit/97c9565e4b015a6642fa0be2ae07737c9ea7f4c0))

## [2.13.0](https://github.com/karimgarba/isaList/compare/v2.12.0...v2.13.0) (2026-06-19)


### Features

* **frontend:** redesign public landing experience ([3dfc35c](https://github.com/karimgarba/isaList/commit/3dfc35cb6482e24bd9eb1b580114544ba052d7f7))
* **tags:** add structured cross-media tag discovery ([5fedb9e](https://github.com/karimgarba/isaList/commit/5fedb9e89ef330f32bac25cfe995ffab329c840b))
* **upcoming:** mix movie tv and anime releases ([7d1d104](https://github.com/karimgarba/isaList/commit/7d1d104b4b1234baa21fc89991b7a49c9b97c91a))


### Bug Fixes

* **frontend:** align cookie consent controls ([43ba288](https://github.com/karimgarba/isaList/commit/43ba288556b4bd82daf7de17be3086f59974abbd))

## [2.12.0](https://github.com/karimgarba/isaList/compare/v2.11.0...v2.12.0) (2026-06-12)


### Features

* **seo:** bot meta endpoint, dynamic sitemap, og card, slugged title URLs ([4fc5cf6](https://github.com/karimgarba/isaList/commit/4fc5cf6e8e2e0eaf8aca2d53a6b5e434653a4fd8))

## [2.11.0](https://github.com/karimgarba/isaList/compare/v2.10.0...v2.11.0) (2026-06-12)


### Features

* **browse,feed:** browse landing with curated rails, decluttered feed ([5d879d4](https://github.com/karimgarba/isaList/commit/5d879d45a51e44255726cf424fc34337becb2205))
* **schedule,notifications:** seasonal anime premieres and airing alerts ([7046075](https://github.com/karimgarba/isaList/commit/704607575f8d87cc83e6735660cd3d3d9422c015))


### Bug Fixes

* **ui:** use theme ink color for rating/review text unreadable in light mode ([ac27c44](https://github.com/karimgarba/isaList/commit/ac27c44766b032f9b855c332e28212442c6628b5))

## [2.10.0](https://github.com/karimgarba/isaList/compare/v2.9.0...v2.10.0) (2026-06-11)


### Features

* **library,title:** next-episode badges from shared upcoming cache ([c18ad3b](https://github.com/karimgarba/isaList/commit/c18ad3b1e86550abb524b7b314a3d5750361d2f8))

## [2.9.0](https://github.com/karimgarba/isaList/compare/v2.8.0...v2.9.0) (2026-06-11)


### Features

* **schedule:** Upcoming-for-you releases + full Schedule page ([bc85be7](https://github.com/karimgarba/isaList/commit/bc85be776eb8cf90aae03c281e20572560253e0e))


### Performance Improvements

* **api,home:** aggregate the four home discover rails into one request ([7fa90e3](https://github.com/karimgarba/isaList/commit/7fa90e31c5297435f27b3ca8b99ec6697224dd4a))
* **api,ui:** bulk library endpoint, badges aggregate, TitleCard memo ([f89b6ad](https://github.com/karimgarba/isaList/commit/f89b6adb2d2e6e9c516e996cf3417cab8e45481b))

## [2.8.0](https://github.com/karimgarba/isaList/compare/v2.7.0...v2.8.0) (2026-06-10)


### Features

* **ui:** add radius/shadow/semantic-color design tokens (revamp foundation) ([d78f242](https://github.com/karimgarba/isaList/commit/d78f2424db2f3ec09e40933b4e11c74e6bc76fbe))

## [2.7.0](https://github.com/karimgarba/isaList/compare/v2.6.0...v2.7.0) (2026-06-10)


### Features

* **upcoming:** show season/episode number + batch AniList airing loo… ([96d9482](https://github.com/karimgarba/isaList/commit/96d9482101f7c5c8cc7b3998bf752cadaefef1a5))
* **upcoming:** show season/episode number + batch AniList airing lookups ([39a4f7e](https://github.com/karimgarba/isaList/commit/39a4f7e18cc9c48653d1af03e63e165b61c0dc57))

## [2.6.0](https://github.com/karimgarba/isaList/compare/v2.5.0...v2.6.0) (2026-06-10)


### Features

* **ui:** add shared Button/Input primitives (phase 4 foundation) ([27f8297](https://github.com/karimgarba/isaList/commit/27f82970bad66872c688a6dde88a9cc884f23b8d))
* **ui:** add shared Button/Input primitives (phase 4 foundation) ([7bbe495](https://github.com/karimgarba/isaList/commit/7bbe49574761b17c13ebf61b2cf40a8e69186786))

## [2.5.0](https://github.com/karimgarba/isaList/compare/v2.4.0...v2.5.0) (2026-06-09)


### Features

* **settings:** link to the Not Interested management page ([d662b7c](https://github.com/karimgarba/isaList/commit/d662b7c96ca97c14a7693b96a7e28e75c18b4abb))


### Bug Fixes

* **ui:** a11y + broken-image fixes from audit (phase 1) ([c2ca082](https://github.com/karimgarba/isaList/commit/c2ca082fa401c9c5bda1b9e507cafcf7f7b0016e))
* **ui:** migrate hardcoded gray/hex colors to theme tokens for light mode ([bacf6af](https://github.com/karimgarba/isaList/commit/bacf6afef9f56f7309febaf57bf168d7b354f97e))
* **ui:** tokenize shared Skeleton + Settings blocked-users for light mode ([d5bc528](https://github.com/karimgarba/isaList/commit/d5bc528f61c3101b7ac72f3ae15c274af38eccc5))
* **ui:** wire error states + mutation feedback from audit (phase 2) ([dfd4eeb](https://github.com/karimgarba/isaList/commit/dfd4eeb5e1e2b384185e65d64ed07bf4aa9ae5ec))

## [2.4.0](https://github.com/karimgarba/isaList/compare/v2.3.1...v2.4.0) (2026-06-09)


### Features

* **feed:** revamp activity feed into a colour-coded timeline ([1655d3a](https://github.com/karimgarba/isaList/commit/1655d3a170d32faecbc0e816f958c02e607fea04))
* **studio,episodes:** studio page polish + episode rating widget UX ([87ef2e9](https://github.com/karimgarba/isaList/commit/87ef2e9e7e8e29d4e9dedf3adb6ce99cd99a9cdd))
* **upcoming,tags:** Upcoming releases page + Tags browse, with sidebar nav ([63d4930](https://github.com/karimgarba/isaList/commit/63d4930bd5b424f08be83e0a1911974e35f959ee))
* **upcoming:** detect next-episode/season air dates for watched shows ([7cc174b](https://github.com/karimgarba/isaList/commit/7cc174b17f364cf3121c3e7a4c47c758c4449af3))


### Bug Fixes

* **card:** align status pill with type badge, declutter card overlays ([3606781](https://github.com/karimgarba/isaList/commit/3606781fa30b8a07993794de3637832eeaa73606))

## [2.3.1](https://github.com/karimgarba/isaList/compare/v2.3.0...v2.3.1) (2026-06-09)


### Performance Improvements

* **for-you:** coalesce cold builds + tame feed prefetch; search QoL ([5a98693](https://github.com/karimgarba/isaList/commit/5a98693234d9a814da1da3912d5a0f97d7c38554))
* **for-you:** coalesce cold builds + tame feed prefetch; search QoL ([e44a470](https://github.com/karimgarba/isaList/commit/e44a4703bc68fd82cc24d3e5cb8fa883ae9d111e))

## [2.3.0](https://github.com/karimgarba/isaList/compare/v2.2.2...v2.3.0) (2026-06-09)


### Features

* **studio,search:** studio catalog pages, FYP tag accuracy, search c… ([044f5ba](https://github.com/karimgarba/isaList/commit/044f5bac585ea6372479bef27027375504d4d8b0))
* **studio,search:** studio catalog pages, FYP tag accuracy, search cleanup ([e31fd15](https://github.com/karimgarba/isaList/commit/e31fd1587153559df9c179047e4280a6a00cce38))

## [2.2.2](https://github.com/karimgarba/isaList/compare/v2.2.1...v2.2.2) (2026-06-09)


### Bug Fixes

* **csp:** point connect-src at api.myisalist.com instead of Render ([ee65d92](https://github.com/karimgarba/isaList/commit/ee65d9240b2bd1464f967de2d653ca86bc2167a7))

## [2.2.1](https://github.com/karimgarba/isaList/compare/v2.2.0...v2.2.1) (2026-06-06)


### Performance Improvements

* **home:** drop wasted For-You prefetch that never matched its consumer ([1057bb8](https://github.com/karimgarba/isaList/commit/1057bb836ded49de5aefd53dd28232e9c8ac951e))

## [2.2.0](https://github.com/karimgarba/isaList/compare/v2.1.0...v2.2.0) (2026-06-06)


### Features

* **for-you:** warm cache on profile load; widen client fallback retry ([cdeedaf](https://github.com/karimgarba/isaList/commit/cdeedaf9a21e98f4bab275f2f850668a107282da))

## [2.1.0](https://github.com/karimgarba/isaList/compare/v2.0.4...v2.1.0) (2026-06-05)


### Features

* **notifications:** tighten live poll cadence for near-realtime feel ([62d0cb9](https://github.com/karimgarba/isaList/commit/62d0cb9e3bee5936d658f7e8dbeb498dc3969487))


### Bug Fixes

* **security,perf:** close authz gaps, fix rate limiting, add RLS+indexes ([e14bcc7](https://github.com/karimgarba/isaList/commit/e14bcc7e958f3762a964e7dbf90955ab6801921a))

## [2.0.4](https://github.com/karimgarba/isaList/compare/v2.0.3...v2.0.4) (2026-06-05)


### Bug Fixes

* **a11y:** label icon-only close buttons and autofocus search input ([5b3f619](https://github.com/karimgarba/isaList/commit/5b3f6193023fd1d9399109354972127b6264f66f))
* **notifications:** refresh unread badge after marking one as read ([bc2d4ef](https://github.com/karimgarba/isaList/commit/bc2d4efba6b4cf9817cf3429d8889b975bc50abf))
* **reviews:** invalidate likers query after like/unlike ([a823a3a](https://github.com/karimgarba/isaList/commit/a823a3a4d08d097cd229ae526936756925fa76f2))

## [2.0.3](https://github.com/karimgarba/isaList/compare/v2.0.2...v2.0.3) (2026-06-05)


### Performance Improvements

* **frontend:** persist react-query cache to localStorage for instant rehydrate ([9fde66c](https://github.com/karimgarba/isaList/commit/9fde66cc9dafcc4b2a453562eda1a342c07ea9de))

## [2.0.2](https://github.com/karimgarba/isaList/compare/v2.0.1...v2.0.2) (2026-06-05)


### Performance Improvements

* **pwa:** fall back to api-cache after 5s of network silence ([25cf2ce](https://github.com/karimgarba/isaList/commit/25cf2cec6258da608393330bade58e9538ab5a44))

## [2.0.1](https://github.com/karimgarba/isaList/compare/v2.0.0...v2.0.1) (2026-06-04)


### Bug Fixes

* **discover:** stop for-you rebuild storm and cap UI paging at backend max ([4f6f0fd](https://github.com/karimgarba/isaList/commit/4f6f0fdfcda5ea9e1c79444b029d38b1d0f8b56c))
* **library-modal:** guard handlers against double-submit on rapid clicks ([fb6eee4](https://github.com/karimgarba/isaList/commit/fb6eee40cb6af9f7139e2f7b222fca878e5b40e7))
* **login:** show back arrow at all breakpoints ([9128599](https://github.com/karimgarba/isaList/commit/9128599f54227f298524c80bc0ac81cca16fa220))
