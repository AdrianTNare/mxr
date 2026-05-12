# Changelog

## [0.5.9](https://github.com/AdrianTNare/mxr/compare/v0.5.8...v0.5.9) (2026-05-12)


### Features

* [] add daemon web bridge ([ec4894a](https://github.com/AdrianTNare/mxr/commit/ec4894aeb258466c963244de02596d2d7b00841b))
* [] add debug action trace ([977b323](https://github.com/AdrianTNare/mxr/commit/977b323321307811cd8978b8ec11acbb2e40c75a))
* [] add desktop shell for mxr ([5b68d5e](https://github.com/AdrianTNare/mxr/commit/5b68d5e35eede463c1f0d37a167377af445a0634))
* [] add Gmail-style search operators ([6b765bf](https://github.com/AdrianTNare/mxr/commit/6b765bf9338bd9db6df6dbc11141480796ea6b10))
* [] expand bridge and tui parity ([47d24ac](https://github.com/AdrianTNare/mxr/commit/47d24ac5303d3a80b539aaf44a1873a21988a837))
* [] finish desktop workbench ([33c2eb1](https://github.com/AdrianTNare/mxr/commit/33c2eb16680068912f60bdddade047f6c8b309f9))
* [] harden mailbox html rendering ([cc3d60a](https://github.com/AdrianTNare/mxr/commit/cc3d60a3325ba66bafd8d0f202862e3cb6a491fe))
* [] harden semantic ingest lifecycle ([a1518a3](https://github.com/AdrianTNare/mxr/commit/a1518a36c73f3caefd25f5394e7e08aa839bc7ef))
* [] refresh desktop workbench shell ([29cd7a1](https://github.com/AdrianTNare/mxr/commit/29cd7a15ca3660192bc4391a79ec1747c1a5df55))
* [] stabilize daemon desktop protocol ([dd26be3](https://github.com/AdrianTNare/mxr/commit/dd26be302557e66a0d8514aa7e55ac4511b4118c))
* [] tighten desktop tui parity ([7e0f212](https://github.com/AdrianTNare/mxr/commit/7e0f212d5b5e40f405e9364c0f4251c945a34be7))
* adapt all providers to eager body fetch ([310c29a](https://github.com/AdrianTNare/mxr/commit/310c29a6bfe8a62f4834e34e48a01a50eee8fe40))
* add --dry-run to mxr send and mxr unsnooze ([d21b65b](https://github.com/AdrianTNare/mxr/commit/d21b65b858840b97cc7df0efcff32547246e2713))
* add compose picker, send confirmation, and instant body display ([1540a19](https://github.com/AdrianTNare/mxr/commit/1540a190f8fba8f5eeb5ccaf27c7685c9b410c77))
* add config edit/get/set CLI commands ([b9876e4](https://github.com/AdrianTNare/mxr/commit/b9876e4b5549c64813f63ac7f56b73c5be9dc24e))
* add config-inclusive reset mode ([8babff5](https://github.com/AdrianTNare/mxr/commit/8babff59fcf355abe45192c2725ae01b6e3223c0))
* add hybrid semantic search ([0d01d9f](https://github.com/AdrianTNare/mxr/commit/0d01d9f945909653eda694d392fa49d38106e6d8))
* add landing page with marketing copy and custom styling ([6502875](https://github.com/AdrianTNare/mxr/commit/650287586a6c0f0a673cd7bda42c19ced21c33a0))
* add safe local-state reset command ([9a862db](https://github.com/AdrianTNare/mxr/commit/9a862db535c95b2ad113710204e2b60e2537a739))
* add scrollable account test details modal in TUI ([6333fb0](https://github.com/AdrianTNare/mxr/commit/6333fb0b812e5a8a754197ee4142b887a049c12e))
* add threading algorithm, body prefetch, and backfill to sync ([7b226e8](https://github.com/AdrianTNare/mxr/commit/7b226e8bff93f08290a794a15f9b4034412af0e1))
* **analytics:** cut decoration, surface ratios and distribution shapes ([d47f761](https://github.com/AdrianTNare/mxr/commit/d47f7618f67cf118436e88e4aff1163de85dac98))
* **analytics:** dashboard redesign across all 6 tabs + stale-while-revalidate cache ([dde446f](https://github.com/AdrianTNare/mxr/commit/dde446f9b19cf480df989588198961af9e3782d6))
* **analytics:** perf, UX overhaul; release ships semantic-local ([e8081b2](https://github.com/AdrianTNare/mxr/commit/e8081b28adcb3712627af9f93daa8d89884f0ba8))
* **bridge:** slice 1 — feature-gated ToSchema on protocol ([74bf031](https://github.com/AdrianTNare/mxr/commit/74bf0315a1e5a4619634cdbe55c7bd98f9cba085))
* **bridge:** slice 2 — utoipa scaffold + openapi.json + Swagger UI ([aec9a3b](https://github.com/AdrianTNare/mxr/commit/aec9a3b84d24c1bb7fbb8e6d7dbb454654bd95f9))
* **bridge:** slice 3 — bucket all 47 routes under /api/v1/* + 308 shim ([a0a32a2](https://github.com/AdrianTNare/mxr/commit/a0a32a27fe10e6b80f33698ab847039eb708bf48))
* **bridge:** slice 4 — auth hardening, /health, host & CORS allowlists ([a1805f7](https://github.com/AdrianTNare/mxr/commit/a1805f76ca98f71691585a2a12e0da2c902884a6))
* **bridge:** slice 5 — daemon-hosted bridge as managed task ([e93f053](https://github.com/AdrianTNare/mxr/commit/e93f053c843562ab299a23676ec26ebe3d5395c8))
* **bridge:** slice 6 — close protocol coverage gap (~30 new routes) ([d25b65e](https://github.com/AdrianTNare/mxr/commit/d25b65edf7643066ad7db212d9c4d39161c4bf77))
* **bridge:** slice 7 — integration harness + OpenAPI conformance CI ([86ac37b](https://github.com/AdrianTNare/mxr/commit/86ac37ba9f96a78f5a8310e828c96f8983981f0d))
* **bridge:** slice 8 — desktop app forward-compat + codegen tooling ([5e44f35](https://github.com/AdrianTNare/mxr/commit/5e44f35806b52975816c94ee73be75c009f4a6fe))
* CLI surface — non-interactive accounts add and logs --format json ([b7effc4](https://github.com/AdrianTNare/mxr/commit/b7effc44c84d4b0042015c21d8201fb3cd618a30))
* **daemon:** IMAP IDLE wake-up framework + FakeProvider hook ([3c2a616](https://github.com/AdrianTNare/mxr/commit/3c2a61640713a230c61ef72e1138d5fee53019d6))
* eager body fetch in sync engine, apply delta label changes ([4610bf7](https://github.com/AdrianTNare/mxr/commit/4610bf779ddccf93d39d6eb0c8ad420ec7530e4f))
* email analytics — CLI commands ([0f48f63](https://github.com/AdrianTNare/mxr/commit/0f48f6349e6a89be45f2a0deb02a0220d2464a8b))
* email analytics — protocol + daemon plumbing ([972612a](https://github.com/AdrianTNare/mxr/commit/972612a95e44ce58d555ab6159299081d4a3d01c))
* email analytics — schema migrations + store APIs ([67a5194](https://github.com/AdrianTNare/mxr/commit/67a51944805e55b2385006b7b58f07e2634af90b))
* enhance search with AST parser, saved searches, and body indexing ([59f61b7](https://github.com/AdrianTNare/mxr/commit/59f61b796de5dae631e155d6cfd1da933631336b))
* enhance TUI with keybindings, command palette, and message view ([6b37fa4](https://github.com/AdrianTNare/mxr/commit/6b37fa4841d39d7cb2f5613a8c168938bc7f390a))
* expand core types and protocol for Phase 2 ([7130c74](https://github.com/AdrianTNare/mxr/commit/7130c74b18fdeffce2ac96870ae690ab5e55561d))
* expand store with full CRUD, label counts, and body caching ([810a027](https://github.com/AdrianTNare/mxr/commit/810a02716a191470478f7c7be7af5d8da6217fb6))
* gmail device flow for ssh and headless ([c7d2895](https://github.com/AdrianTNare/mxr/commit/c7d2895a437a0c75db82ed20cf31b7384d17f599))
* implement compose workflow with YAML frontmatter and $EDITOR ([f658bfe](https://github.com/AdrianTNare/mxr/commit/f658bfe2852dc9d1d84f758695cda93c9cf44026))
* implement config system with TOML resolution and defaults ([9021ef8](https://github.com/AdrianTNare/mxr/commit/9021ef86315d90a73f7a610d9fb6ddcd37b22b21))
* implement daemon with Unix socket server and background sync ([bbea6ed](https://github.com/AdrianTNare/mxr/commit/bbea6edc63ad684ed3e8b6eefc8466bbe3ed91d8))
* implement fake provider for testing ([24cb7db](https://github.com/AdrianTNare/mxr/commit/24cb7dbb27e20c49b3078b31e67a35895e3586a2))
* implement full CLI surface and expand daemon handler ([b2fdb20](https://github.com/AdrianTNare/mxr/commit/b2fdb20e2836e6d10a91bf83f9fb865b0e8f3d88))
* implement Gmail provider with OAuth2 and delta sync ([cebccbb](https://github.com/AdrianTNare/mxr/commit/cebccbbecef239306193e70d8f95354db905c76d))
* implement IMAP provider with session management and UID polling ([ac1ee8c](https://github.com/AdrianTNare/mxr/commit/ac1ee8c0cde463f772de6d5423506131ee9c0f7a))
* implement mxr-core types, provider traits, and error types ([75d18ae](https://github.com/AdrianTNare/mxr/commit/75d18aee4011b694e3d476d1a3415bc84c8bfe81))
* implement mxr-protocol with IPC codec and command types ([c042885](https://github.com/AdrianTNare/mxr/commit/c0428855b8826a88c9e2e0ec26f6073ad1a9fef6))
* implement mxr-search with Tantivy BM25 indexing ([480235e](https://github.com/AdrianTNare/mxr/commit/480235ec411660fd14361cb20829b714cf422a00))
* implement mxr-store with SQLite persistence ([f96f86c](https://github.com/AdrianTNare/mxr/commit/f96f86cb96623ff9862c2d21c1d869086ca7144d))
* implement reader mode with HTML-to-text pipeline ([1e5add1](https://github.com/AdrianTNare/mxr/commit/1e5add17aa72b9cc22b27c0e841850b4bb2cac8d))
* implement SMTP send provider via lettre ([0727d6c](https://github.com/AdrianTNare/mxr/commit/0727d6ca7da8a22d9a08e8cb4b0830e0c1eefaf3))
* implement sync engine orchestrating providers, store, and search ([4495ee8](https://github.com/AdrianTNare/mxr/commit/4495ee835096c574b6ccb1649ff4a804528628f9))
* implement TUI client with ratatui ([bc55db9](https://github.com/AdrianTNare/mxr/commit/bc55db9275d0df8ef9258dd4f73cfc93170a47e1))
* improve tui help and account setup ([e06c0ab](https://github.com/AdrianTNare/mxr/commit/e06c0ab85ce0e55747a723cb9d76d80681287780))
* mxr undo CLI + Tantivy reindex on restore ([88c5d88](https://github.com/AdrianTNare/mxr/commit/88c5d880f1ba29de60bf5a4773d704d2cb8455f2))
* mxr wrapped + mxr storage --by message ([de82195](https://github.com/AdrianTNare/mxr/commit/de82195c3aeaf283a560f162584ab92469550cd1))
* overhaul landing page, README, and docs ([827ab9a](https://github.com/AdrianTNare/mxr/commit/827ab9a36412b8fe23b135a6afe04573d117d8af))
* persistent search workspace ([033bca7](https://github.com/AdrianTNare/mxr/commit/033bca7894d29b6d7b0aae44db0db92bbdf2be1b))
* phase 1-4 — triage, drafts, llm scaffolding, sender view, screener ([fd1bf60](https://github.com/AdrianTNare/mxr/commit/fd1bf60370c91f30ede10a99fa5d5f187dcc66b0))
* **provider-imap:** real IMAP IDLE protocol wiring ([beb2d42](https://github.com/AdrianTNare/mxr/commit/beb2d42561e1ac5baf852bbca5e44de4e7957d89))
* refresh tui ux ([e0699bc](https://github.com/AdrianTNare/mxr/commit/e0699bc130fcea06877baf94821ea6535a57d5cd))
* replace lazy body hydration with eager fetch in core types ([745adf4](https://github.com/AdrianTNare/mxr/commit/745adf4ed044ceb14c60d8c1aaf2fc81b17207c7))
* self-healing analytics with live progress feedback ([82021fc](https://github.com/AdrianTNare/mxr/commit/82021fc7ef91aae348c799f776fc600877f73df2))
* send-flow correctness — sent visibility, draft state machine, idempotency ([1f0c7bb](https://github.com/AdrianTNare/mxr/commit/1f0c7bb2d6055d9bc42f3274ab0d5509c02dbb97))
* ship CLI v1 — compose journeys, mutation coherence, IMAP UIDPLUS safety ([68a96d8](https://github.com/AdrianTNare/mxr/commit/68a96d83bc421670b9e134130b24f07b42bca4fe))
* ship local-first docs and mutation history ([f7a1c77](https://github.com/AdrianTNare/mxr/commit/f7a1c77d55d507282fd46a415a34754178e13191))
* ship semantic search and diagnostics overhaul ([c4ab988](https://github.com/AdrianTNare/mxr/commit/c4ab988312a1732b2cd8d90b06184c17a3cec679))
* ship subscriptions mailbox ([28e0746](https://github.com/AdrianTNare/mxr/commit/28e07467cbb8613c2f0b7d2df0031d07753b1e74))
* store Gmail OAuth tokens in OS keychain instead of plaintext on disk ([c7aba27](https://github.com/AdrianTNare/mxr/commit/c7aba273862b53ee6ea74284302b83cac5bfa9cc))
* surface body-fetch failures in TUI + Gmail attachment base64 fix ([9fd48f7](https://github.com/AdrianTNare/mxr/commit/9fd48f7f851d10a721bdc7388c8a06e2f62a36cd))
* terminal-native design overhaul, fix crates.io readme ([797452b](https://github.com/AdrianTNare/mxr/commit/797452bde2252325e86d0b892934c64cee1439f1))
* TUI polish, theme presets, snapshot tests, and remaining work ([5ed4622](https://github.com/AdrianTNare/mxr/commit/5ed462291c472a4bf26e97ec070d458af6cd4bfa))
* **tui:** account repair from accounts view ([cf40be4](https://github.com/AdrianTNare/mxr/commit/cf40be491594afb38a9250fd2f58c0cf16c9dbdc))
* **tui:** add centralized theme system, remove all hardcoded colors ([62c0d09](https://github.com/AdrianTNare/mxr/commit/62c0d0923c247785b9e5ac72b62f48efb9ffbf4d))
* **tui:** add CLI-equivalent analytics views to TUI ([e034f1a](https://github.com/AdrianTNare/mxr/commit/e034f1a0459ba8a437c725820f6feed1bbc2dbcb))
* **tui:** add URL picker modal (L key) with labeled links ([793c73c](https://github.com/AdrianTNare/mxr/commit/793c73cd8b48f480a9167e1976fa2537e66cc0d5))
* **tui:** centralized async error surfacing — UserError ring buffer + reporter ([24b6c5d](https://github.com/AdrianTNare/mxr/commit/24b6c5de0b91944e20ced309e640c32f93e94c8d))
* **tui:** complete UI overhaul phases 2-10 ([a0da9e2](https://github.com/AdrianTNare/mxr/commit/a0da9e256e640b1c84f606fb733447af1416d5fc))
* **tui:** four analytics views unified in one Analytics screen ([712921e](https://github.com/AdrianTNare/mxr/commit/712921e1252b52d81051b571433072dcf8615e85))
* **tui:** highlight URLs in message body with blue underline ([4b7b97f](https://github.com/AdrianTNare/mxr/commit/4b7b97fc88db334a8e49003c87d13d408a4b55fa))
* **tui:** HTML view polish — clearer placeholders + scroll on toggle ([fb0cfc1](https://github.com/AdrianTNare/mxr/commit/fb0cfc13a3de15c08a74a6a400f83848d746ddab))
* **tui:** rule form shell hooks + client-side validation ([8eba799](https://github.com/AdrianTNare/mxr/commit/8eba7993329d2b6380e5cd8045ec63541db48424))
* **tui:** saved-search form data model + dispatch helpers ([dc7da63](https://github.com/AdrianTNare/mxr/commit/dc7da6369f0307cf7327f50a598223bd92d71577))
* **tui:** saved-search modal + sidebar n/e/d + dispatch wiring ([1a59da4](https://github.com/AdrianTNare/mxr/commit/1a59da4510afae12ed1a3fa721d2f975f503418a))
* **tui:** semantic controls in command palette ([049fba8](https://github.com/AdrianTNare/mxr/commit/049fba8b61f23f4f0607515850a3752ce79a3123))
* **tui:** task-oriented help section ([8108c21](https://github.com/AdrianTNare/mxr/commit/8108c2119d78842085838bdc6bcea7bc2c570e4d))
* **tui:** undo binding — `u` reverses the most recent destructive mutation ([1a504fa](https://github.com/AdrianTNare/mxr/commit/1a504fa95642e2c7cf9165ce238cbafaae8c2457))
* undo daemon pipeline — snapshot, restore, reverse-op ([40c7149](https://github.com/AdrianTNare/mxr/commit/40c714961bf80a0b41df07144e3adfe650f3e2d2))
* undo log foundation — store layer + protocol surface ([d17dc21](https://github.com/AdrianTNare/mxr/commit/d17dc215a78a57b97bfc48aa9c69bcc3abef38c1))
* update IPC protocol for eager body fetch and server drafts ([44ba608](https://github.com/AdrianTNare/mxr/commit/44ba6086b280ff4494dcce57c30d90a4ff49d4dd))
* v1 TUI ship-blockers — send-to-Sent visibility and IPC connection state ([c57c214](https://github.com/AdrianTNare/mxr/commit/c57c21409c208c150e8a913465dc6739179f5dba))
* **web:** harden bridge stability ([ce5cc8d](https://github.com/AdrianTNare/mxr/commit/ce5cc8d8d798a3d92535edd0feb3764db1ed37a3))
* **web:** improve mail navigation and sender profiles ([b103fe2](https://github.com/AdrianTNare/mxr/commit/b103fe23ded7bc003fbd923d4f3cea7fcfee3e67))


### Bug Fixes

* [] add desktop RPM license metadata ([373b61d](https://github.com/AdrianTNare/mxr/commit/373b61d7f5ceedfb8bee380a0a8356cf8df565aa))
* [] add desktop RPM release metadata ([ddce3be](https://github.com/AdrianTNare/mxr/commit/ddce3be52bd5bd5be492764dd6aa49c5752f2807))
* [] avoid envelope id decode panic ([4aaf902](https://github.com/AdrianTNare/mxr/commit/4aaf9024539106e6dd5fd3ef62050bbbdefcdfc9))
* [] clean rebase fallout ([325e823](https://github.com/AdrianTNare/mxr/commit/325e823cd1044a340f2489df37babf5962671ffe))
* [] clear ship-blocking test gates ([bb91a4c](https://github.com/AdrianTNare/mxr/commit/bb91a4c7198dc1c9a9183cdcb9d54b63aa621a7a))
* [] harden desktop app shell ([f0bc7b0](https://github.com/AdrianTNare/mxr/commit/f0bc7b07d46141c3d0ac5b30c9722061a3384936))
* [] harden desktop packaged smoke ([9afaf20](https://github.com/AdrianTNare/mxr/commit/9afaf20087ff84baeb83d9f231ec81d8e1c783bd))
* [] reconcile folder mutations ([f09ff54](https://github.com/AdrianTNare/mxr/commit/f09ff544ae5870204d068897e4682935277028a9))
* [] resolve label refs for mutations ([e5599fb](https://github.com/AdrianTNare/mxr/commit/e5599fb1d90ace5d80a9653bcb5d8baada698a4a))
* [] route search escape to inbox ([b119307](https://github.com/AdrianTNare/mxr/commit/b119307222ec7b900d97d2cd9331e5298b995e75))
* [] satisfy validation lint fixes ([41ea5e9](https://github.com/AdrianTNare/mxr/commit/41ea5e93bba65fb8abe071cf3ec89ef5b2fa7184))
* [] satisfy warning-deny cargo check ([4dd90c0](https://github.com/AdrianTNare/mxr/commit/4dd90c03fea99ed5d7093e23650da8eb9069a43b))
* [] scope sync command by account ([5622a69](https://github.com/AdrianTNare/mxr/commit/5622a6964821cfc5c167ccdbbe10d90b8a76297d))
* [] tighten semantic search pipeline ([b5457be](https://github.com/AdrianTNare/mxr/commit/b5457bed97e3f5483912bfb79db21082d7974a1d))
* align lockfile with v0.4.17 publish ([98ffc9e](https://github.com/AdrianTNare/mxr/commit/98ffc9e48405bcfe17adb295bda2707a5341de7a))
* analytics correctness — date floor, time-window filters, reply-pair backfill ([ce7270f](https://github.com/AdrianTNare/mxr/commit/ce7270fb1955c9be78eb38e897b96e901ac7f173))
* avoid keychain prompts and recover message bodies ([61560bb](https://github.com/AdrianTNare/mxr/commit/61560bbed8ed870e0f3b82590d65d49c0540ff92))
* build artifacts for release-prepare commits even when diff is version-only ([dc3ab44](https://github.com/AdrianTNare/mxr/commit/dc3ab444ccf04bc1936e05b926fe5a235e55c571))
* build Linux x86_64 natively with libssl-dev, skip aarch64-linux for now ([034bf4e](https://github.com/AdrianTNare/mxr/commit/034bf4e73660490a41a59c35443b4eaca0ed0906))
* cache browser-open files ([1a25dc9](https://github.com/AdrianTNare/mxr/commit/1a25dc9020ecce5a648e87fe142ef5f75288c459))
* cache provider secrets and restore tui shortcuts ([bd4d8c6](https://github.com/AdrianTNare/mxr/commit/bd4d8c66f3e12191f70196e95afd4334e7fb9400))
* clarify message view states ([1dbac54](https://github.com/AdrianTNare/mxr/commit/1dbac540599e977e87707690a557a39b40c5d633))
* collapse mxr into a single publishable package ([b83b9e6](https://github.com/AdrianTNare/mxr/commit/b83b9e6bded098bc3a0e15a758ce91b7beac7370))
* complete desktop mail parity ([b19ba5c](https://github.com/AdrianTNare/mxr/commit/b19ba5c2553f6df3541505c17a398550432efcdb))
* correct release archive naming for homebrew compatibility ([23131c5](https://github.com/AdrianTNare/mxr/commit/23131c58b72e00f2a7f17f83a652b106edff619b))
* debounce body fetches during rapid scrolling in ThreePane mode ([f857b2a](https://github.com/AdrianTNare/mxr/commit/f857b2aeec6534aee310de083cac2cec66472f29))
* drop unused Timelike import to clear CI -D warnings ([67465a7](https://github.com/AdrianTNare/mxr/commit/67465a72e5df30a33caf10e592100f4d7392c3ab))
* enable cargo install mxr via crates.io ([583f26a](https://github.com/AdrianTNare/mxr/commit/583f26ad46bb01c27a107a4ef6deb0c0bcff65c5))
* force SQLX_OFFLINE=true via build.rs in published crates ([425c383](https://github.com/AdrianTNare/mxr/commit/425c383fbc34f8929e96ec3d177db7777050bec1))
* gracefully handle missing providers instead of panicking ([5cbf473](https://github.com/AdrianTNare/mxr/commit/5cbf4733cac2830732db4a448c487a05d27f0f5c))
* harden crates publish path ([d81a790](https://github.com/AdrianTNare/mxr/commit/d81a7901f86715791270f82f4913869242a3a881))
* improve tui interaction recovery ([45d7fff](https://github.com/AdrianTNare/mxr/commit/45d7fffbb68a28fb8e37a1b3ab452f1ec815a2ac))
* isolate account mutations ([c2426e9](https://github.com/AdrianTNare/mxr/commit/c2426e91789bdc19d099457d6de7479988863992))
* load accounts at startup for sidebar account switcher ([2142297](https://github.com/AdrianTNare/mxr/commit/21422973fbae97a058de48d8abaa013c383ba244))
* make crates publish rerunnable ([7e63e79](https://github.com/AdrianTNare/mxr/commit/7e63e791486b5fe71c906388cbe8bd8d96adae2a))
* make release-please handle workspace crates ([cc81ec9](https://github.com/AdrianTNare/mxr/commit/cc81ec97d4ece363ba3317c5b187200391b09099))
* make search results behave like mailbox ([f183d1c](https://github.com/AdrianTNare/mxr/commit/f183d1cd6a2d1a9f0aa9e9309d3eea54b91739e1))
* multi-account UX, sidebar jump, search multi-select ([4879bb0](https://github.com/AdrianTNare/mxr/commit/4879bb00bfff7841bc62ee77b0eb7a2955708de5))
* package sqlx metadata with mxr-store ([e975409](https://github.com/AdrianTNare/mxr/commit/e9754094857a49e0bdb97729722c121d36a673fb))
* pass Gmail OAuth secrets to release build steps ([e977035](https://github.com/AdrianTNare/mxr/commit/e977035837972b62300066a70a91f493f3a08955))
* per-crate .sqlx and conditional build.rs offline default ([ea43325](https://github.com/AdrianTNare/mxr/commit/ea433258be28d9ccd1dda8cbf10871457f91c36b))
* polish desktop workflows ([c08629d](https://github.com/AdrianTNare/mxr/commit/c08629d8178d9f1249bcfdedc12d9428a4053d20))
* prevent silent label corruption with transactional set_message_labels ([0a6d40e](https://github.com/AdrianTNare/mxr/commit/0a6d40e8a05d4f2ab2bb56e3473d0dcd6e613756))
* prioritize file attachments in attachment modal ([486b062](https://github.com/AdrianTNare/mxr/commit/486b0621145ca1622b1f1c3ba0ac92e4da87319b))
* **provider-gmail:** normalize OAuth scope order in keychain lookups ([8844df4](https://github.com/AdrianTNare/mxr/commit/8844df4d18a859d2c3663600ab010af1d0077993))
* publish async-imap fork as mxr-async-imap, make all crates publishable ([0e808cb](https://github.com/AdrianTNare/mxr/commit/0e808cb965bb45adbc6dfc6f483b119aad7f4e92))
* publish mxr-test-support before its dependents ([d107405](https://github.com/AdrianTNare/mxr/commit/d10740514f01b28242582ca179e2da393a89497b))
* publish test support before readers ([81f8714](https://github.com/AdrianTNare/mxr/commit/81f8714ffc9860b20497869809217565f1178a9b))
* publish vendored async-imap before mxr release ([8fd5a77](https://github.com/AdrianTNare/mxr/commit/8fd5a777e96bdb5e27955b1282a2ed9ea1db1962))
* recover broken daemon sockets ([4d5f298](https://github.com/AdrianTNare/mxr/commit/4d5f298cc1562765adef4eaf20a90ac2a2519722))
* rehydrate missing bodies and render non-text mail ([a744ff7](https://github.com/AdrianTNare/mxr/commit/a744ff7fc1e224a42d2fad368e58161201950f65))
* release 0.4.10 search tab hydration ([b0b4354](https://github.com/AdrianTNare/mxr/commit/b0b4354f093e21764b0d76a543995afe55f12762))
* release 0.4.12 tui contrast recovery ([1dd0ed6](https://github.com/AdrianTNare/mxr/commit/1dd0ed6a2049124193634433a7d4e2f4d2250af5))
* release 0.4.13 search recovery ([ccd72f9](https://github.com/AdrianTNare/mxr/commit/ccd72f9f00578fb9fba61237fd053c146d9d0d6a))
* release 0.4.14 publish mxr-web ([33c9a39](https://github.com/AdrianTNare/mxr/commit/33c9a39fd3b0c84d3d82be06be4728412805a4d9))
* release 0.4.5 daemon startup recovery ([fd3a272](https://github.com/AdrianTNare/mxr/commit/fd3a27228a88feff778fd037630fe4ba05d30e8b))
* release 0.4.6 gmail stale cursor recovery ([13a11cd](https://github.com/AdrianTNare/mxr/commit/13a11cdb9880c991a5c50bf057a240ac520277bd))
* release 0.4.7 mailbox polish ([a4b9fe0](https://github.com/AdrianTNare/mxr/commit/a4b9fe0cb272f41b1a92f506765a640086125a1f))
* release 0.4.8 publish sync ([5b84d25](https://github.com/AdrianTNare/mxr/commit/5b84d255a6c877a12833bb7563abb9a295136979))
* release 0.4.9 search and diagnostics recovery ([961a55f](https://github.com/AdrianTNare/mxr/commit/961a55fdaa8548a2d665771bc0cd08202cb4ec34))
* release v0.4.19 workflow outputs ([5481009](https://github.com/AdrianTNare/mxr/commit/5481009a5fda065dba74fc48c13f0bc999c90993))
* release v0.4.20 artifact scope ([67a40a4](https://github.com/AdrianTNare/mxr/commit/67a40a44535f2b9b8df53b890f591cdd8020a5f4))
* release v0.4.21 cli scope ([7d65512](https://github.com/AdrianTNare/mxr/commit/7d655124f1f40ab976bc6db4582f41672d9b7446))
* release v0.4.22 publish gate ([b8ba725](https://github.com/AdrianTNare/mxr/commit/b8ba725b3eb3376a810f17af0c672c29caa4fb22))
* remove redundant crates wait ([a50e384](https://github.com/AdrianTNare/mxr/commit/a50e384663ce26db6c4e348c8de6719fdf176213))
* render complete homebrew formulas ([7984e91](https://github.com/AdrianTNare/mxr/commit/7984e912f49c859cb8ebc9237e86af3afbf7a968))
* render onboarding modal globally and surface sync errors ([872f36c](https://github.com/AdrianTNare/mxr/commit/872f36ce921bc107658cbc82bf5dccd8f8dd97ba))
* repair 0.4.1 release ([991553e](https://github.com/AdrianTNare/mxr/commit/991553eeeb42ea2ad3d6624c5a5da15636ffd930))
* repair 0.4.2 release ([59d8b7a](https://github.com/AdrianTNare/mxr/commit/59d8b7a55bd1b25f828aa2e4dcd6eee531790392))
* replace macos keychain items during repair ([b7cf41d](https://github.com/AdrianTNare/mxr/commit/b7cf41de53b72ca4ac3f37e0e905ced28fe665f1))
* restore browser open flow ([b36fdd2](https://github.com/AdrianTNare/mxr/commit/b36fdd27c3da1ecde4d71c8c1629f25a8acdb823))
* restore release version sync ([aa75cc5](https://github.com/AdrianTNare/mxr/commit/aa75cc5bf94726a07adf69d14ddce5b694af6135))
* retry crates publish on rate limits ([2f56d1c](https://github.com/AdrianTNare/mxr/commit/2f56d1c802fac205e949b92260b5682c3d7cfcd0))
* sanitize IMAP protocol parse errors for end users ([fe85eea](https://github.com/AdrianTNare/mxr/commit/fe85eea5d6995104eb30fe46feba826fb3d1c21d))
* stabilize daemon startup ([385c7c3](https://github.com/AdrianTNare/mxr/commit/385c7c3d1380f772577d6fe013b49169674f1067))
* stabilize tui archive selection and search results ([3d272ba](https://github.com/AdrianTNare/mxr/commit/3d272ba1465c040bf2820f2534a4d11876789523))
* support draft-first compose flow ([44a4013](https://github.com/AdrianTNare/mxr/commit/44a40131ed6ac434195f57069503b98ed4e6d8f0))
* switch Linux release targets from musl to gnu (OpenSSL compat) ([413250e](https://github.com/AdrianTNare/mxr/commit/413250e8ce738a75b34a6f9bdc50c7f79f2752e2))
* sync Cargo.lock to 0.4.56 workspace version ([3e10d7f](https://github.com/AdrianTNare/mxr/commit/3e10d7f83cc3017798774da278752b50bb2c21e9))
* tolerate duplicate crate publishes ([3c6a37e](https://github.com/AdrianTNare/mxr/commit/3c6a37ebfddc8410301fb3994d041b628c2c3834))
* topologically sort crates.io publish loop ([0c85af7](https://github.com/AdrianTNare/mxr/commit/0c85af76e9605ae04839dd172305c723ed74781f))
* **tui:** clean up deprecated method and dead code warnings ([5f21103](https://github.com/AdrianTNare/mxr/commit/5f21103da80758fc6187abb6972e95aea200ef17))
* **tui:** restore line numbers in mail list ([bebb3eb](https://github.com/AdrianTNare/mxr/commit/bebb3ebf90d8ef956eca7e1f4a834281d3555673))
* unblock crates publish ([491f068](https://github.com/AdrianTNare/mxr/commit/491f06834bcb2136a3bc1ee18f7276460519d0b4))
* unblock crates publish for 0.4.4 ([78dd8d8](https://github.com/AdrianTNare/mxr/commit/78dd8d81b28cfb60e8e62ae28c48e37c49ac4173))
* unify search message view behavior ([5c4bf60](https://github.com/AdrianTNare/mxr/commit/5c4bf6020f5725aa469f375fc9d80cc580c11ba3))
* update rustls webpki advisory ([a3f3dbd](https://github.com/AdrianTNare/mxr/commit/a3f3dbd3a2ab30a72e0b7e04ba9ba9f0a20003af))
* upsert labels and envelopes by natural key to survive ID derivation change ([3d4414b](https://github.com/AdrianTNare/mxr/commit/3d4414b2da247fa6533a865e04a2300331fd95bd))
* wait for crates index propagation ([f3bc0bc](https://github.com/AdrianTNare/mxr/commit/f3bc0bcf65501031ea56c37350057ec9a40b1508))


### Refactoring

* [] compose TUI app state ([e616c31](https://github.com/AdrianTNare/mxr/commit/e616c31ba4e6ce7879c60da95567472864b908b7))
* [] formalize IPC buckets ([ed16b37](https://github.com/AdrianTNare/mxr/commit/ed16b372f6bdf9f8948982d7c62f51bf89911e42))
* [] make workspace boundaries real ([09fba61](https://github.com/AdrianTNare/mxr/commit/09fba6146d4bdf04b0ea433cc6faab0d7907c635))
* adapt daemon to eager body fetch ([995a9d8](https://github.com/AdrianTNare/mxr/commit/995a9d8bb3a8dcbf220da2a0dd6ad93c9e712b78))
* harden async runtime paths ([0147e4f](https://github.com/AdrianTNare/mxr/commit/0147e4f1fd838a483b1fb8c2ebd293bc7e264545))
* improve smart pointer usage ([7523f23](https://github.com/AdrianTNare/mxr/commit/7523f2322bce2c491f9143735f0c13ac72e5a310))
* remove lazy body fetch from store, add contacts query ([3b4eb1d](https://github.com/AdrianTNare/mxr/commit/3b4eb1dd28d8a1fef65e09cdff15a2c7464337fa))
* rename mxr-daemon package to mxr for simpler cargo install ([24aaf3d](https://github.com/AdrianTNare/mxr/commit/24aaf3df9f48122658f87aca6a3310601e08cca4))
* track applied DB migrations in schema_migrations table ([98f6a87](https://github.com/AdrianTNare/mxr/commit/98f6a8753956bf77ed95dd01ee5cb2484c7bcb5a))
* typed MxrError::RateLimited and IpcErrorKind::RateLimited ([6efddc0](https://github.com/AdrianTNare/mxr/commit/6efddc007c421e181306156361fed2875a49f27f))


### Documentation

* [] align IPC docs ([0853eef](https://github.com/AdrianTNare/mxr/commit/0853eefc5f19074728fb1af977d416ecff50e36a))
* [] document provider truth seams ([669a881](https://github.com/AdrianTNare/mxr/commit/669a881845be48c1551c5211e68425b6b464e535))
* [] document sync and search lifecycle ([1ec205f](https://github.com/AdrianTNare/mxr/commit/1ec205fe3cbcf9f717b9069eb979dd276b349ede))
* [] rewrite docs landing copy ([83b5436](https://github.com/AdrianTNare/mxr/commit/83b5436caa5f571d64680e41c1c0cbd6c023a605))
* [] update semantic search docs ([33b38b0](https://github.com/AdrianTNare/mxr/commit/33b38b0ef01d4db64302332bcfce75b745239b06))
* [] update site architecture ([3599ff2](https://github.com/AdrianTNare/mxr/commit/3599ff2084683a54ac1c117150b0593eb96269f1))
* add A010 — CLI v1 ship gate addendum ([ad45e17](https://github.com/AdrianTNare/mxr/commit/ad45e1723bab43f0f5db37632fe6ec33d288082e))
* add all documentation content pages ([805c72d](https://github.com/AdrianTNare/mxr/commit/805c72d313a243d1949570ec32d68f18ab2d1349))
* add analytics guide + CLI reference section ([c1ee7c5](https://github.com/AdrianTNare/mxr/commit/c1ee7c58c6dd64133e308401dbb3b917ec53f85b))
* add analytics workflow recipes — situations, not commands ([d189ead](https://github.com/AdrianTNare/mxr/commit/d189ead30ec9c3e430d10c98bbf643de82e55c39))
* add blueprint and implementation plans ([2d6861c](https://github.com/AdrianTNare/mxr/commit/2d6861cfab4378947950561d100814339fa6d063))
* add documentation site and legal pages ([793c527](https://github.com/AdrianTNare/mxr/commit/793c52713cb3ab5de47a658550502e5c6da0ff19))
* add IMAP/SMTP setup guide as first-class getting started page ([a213733](https://github.com/AdrianTNare/mxr/commit/a2137330f6612e3c220ee3e12df61febe8dbd951))
* add mxr CLI skill for AI agent integration ([b0b98d2](https://github.com/AdrianTNare/mxr/commit/b0b98d2c49f1d83ac63153888b674595f0c9cd7b))
* align docs and harden site build ([257032b](https://github.com/AdrianTNare/mxr/commit/257032bbcea859180005b71b47a10207f33352d5))
* **bridge:** add v0.5 HTTP bridge guide ([ddb9273](https://github.com/AdrianTNare/mxr/commit/ddb92732f442c7f5dc1cdd0cf3560fcb85bb4b33))
* **cli:** document undo, snooze, accounts repair/disable/remove, search operators ([c1a1e13](https://github.com/AdrianTNare/mxr/commit/c1a1e1331f7c4229320bba452f7e5952cc2a71e9))
* collaborative positioning, fix broken install methods ([11a71ec](https://github.com/AdrianTNare/mxr/commit/11a71ec1245529ce6252b8da3b4a389a6582c524))
* cover Analytics tab + self-healing rebuild flow ([99266af](https://github.com/AdrianTNare/mxr/commit/99266af1517826fa4a4346f8f8b80075a42579ed))
* cover mxr wrapped + storage --by message drill-down ([8c93236](https://github.com/AdrianTNare/mxr/commit/8c932364f14bcd3f1567ad72313ca3feb76be10b))
* document eager body fetch (D049) and daemon trait boundary ([f7e187c](https://github.com/AdrianTNare/mxr/commit/f7e187c0d6fedabfa1ac58e3834dc504de1658e9))
* drop ghost flags, lead with mxr accounts add for IMAP/SMTP ([58ea627](https://github.com/AdrianTNare/mxr/commit/58ea627e007bc3f8465e08dcb89359aed9d49213))
* expand comparison table with notmuch, meli, and nuanced feature details ([465d846](https://github.com/AdrianTNare/mxr/commit/465d846a9e00ccb40d6b775bcacfac2300fd0f5b))
* expand Gmail setup guide with full walkthrough ([b2e7c44](https://github.com/AdrianTNare/mxr/commit/b2e7c4499b18840cf4564b3b282980a81817b4bf))
* fix comparison table accuracy after audit ([8d4ac41](https://github.com/AdrianTNare/mxr/commit/8d4ac41e5ef1bce6a93e74423a4cc19813928a76))
* fix install instructions to match shipped reality ([1d4fbc9](https://github.com/AdrianTNare/mxr/commit/1d4fbc9e8973559f115cd7b013f8685d9022213b))
* flagship polish on landing page (impeccable pass) ([5b5eda1](https://github.com/AdrianTNare/mxr/commit/5b5eda1db95739cefa55aca9c64b4b01c4d9fe12))
* humanize all copy, update install to cargo install mxr ([b26b4eb](https://github.com/AdrianTNare/mxr/commit/b26b4eb673d6291fc31e90ed432e48528e2cb68e))
* install path, quick-start, troubleshooting, release-please drift ([b5e982d](https://github.com/AdrianTNare/mxr/commit/b5e982d305970a0c6931a31a0e304bba1f56abf3))
* overhaul landing page (dark default, no cards, nyx-influenced) ([86d738b](https://github.com/AdrianTNare/mxr/commit/86d738b820d6126768cf1a18ae1b80154f19f07b))
* replace pre-built binaries link with from-source until first release ([bcc8057](https://github.com/AdrianTNare/mxr/commit/bcc80571b07f7a285fb45804168e9ca8399cd0c7))
* reposition as the universal email CLI, lead with agent-native ([fd19d4a](https://github.com/AdrianTNare/mxr/commit/fd19d4adce7928758a695a8b992714e65842b162))
* restore docs navigation on the landing page ([b4417e1](https://github.com/AdrianTNare/mxr/commit/b4417e1d61af0a7599fcd9e95c7b92f4d22650b6))
* restructure landing page with proper layering and lineage timeline ([1e5aac0](https://github.com/AdrianTNare/mxr/commit/1e5aac0287d4aafca23c2949cfe8259dfee958d7))
* rewrite landing page around user superpowers ([8ca481a](https://github.com/AdrianTNare/mxr/commit/8ca481ae23090f3553b7b92104fe029704f02956))
* rewrite README with positioning and marketing copy ([bf40c57](https://github.com/AdrianTNare/mxr/commit/bf40c57c69cf3f759ace4b30b338fd3abfe3d536))
* update implementation plans and add release pipeline blueprint ([0c4cb0b](https://github.com/AdrianTNare/mxr/commit/0c4cb0b3b869807efe87f2370c1c55d6f230f7a0))
* update install instructions — all methods now live ([9d71c4c](https://github.com/AdrianTNare/mxr/commit/9d71c4ce90e7d0e3c9d86bf5ec785ae97d54bb85))

## [0.4.68](https://github.com/planetaryescape/mxr/compare/v0.4.67...v0.4.68) (2026-05-06)


### Features

* [] add Gmail-style search operators ([6b765bf](https://github.com/planetaryescape/mxr/commit/6b765bf9338bd9db6df6dbc11141480796ea6b10))
* add --dry-run to mxr send and mxr unsnooze ([d21b65b](https://github.com/planetaryescape/mxr/commit/d21b65b858840b97cc7df0efcff32547246e2713))
* store Gmail OAuth tokens in OS keychain instead of plaintext on disk ([c7aba27](https://github.com/planetaryescape/mxr/commit/c7aba273862b53ee6ea74284302b83cac5bfa9cc))
* surface body-fetch failures in TUI + Gmail attachment base64 fix ([9fd48f7](https://github.com/planetaryescape/mxr/commit/9fd48f7f851d10a721bdc7388c8a06e2f62a36cd))


### Bug Fixes

* upsert labels and envelopes by natural key to survive ID derivation change ([3d4414b](https://github.com/planetaryescape/mxr/commit/3d4414b2da247fa6533a865e04a2300331fd95bd))


### Refactoring

* track applied DB migrations in schema_migrations table ([98f6a87](https://github.com/planetaryescape/mxr/commit/98f6a8753956bf77ed95dd01ee5cb2484c7bcb5a))
* typed MxrError::RateLimited and IpcErrorKind::RateLimited ([6efddc0](https://github.com/planetaryescape/mxr/commit/6efddc007c421e181306156361fed2875a49f27f))


### Documentation

* **cli:** document undo, snooze, accounts repair/disable/remove, search operators ([c1a1e13](https://github.com/planetaryescape/mxr/commit/c1a1e1331f7c4229320bba452f7e5952cc2a71e9))
* drop ghost flags, lead with mxr accounts add for IMAP/SMTP ([58ea627](https://github.com/planetaryescape/mxr/commit/58ea627e007bc3f8465e08dcb89359aed9d49213))
* fix install instructions to match shipped reality ([1d4fbc9](https://github.com/planetaryescape/mxr/commit/1d4fbc9e8973559f115cd7b013f8685d9022213b))

## [0.4.63](https://github.com/planetaryescape/mxr/compare/v0.4.62...v0.4.63) (2026-05-04)


### Bug Fixes

* per-crate .sqlx caches and build.rs that respects DATABASE_URL so `cargo install --locked mxr` succeeds end-to-end

## [0.4.62](https://github.com/planetaryescape/mxr/compare/v0.4.61...v0.4.62) (2026-05-04)


### Bug Fixes

* default to SQLX_OFFLINE=true via build.rs in published crates so `cargo install --locked mxr` builds without a database

## [0.4.61](https://github.com/planetaryescape/mxr/compare/v0.4.60...v0.4.61) (2026-05-04)


### Bug Fixes

* topologically sort crates.io publish loop so dev-deps land before consumers

## [0.4.60](https://github.com/planetaryescape/mxr/compare/v0.4.59...v0.4.60) (2026-05-04)


### Bug Fixes

* publish mxr-test-support before its dependents in the crates.io publish loop

## [0.4.59](https://github.com/planetaryescape/mxr/compare/v0.4.58...v0.4.59) (2026-05-04)


### Bug Fixes

* add description metadata to internal crates so crates.io publish accepts them

## [0.4.58](https://github.com/planetaryescape/mxr/compare/v0.4.57...v0.4.58) (2026-05-04)


### Bug Fixes

* build artifacts for release-prepare commits even when the diff is version-only

## [0.4.57](https://github.com/planetaryescape/mxr/compare/v0.4.56...v0.4.57) (2026-05-04)


### Bug Fixes

* sync Cargo.lock to workspace version so `cargo build --locked` succeeds in release CI

## [0.4.56](https://github.com/planetaryescape/mxr/compare/v0.4.55...v0.4.56) (2026-05-04)


### Bug Fixes

* drop unused Timelike import to clear CI -D warnings ([67465a7](https://github.com/planetaryescape/mxr/commit/67465a72e5df30a33caf10e592100f4d7392c3ab))

## [0.4.55](https://github.com/planetaryescape/mxr/compare/v0.4.54...v0.4.55) (2026-05-04)


### Features

* CLI surface — non-interactive accounts add and logs --format json ([b7effc4](https://github.com/planetaryescape/mxr/commit/b7effc44c84d4b0042015c21d8201fb3cd618a30))
* email analytics — CLI commands ([0f48f63](https://github.com/planetaryescape/mxr/commit/0f48f6349e6a89be45f2a0deb02a0220d2464a8b))
* email analytics — protocol + daemon plumbing ([972612a](https://github.com/planetaryescape/mxr/commit/972612a95e44ce58d555ab6159299081d4a3d01c))
* email analytics — schema migrations + store APIs ([67a5194](https://github.com/planetaryescape/mxr/commit/67a51944805e55b2385006b7b58f07e2634af90b))
* gmail device flow for ssh and headless ([c7d2895](https://github.com/planetaryescape/mxr/commit/c7d2895a437a0c75db82ed20cf31b7384d17f599))
* send-flow correctness — sent visibility, draft state machine, idempotency ([1f0c7bb](https://github.com/planetaryescape/mxr/commit/1f0c7bb2d6055d9bc42f3274ab0d5509c02dbb97))


### Bug Fixes

* prevent silent label corruption with transactional set_message_labels ([0a6d40e](https://github.com/planetaryescape/mxr/commit/0a6d40e8a05d4f2ab2bb56e3473d0dcd6e613756))


### Documentation

* install path, quick-start, troubleshooting, release-please drift ([b5e982d](https://github.com/planetaryescape/mxr/commit/b5e982d305970a0c6931a31a0e304bba1f56abf3))

## [0.4.17](https://github.com/planetaryescape/mxr/compare/v0.4.16...v0.4.17) (2026-03-24)


### Bug Fixes

* collapse mxr into a single publishable package ([b83b9e6](https://github.com/planetaryescape/mxr/commit/b83b9e6bded098bc3a0e15a758ce91b7beac7370))

## [0.4.16](https://github.com/planetaryescape/mxr/compare/v0.4.15...v0.4.16) (2026-03-23)


### Bug Fixes

* make release-please handle workspace crates ([cc81ec9](https://github.com/planetaryescape/mxr/commit/cc81ec97d4ece363ba3317c5b187200391b09099))
