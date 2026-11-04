# Changelog

All notable changes to dagster-authkit will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

<!-- version list -->

## [1.3.0](https://github.com/MCBoarder289/dagster-authkit/compare/v1.2.0...v1.3.0) (2026-11-04)


### Features

* add development workflow automation ([314476e](https://github.com/MCBoarder289/dagster-authkit/commit/314476efba78a7c9a21d74ed4bb8d0dd8fe1cb37))
* add Helm chart for Kubernetes deployment ([376ef49](https://github.com/MCBoarder289/dagster-authkit/commit/376ef493b84c1b197fdd34bf46e2b283fbb846e5))
* add Helm chart for Kubernetes deployment ([a340e75](https://github.com/MCBoarder289/dagster-authkit/commit/a340e75603b71db31a334fc76e7d386bc4f28223))
* add LDAP authentication backend ([6ea6584](https://github.com/MCBoarder289/dagster-authkit/commit/6ea6584d70574c8057baf25ac3050053668317a3))
* add Makefile and example environments ([2e0b391](https://github.com/MCBoarder289/dagster-authkit/commit/2e0b391d67b42f3e6ce52ffa4d976041ae7a5039))
* Add proxy authentication backend with Authelia forward auth support ([879aae3](https://github.com/MCBoarder289/dagster-authkit/commit/879aae3ddfef71663f7212d5f1020b0bd3006522))
* add Redis support to rate limiter and refactor to backend pattern ([870f289](https://github.com/MCBoarder289/dagster-authkit/commit/870f289e2c9a1c5d1c8c937c91344380c4915e98))
* add service token for non-interactive API clients ([d7e54e0](https://github.com/MCBoarder289/dagster-authkit/commit/d7e54e0fe9a4bd4ecff5431af85b3b2838b3611c))
* add service token for non-interactive API clients ([f80fffb](https://github.com/MCBoarder289/dagster-authkit/commit/f80fffbb0fd91405ac6f54e97f46a76e4fabfe03)), closes [#15](https://github.com/MCBoarder289/dagster-authkit/issues/15)
* centralize RBAC permissions in RolePermissions class ([eab6832](https://github.com/MCBoarder289/dagster-authkit/commit/eab6832eb6435de44b56ed7ea673fc43e2e7327f))
* **core:** replace regex GraphQL parser with official AST ([0955373](https://github.com/MCBoarder289/dagster-authkit/commit/09553734be63d71d254a2b26856f2bdfad9888cf))
* expand GraphQL mutation RBAC mapping and fix config path ([86bfd2a](https://github.com/MCBoarder289/dagster-authkit/commit/86bfd2adcb7278a92e0a91a7fdc1f24c6fc0b010))
* hardening Redis session and rate limiter operations ([a93f0d5](https://github.com/MCBoarder289/dagster-authkit/commit/a93f0d5d5753906d542f83bcfe8c924a0b8c5dce))
* implement hierarchical RBAC with AuthUser dataclass ([a4755e2](https://github.com/MCBoarder289/dagster-authkit/commit/a4755e2165426c21040959170481bdfbab714748))
* implement session orchestrator with Redis support ([6f2559c](https://github.com/MCBoarder289/dagster-authkit/commit/6f2559ce1bcb5b2eff5005cb092067406eedffeb))
* let the Helm chart configure a Dagster workspace and instance ([9952bf0](https://github.com/MCBoarder289/dagster-authkit/commit/9952bf0fc0def87112d73278fec36cc92113ca32))
* let the Helm chart configure a Dagster workspace and instance ([d92f8e1](https://github.com/MCBoarder289/dagster-authkit/commit/d92f8e1c1ebb6c1a7bb3006aa9931905db8c807a)), closes [#21](https://github.com/MCBoarder289/dagster-authkit/issues/21)
* operationName support, unified role model, multi-pod tests ([4b5f9a2](https://github.com/MCBoarder289/dagster-authkit/commit/4b5f9a2384f5adcbb9e8c488ad4eb808f129ade6))
* **proxy:** Enhance groups header parser with multi-strategy support ([ef0b97f](https://github.com/MCBoarder289/dagster-authkit/commit/ef0b97f901cde6ae62ef3db27596e2789b7c30cb))
* publish a container image to GHCR on release ([2f5a71d](https://github.com/MCBoarder289/dagster-authkit/commit/2f5a71d41b825d5ff81d292fafaf3bd52bebe48e))
* publish a container image to GHCR on release ([2817179](https://github.com/MCBoarder289/dagster-authkit/commit/2817179ce01719b1d3546911fdf5950a2a58f0df)), closes [#20](https://github.com/MCBoarder289/dagster-authkit/issues/20)
* publish the Helm chart to GHCR and prepare it for Artifact Hub ([ed29546](https://github.com/MCBoarder289/dagster-authkit/commit/ed29546c8efd3f1af023ce330a535604f08d7f87))
* publish the Helm chart to GHCR and prepare it for Artifact Hub ([780e53b](https://github.com/MCBoarder289/dagster-authkit/commit/780e53b6d09253fe5120471dbc541327d3a898df)), closes [#22](https://github.com/MCBoarder289/dagster-authkit/issues/22)
* redesign UI with official Dagster design system ([e9f3594](https://github.com/MCBoarder289/dagster-authkit/commit/e9f3594e45624ac06467290b9efa65e9977e2d83))
* replace SQLite backend with Peewee ORM ([d5db137](https://github.com/MCBoarder289/dagster-authkit/commit/d5db137ea4815fc88810c7dd3b33b0d0583ece37))
* simplify Docker deployment with PostgreSQL and Redis ([f90c523](https://github.com/MCBoarder289/dagster-authkit/commit/f90c52326c86c9280da9489aa1d28f0c47f4e60d))
* **ui:** add resilient sidebar injection with retry and safe mode ([1b347e8](https://github.com/MCBoarder289/dagster-authkit/commit/1b347e8a90fff71791550df58476331394661731))
* unify SQL backends with Peewee ORM ([58b0c60](https://github.com/MCBoarder289/dagster-authkit/commit/58b0c600e25f2adb5ed37e5990a8a1ec95385482))


### Bug Fixes

* add default_role param to can_execute; add B-11/B-12 tests ([a06158a](https://github.com/MCBoarder289/dagster-authkit/commit/a06158ae7a704429c42d881352ccb97848408139))
* add double-checked locking to get_rate_limiter singleton ([ddd2a56](https://github.com/MCBoarder289/dagster-authkit/commit/ddd2a5653d0ee1510bea87f506500b5fa04775be))
* add dummy bcrypt timing in authenticate, use Database.bind instead of class-level mutation ([1512094](https://github.com/MCBoarder289/dagster-authkit/commit/15120944d4677685af1828de347be079a5e94e7c))
* add exc_info=True to logger.error/critical calls across codebase ([4d16f24](https://github.com/MCBoarder289/dagster-authkit/commit/4d16f24e532934dcc8e9582dc1d1684b1526b15d))
* add hard cap to revoked-token store to prevent OOM ([d69a3b2](https://github.com/MCBoarder289/dagster-authkit/commit/d69a3b2658253ba968fddd7ad28c6cdf27ee9bd9))
* add metrics token gate, CSRF, security headers, and fail-closed paths ([376ef49](https://github.com/MCBoarder289/dagster-authkit/commit/376ef493b84c1b197fdd34bf46e2b283fbb846e5))
* add optional token-based protection for /auth/metrics ([3a8e171](https://github.com/MCBoarder289/dagster-authkit/commit/3a8e1717d6dd7f9d8c309a986815006d24eca98f))
* add pytest-cov to dev dependencies ([07a3d79](https://github.com/MCBoarder289/dagster-authkit/commit/07a3d79086ee76d4cfad97d5f0cb18291c00f5f6))
* bind CSRF token to client via double-submit cookie ([4b7f009](https://github.com/MCBoarder289/dagster-authkit/commit/4b7f009455ba23954e7e5af0683a0e3024bd14da))
* cache backend instances in registry to prevent connection leak ([2547de7](https://github.com/MCBoarder289/dagster-authkit/commit/2547de76f6d1fd3b17619abde5fa02b36b94cf0c))
* change_role revokes sessions, non-dict GraphQL payloads, delete-user message ([e1dd30a](https://github.com/MCBoarder289/dagster-authkit/commit/e1dd30adc768b8e89c4d2a080d6f7325d4c809b8))
* check Starlette Middleware.cls attribute for compatibility ([919946e](https://github.com/MCBoarder289/dagster-authkit/commit/919946e0435a5971da1935c8be49f385f2093e8e))
* correct Helm chart template defects ([dd4c69c](https://github.com/MCBoarder289/dagster-authkit/commit/dd4c69ce780105ab5c0eee2e24ee5a56ff09da71))
* correct Helm chart template defects ([2121824](https://github.com/MCBoarder289/dagster-authkit/commit/212182488ac06fb92c10501717a744c35290df57)), closes [#19](https://github.com/MCBoarder289/dagster-authkit/issues/19)
* correct release-prod dependency from nonexistent release-build to test job ([c94120b](https://github.com/MCBoarder289/dagster-authkit/commit/c94120b34b299f185ba186f7a832948cb01e6207))
* DB-backed session version for cross-pod revoke_all ([bd7094f](https://github.com/MCBoarder289/dagster-authkit/commit/bd7094f6281a69116bfe6ffd55a3b67184e154e8))
* Don't mint new CSRF token when existing still valid ([ee627ab](https://github.com/MCBoarder289/dagster-authkit/commit/ee627aba23365a0c68c159b816914f818f31275e))
* enable ruff rules TRY400 and LOG007 for exc_info enforcement ([b0f9d50](https://github.com/MCBoarder289/dagster-authkit/commit/b0f9d50eb3b90eae8048222a57eb302ee688fd17))
* escape HTML-special chars in user data before JSON injection ([f124de3](https://github.com/MCBoarder289/dagster-authkit/commit/f124de3dd13a9d809b595d98daa73689d7b0f6f2))
* fail closed on malformed GraphQL batch payloads ([4bce5ef](https://github.com/MCBoarder289/dagster-authkit/commit/4bce5efc9c67219a50e139dda3dd2afd71279178))
* handle scalar LDAP attribute values in _first_value ([7d0e537](https://github.com/MCBoarder289/dagster-authkit/commit/7d0e537b88fc29a84fe3625dddd64270da1a29b7))
* harden auth across RBAC, sessions, LDAP, and rate limiting ([376ef49](https://github.com/MCBoarder289/dagster-authkit/commit/376ef493b84c1b197fdd34bf46e2b283fbb846e5))
* harden service token header handling ([82bc1ed](https://github.com/MCBoarder289/dagster-authkit/commit/82bc1ed1ac3f5ae6b72a436dbeea015c4b29a28d))
* health check, audit log accuracy, LDAP connection leak, REST RBAC config ([ca5ecce](https://github.com/MCBoarder289/dagster-authkit/commit/ca5ecce9747396caabec1bcb43cd574a0bfb7ad8))
* implement change-role CLI command and remove dead 'user' entry ([8fbd125](https://github.com/MCBoarder289/dagster-authkit/commit/8fbd125e05b7d8656d29c1d4a16fc411893d225d))
* inject security headers on all response paths ([8053442](https://github.com/MCBoarder289/dagster-authkit/commit/805344253a616a2602d32718476c9d1ca65f537e))
* LDAP log level, connection leak, unused param, TLS warning ([2f78ac0](https://github.com/MCBoarder289/dagster-authkit/commit/2f78ac00f32004afc04155d9eb897abae8340998))
* LDAP single-value attributes and bcrypt hash compatibility ([4e0ca30](https://github.com/MCBoarder289/dagster-authkit/commit/4e0ca305ed56beccb595ce58eea08b0b37b89300))
* **ldap:** overhaul SAFE_SYNC strategy and OpenLDAP group support ([a2de4e1](https://github.com/MCBoarder289/dagster-authkit/commit/a2de4e1ca817b096d0753ec934eccc1aa18d0e07))
* link updated ([67b70e4](https://github.com/MCBoarder289/dagster-authkit/commit/67b70e46d4eaf579273e11daacd9a9dbf8029a80))
* log warning with exc_info when session validate fails ([b50c4c8](https://github.com/MCBoarder289/dagster-authkit/commit/b50c4c81a39b8c8d5e9edba7fe65047e73af5649))
* make can_execute deny-by-default with ADMIN default_role ([f664658](https://github.com/MCBoarder289/dagster-authkit/commit/f664658bb00e0049e862645ec776215078b9ca3e))
* make check_and_record atomic via backend method ([ff797be](https://github.com/MCBoarder289/dagster-authkit/commit/ff797bef3b60877a58c91cf12d14228315e9c93c))
* make rate limiter EXPIRE compatible with Redis 6 ([52b84a3](https://github.com/MCBoarder289/dagster-authkit/commit/52b84a31aad61c9766bb3d0817decbd7d866b05b))
* make the Helm chart start with default values ([06a1eb3](https://github.com/MCBoarder289/dagster-authkit/commit/06a1eb306960385f3b2e4551e35392d561630b9d))
* make the Helm chart start with default values ([fdb800c](https://github.com/MCBoarder289/dagster-authkit/commit/fdb800c4b3d488c1166f82029776f4f6aa3fd553)), closes [#18](https://github.com/MCBoarder289/dagster-authkit/issues/18)
* N-10 add cycle guard in fragment traversal, N-11 replace dead test_middleware var with assertion ([9367a3b](https://github.com/MCBoarder289/dagster-authkit/commit/9367a3b27093769b29da93d473d0990cd66977a1))
* OOM prevention in InMemoryRateLimiter -- max tracked entries guard ([e6f2953](https://github.com/MCBoarder289/dagster-authkit/commit/e6f2953e839800f4af362d52ead10a6dfe65e7ec))
* pass operator identity to change_role audit ([f65544d](https://github.com/MCBoarder289/dagster-authkit/commit/f65544dec304523ba26b90fbd65a701370dc3e6b))
* production secret key enforcement, sentinel safety, dual rate-limit ([b6a05b6](https://github.com/MCBoarder289/dagster-authkit/commit/b6a05b647208ee45d4da441348ec99f084bf1054))
* pure ASGI middleware -- WebSocket auth was being bypassed ([6153c4a](https://github.com/MCBoarder289/dagster-authkit/commit/6153c4acfed2ca6e4edbc27d61441ad9eb18bc44))
* rate-limit, middleware body hang, registry race, proxy examples ([7f106b7](https://github.com/MCBoarder289/dagster-authkit/commit/7f106b7c4d8fdaad4941951a8061f6af6a7597c5))
* readme badges ([0008756](https://github.com/MCBoarder289/dagster-authkit/commit/0008756c6e1c28123c18b92c0dd399427f92d362))
* remove action label from RBAC metric to prevent unbounded cardinality ([303d317](https://github.com/MCBoarder289/dagster-authkit/commit/303d317d3144462afbc1bc94b40bb890734df555))
* remove invalid pypi classifier ([ad52724](https://github.com/MCBoarder289/dagster-authkit/commit/ad5272437799cd0d7725d8521d148c0248c8887e))
* remove trusted IP list from proxy auth log ([e69cf5c](https://github.com/MCBoarder289/dagster-authkit/commit/e69cf5c14cbdfe7f7ead5c1a5ab0f9470995f1bc))
* remove username from metrics labels to prevent info leak ([f2deae2](https://github.com/MCBoarder289/dagster-authkit/commit/f2deae240931fe966225b6b933a643bf9606c2d8))
* replace print with logging for auto-generated SECRET_KEY warning ([aa7892b](https://github.com/MCBoarder289/dagster-authkit/commit/aa7892b0d903d4fd23014ae30dd08d55193a496e))
* require explicit image.tag in Helm chart ([db0107b](https://github.com/MCBoarder289/dagster-authkit/commit/db0107b91bb0d37efa6fa7c98616403d48debfe5))
* resolve three UI injection bugs for Dagster 1.13.8 + Starlette 1.3.1 ([2976607](https://github.com/MCBoarder289/dagster-authkit/commit/2976607adf81dc07f37b2099c88aa84c9507b39a))
* safely extract LDAP attribute first values in list_users ([3d2ba20](https://github.com/MCBoarder289/dagster-authkit/commit/3d2ba200fda30c4ac78ce6f5c0b71bad6ccd59bb))
* security - auth backends hardening ([e1b3278](https://github.com/MCBoarder289/dagster-authkit/commit/e1b3278616158ef6ac228dd8d40e0f827cfa57d2))
* security - GraphQL analyzer RBAC bypass and unparseable query handling ([a49632b](https://github.com/MCBoarder289/dagster-authkit/commit/a49632be11cc8de82109b3e5d426cdae6e369901))
* security - patch resilience and XSS prevention ([8279f26](https://github.com/MCBoarder289/dagster-authkit/commit/8279f262d1fbd8260a7616954aa8dde59df40c59))
* session, rate-limiter, config, audit and health improvements ([c6fc1b9](https://github.com/MCBoarder289/dagster-authkit/commit/c6fc1b9adbe33979eab2a5bde898eece7d2473b7))
* **sqlite:** improve quickstart reliability ([6e2bcb4](https://github.com/MCBoarder289/dagster-authkit/commit/6e2bcb445af061e4bef72b5df694b942abd5d27e))
* stateless CSRF + async thread pool for login handler ([176988b](https://github.com/MCBoarder289/dagster-authkit/commit/176988bdcc47db7145d6d2d85b7d68f3952d7d23))
* sync Helm chart with app config and wire into semantic-release ([6b92d84](https://github.com/MCBoarder289/dagster-authkit/commit/6b92d845052c2a0adf696cad69fadaf3d4d95d5d))
* unbind LDAP connection in _get_user_attributes finally block ([12e2a71](https://github.com/MCBoarder289/dagster-authkit/commit/12e2a717abc0c7825b227cc04ab0561d057079e7))
* update PyPI badges in README ([be48181](https://github.com/MCBoarder289/dagster-authkit/commit/be48181a1e521e47ce461766a43f4644c4fe4e39))
* update upload-artifact to v5 to resolve Node 20 deprecation ([9134fe4](https://github.com/MCBoarder289/dagster-authkit/commit/9134fe4a6d748e758a36a7bda5598aa7b3dd3086))
* updated CSP headers for dagster ui updates ([d149f72](https://github.com/MCBoarder289/dagster-authkit/commit/d149f72433c7439bcb11a31447b7adb6137bd8f3))
* updated CSP headers for dagster ui updates ([f94eeb4](https://github.com/MCBoarder289/dagster-authkit/commit/f94eeb4cf4ce72405a08b7b7ea4ba6f1c7caf8cd))
* use Role[role_name] instead of nonexistent Role.from_string ([e358a1e](https://github.com/MCBoarder289/dagster-authkit/commit/e358a1e4935f56d1e35daf9bebe695c529aee4ea))
* validate PBKDF2 split parts, sanitize client_ip in log, strengthen verify_patches ([5ecd8fe](https://github.com/MCBoarder289/dagster-authkit/commit/5ecd8fed1d4ed9791da050e7b1b7f52d4df20afd))
* wire up track_login_attempt, track_session_created, track_request_duration in production ([0ae212b](https://github.com/MCBoarder289/dagster-authkit/commit/0ae212bee31b04b91191f7d00b56ae175faa3f26))


### Documentation

* add __init__.py package descriptions for all subpackages ([8834e63](https://github.com/MCBoarder289/dagster-authkit/commit/8834e630867b24d6080fde04dc5d55adfc75ab3c))
* add badges and visitor counter widget via CI ([376ef49](https://github.com/MCBoarder289/dagster-authkit/commit/376ef493b84c1b197fdd34bf46e2b283fbb846e5))
* add badges to README (CI, coverage, PyPI, downloads) ([baaa201](https://github.com/MCBoarder289/dagster-authkit/commit/baaa201959f6b4afe2b456482df808063056192c))
* add comprehensive documentation for initial release ([8a6be6e](https://github.com/MCBoarder289/dagster-authkit/commit/8a6be6e88c8e647e2fdfacaa896092f4243c215b))
* add website visitor counter widget via CI, keep README clean ([4fba683](https://github.com/MCBoarder289/dagster-authkit/commit/4fba683c1457e79b2a7fc9b571a52eb49e6080e6))
* API routes, health endpoints, CLI commands, middleware ([700258b](https://github.com/MCBoarder289/dagster-authkit/commit/700258be15a82c1279e42dd82f877348ae7b99a7))
* audit, config, logging, display, templates -- full API docs ([8d6040e](https://github.com/MCBoarder289/dagster-authkit/commit/8d6040e6fa54728464a4c39e8de15084b460f4e3))
* **authelia:** add complete Authelia integration example with Caddy reverse proxy ([657129c](https://github.com/MCBoarder289/dagster-authkit/commit/657129ccdd69fb4bd766c61dbe788a31d890fea7))
* backend __init__ docstrings + RBAC method examples ([00ffea7](https://github.com/MCBoarder289/dagster-authkit/commit/00ffea7c68d2426916a4121c92868c7dd661f1dd))
* enable automated CHANGELOG and backfill v1.0.0 release notes ([317a10f](https://github.com/MCBoarder289/dagster-authkit/commit/317a10f7857abf6a93399ed68931e22b24f1e86d))
* **k8s:** add complete Kubernetes example with Authelia + LDAP + Caddy + Dagster ([541ac74](https://github.com/MCBoarder289/dagster-authkit/commit/541ac7468f7d5e091866d45a644ea46ad4f2afb2))
* restructure README with v0.2.0 features and redefined roadmap ([f3f567d](https://github.com/MCBoarder289/dagster-authkit/commit/f3f567d7a03217b3eca5450613352277110287a1))
* session, security, rate_limiter -- class and method docstrings ([14a126e](https://github.com/MCBoarder289/dagster-authkit/commit/14a126e8b81536289225d70b5533ab20fb5f5cb9))
* update Python version badge and fix CLI example flag ([ba7affb](https://github.com/MCBoarder289/dagster-authkit/commit/ba7affb62b8f823987f4edc24e27165997b1bc52))
* update README with honest disclaimers and LDAP status ([0c62aa4](https://github.com/MCBoarder289/dagster-authkit/commit/0c62aa496ecccf96ca774a4fe94d56adb481b0c4))

## [1.2.0](https://github.com/maltzsama/dagster-authkit/compare/v1.1.0...v1.2.0) (2026-10-10)


### Features

* let the Helm chart configure a Dagster workspace and instance ([9952bf0](https://github.com/maltzsama/dagster-authkit/commit/9952bf0fc0def87112d73278fec36cc92113ca32))
* let the Helm chart configure a Dagster workspace and instance ([d92f8e1](https://github.com/maltzsama/dagster-authkit/commit/d92f8e1c1ebb6c1a7bb3006aa9931905db8c807a)), closes [#21](https://github.com/maltzsama/dagster-authkit/issues/21)
* publish a container image to GHCR on release ([2f5a71d](https://github.com/maltzsama/dagster-authkit/commit/2f5a71d41b825d5ff81d292fafaf3bd52bebe48e))
* publish a container image to GHCR on release ([2817179](https://github.com/maltzsama/dagster-authkit/commit/2817179ce01719b1d3546911fdf5950a2a58f0df)), closes [#20](https://github.com/maltzsama/dagster-authkit/issues/20)
* publish the Helm chart to GHCR and prepare it for Artifact Hub ([ed29546](https://github.com/maltzsama/dagster-authkit/commit/ed29546c8efd3f1af023ce330a535604f08d7f87))
* publish the Helm chart to GHCR and prepare it for Artifact Hub ([780e53b](https://github.com/maltzsama/dagster-authkit/commit/780e53b6d09253fe5120471dbc541327d3a898df)), closes [#22](https://github.com/maltzsama/dagster-authkit/issues/22)


### Bug Fixes

* correct Helm chart template defects ([dd4c69c](https://github.com/maltzsama/dagster-authkit/commit/dd4c69ce780105ab5c0eee2e24ee5a56ff09da71))
* correct Helm chart template defects ([2121824](https://github.com/maltzsama/dagster-authkit/commit/212182488ac06fb92c10501717a744c35290df57)), closes [#19](https://github.com/maltzsama/dagster-authkit/issues/19)
* make the Helm chart start with default values ([06a1eb3](https://github.com/maltzsama/dagster-authkit/commit/06a1eb306960385f3b2e4551e35392d561630b9d))
* make the Helm chart start with default values ([fdb800c](https://github.com/maltzsama/dagster-authkit/commit/fdb800c4b3d488c1166f82029776f4f6aa3fd553)), closes [#18](https://github.com/maltzsama/dagster-authkit/issues/18)

## v1.1.0 (2026-10-10)

### Bug Fixes

- Harden service token header handling
  ([`82bc1ed`](https://github.com/maltzsama/dagster-authkit/commit/82bc1ed1ac3f5ae6b72a436dbeea015c4b29a28d))

### Chores

- Readme badges
  ([`4a61eb4`](https://github.com/maltzsama/dagster-authkit/commit/4a61eb4016b2c0cf04ed72fe4c0b3cb5a103f6e8))

### Features

- Add service token for non-interactive API clients
  ([`f80fffb`](https://github.com/maltzsama/dagster-authkit/commit/f80fffbb0fd91405ac6f54e97f46a76e4fabfe03))


## v1.0.1 (2026-08-23)

### Bug Fixes

- Update PyPI badges in README
  ([`be48181`](https://github.com/maltzsama/dagster-authkit/commit/be48181a1e521e47ce461766a43f4644c4fe4e39))

- Update upload-artifact to v5 to resolve Node 20 deprecation
  ([`9134fe4`](https://github.com/maltzsama/dagster-authkit/commit/9134fe4a6d748e758a36a7bda5598aa7b3dd3086))

### Chores

- Update tooling config for Ruff and Black
  ([`0e370c1`](https://github.com/maltzsama/dagster-authkit/commit/0e370c166f5e11f869ce88b24d813806f1d5adde))

### Continuous Integration

- Gate releases and consolidate publish workflow
  ([`513d7d4`](https://github.com/maltzsama/dagster-authkit/commit/513d7d4e080f57546658de33a472de6918499b60))

### Documentation

- Enable automated CHANGELOG and backfill v1.0.0 release notes
  ([`317a10f`](https://github.com/maltzsama/dagster-authkit/commit/317a10f7857abf6a93399ed68931e22b24f1e86d))

### Refactoring

- Apply linting fixes across codebase
  ([`4c26242`](https://github.com/maltzsama/dagster-authkit/commit/4c26242c917b52205ee09f2a50f9cdfea379c4c6))

- Clean up unused imports in tests
  ([`b299639`](https://github.com/maltzsama/dagster-authkit/commit/b299639fdaefe20c718e6e29aee0e380df8ce288))

- Remove unused imports and fix import ordering
  ([`23a5d8e`](https://github.com/maltzsama/dagster-authkit/commit/23a5d8e0f6c967d83d67a8877216452a586f7e8b))


## [1.0.0] - 2026-08-05

### Features

* **Helm Chart:** New production-ready Kubernetes chart under `helm/dagster-authkit/`, synced with the application's config (env vars, secrets, image tag) and wired into semantic-release versioning.

### Bug Fixes

* **CSRF:** Tokens now bound to the client via a double-submit signed cookie.
* **GraphQL parsing:** Fail closed on malformed batch payloads instead of erroring.
* **Metrics:** Added optional token-based protection for `/auth/metrics`; removed username/action labels to prevent unbounded cardinality.
* **RBAC deny-by-default:** `can_execute` and `DagsterAuthMiddleware` now deny unknown mutations with an `ADMIN` default role.
* **Rate limiting:** `check_and_record` made atomic via the backend method; added double-checked locking to the singleton; rate limiter `EXPIRE` now compatible with Redis 6.
* **LDAP:** Unbind connection in `_get_user_attributes` `finally`; safe LDAP attribute first-value extraction in `list_users`; scalar `_first_value` handling.
* **Sessions:** Hard cap on `_MAX_REVOKED` revoked-token store to prevent OOM; `CookieBackend` revocation capped.
* **Detection layer:** Check `Middleware.cls` attribute for Starlette compatibility.
* **Change role:** Restored `change-role` CLI command; pass operator identity to `change_role` audit.
* **Security headers:** Inject headers on all response paths.
* **Logging:** `exc_info=True` on `logger.error/critical` calls; HTML-escape user data before JSON injection.
* **Secret key:** Replace `print` with logging for auto-generated `SECRET_KEY` warning.
* **Proxy auth:** Removed trusted IP list from proxy auth log.
* **Helm:** Require explicit `image.tag` in the chart.

### CI / DevEx

* Semantic-release + uv-based workflows; fix docs deploy.
* Replace `[all]` extra with `[sqlite]` in CI to avoid native build deps.
* Restore `contents:write` for the semantic-release push; grant `actions:write` in the publish workflow.

### Testing

* Boosted coverage 44% → 52% (+98 tests).
* Added suites: detection layer, Redis rate limiter, metrics token gate, CookieBackend, CLI (24 tests), LDAP (64 tests), middleware (WebSocket/proxy/RBAC/helpers).

---
## [0.4.2] - 2026-07-17

### Bug Fixes

* **UI Injection (Starlette 1.x compat):** Fixed `TypeError: 'coroutine' object is not callable` when Dagster uses a sync `index_html_endpoint`. The patched handler now always awaits — previously the sync branch called `_inject_resilient_ui` (async) without `await`, returning an unawaited coroutine that Starlette could not invoke as a Response.
* **Middleware State Access:** Fixed silent injection skip on Starlette >=1.3.1 where `request.state` is backed by a plain dict. Now checks both `request.scope["state"]` (dict) and `request.state` (State object) for the authenticated user.
* **CSP Nonce Support:** Copied the `<script nonce="...">` from Dagster's existing scripts to injected blocks, fixing UI injection breakage on Dagster deployments with Content Security Policy nonces.

---

## [0.4.1] - 2026-07-14

### Bug Fixes

* **Bootstrap:** Admin username now configurable via `DAGSTER_AUTH_ADMIN_USER` (default: `admin`). Previously the username was hardcoded, making the documented `DAGSTER_AUTH_ADMIN_USER` env var non-functional.

---

## [0.4.0] - 2026-07-13

### Major Changes

**Cross-Pod Session Revocation (DB-backed)**

* Added `session_version` column to `users` table — bumps on `change_password`, `change_role`, `delete_user`
* `CookieBackend` now reads version from DB (with 10s TTL cache) for multi-pod safe revocation without Redis
* Automatic migration on first boot for existing databases
* Non-SQL backends get a `WARNING` about single-pod limitation

**Pure ASGI Middleware**

* Rewrote `DagsterAuthMiddleware` from `BaseHTTPMiddleware` to pure ASGI
* WebSocket connections (GraphQL subscriptions at `/graphql`) now authenticated via session cookie
* Unauthenticated WS connections closed with code 4001
* CORS preflight (`OPTIONS`) passes through before auth check

**RBAC: Deny-by-Default**

* Unknown GraphQL mutations now require `ADMIN` by default (was: open to `VIEWER`)
* Configurable via `DAGSTER_AUTH_UNKNOWN_MUTATION_ROLE`
* `operationName` support — multi-operation documents only check the named operation
* REST write minimum role configurable via `DAGSTER_AUTH_REST_WRITE_ROLE`

### Security Hardening

* **CSRF protection** — Signed double-submit cookie on login form (stateless, works multi-pod)
* **XSS prevention** — `html.escape()` on all user-controlled values in login and 403 pages
* **Open redirect hardening** — Protocol-relative URLs (`//evil.com`) blocked
* **Empty password rejection** — All backends refuse empty passwords (prevents unauthenticated LDAP binds)
* **Password hash compatibility** — Accepts `$2a$`/`$2y$` bcrypt prefixes in addition to `$2b$`
* **Proxy trust enforcement** — `DAGSTER_AUTH_PROXY_TRUSTED_IPS` required in proxy mode
* **Username sanitization** — Applied in SQL `add_user` (was only in web route)
* **Metrics hardening** — Removed `username` from metric labels (prevented info leak via `/metrics`)

### Core Improvements

* **Patch resilience** — Async/sync detection via `iscoroutinefunction`, `try/except` fallback to vanilla Dagster, idempotency guard
* **Backend instance caching** — Backend connections reused across requests (prevents connection pool exhaustion)
* **Dual rate-limiting** — Independent limits per username AND per IP
* **Unified role serialization** — `AuthUser.to_dict()` uses `role.value` (int) for cross-backend consistency
* **LDAP fixes** — Connection leak fixed (`try/finally`), timeout on all connections, single-value attribute handling
* **Health check** — Database check works for both `sql` and `sqlite` backends via cached Peewee connection
* **OAuth stub** — `OAuthBackend` class implemented (was empty file causing import errors)
* **Blocking I/O** — `backend.authenticate()` runs via `run_in_threadpool` to avoid event loop starvation

### Bug Fixes

* `change_role` now revokes sessions (was missing `revoke_all` call)
* Audit JSON now reflects actual method/path for REST denials (was hardcoded `POST /graphql`)
* `_find_user_dn` connection cleanup on LDAP exceptions
* Non-dict GraphQL payloads rejected with 400 instead of AttributeError
* CLI `delete-user` message corrected (soft-delete, not permanent)
* `verify_patches()` checks sentinel (was always returning `True`)
* Bare `except:` replaced with explicit exception types
* Portuguese comments translated to English
* `datetime.utcnow()` replaced with `datetime.now(timezone.utc)`
* `InMemoryRateLimiter` prunes empty entries to prevent memory leak

### Testing

* 258 unit + integration tests across 14 test files
* Multi-pod integration tests (session + CSRF portability)
* `operationName` and fragment traversal tests for GraphQL analyzer
* Security regression tests (empty password, XSS escape, open redirect, RBAC default-deny)

### Configuration Changes

**New Environment Variables:**
```bash
DAGSTER_AUTH_UNKNOWN_MUTATION_ROLE   # Role for unrecognized mutations (default: ADMIN)
DAGSTER_AUTH_REST_WRITE_ROLE         # Minimum role for REST write requests (default: EDITOR)
DAGSTER_AUTH_PROXY_TRUSTED_IPS       # Comma-separated proxy IPs (REQUIRED in proxy mode)
DAGSTER_AUTH_PROXY_TRUST_ALL         # Opt-in to proxy mode without IP allowlist (default: false)
```

### Breaking Changes

* **`SECRET_KEY` is now required in production.** Server refuses to start without it.
* **Proxy mode requires `DAGSTER_AUTH_PROXY_TRUSTED_IPS`** or explicit `TRUST_ALL=true`.
* **`AuthUser.to_dict()` now serializes role as int** (`40`) instead of string (`"ADMIN"`). `from_dict()` handles both formats (backward-compatible).
* **Database migration** — `session_version` column added to `users` table. Automatic on boot; manual fallback documented.
* **Default RBAC posture changed** — Unknown mutations now require `ADMIN` instead of being open.
* **`SESSION_COOKIE_SECURE` now defaults to `true`** (was `false`).

---

## [0.3.0] - 2026-02-14

### Major Changes

**Proxy Authentication Mode (Stable)**

* Added `ProxyAuthBackend` for delegating authentication to external reverse proxies (Authelia, Traefik, Caddy, oauth2-proxy)
* User identity extracted from HTTP headers (`Remote-User`, `Remote-Groups`, `Remote-Email`, `Remote-Name`)
* Configurable group-to-role mapping via `DAGSTER_AUTH_PROXY_GROUP_PATTERN`
* Logout endpoint now redirects to external provider logout URL in proxy mode
* Smart group header parser handles JSON arrays, LDAP DNs, CSV, and mixed delimiters

**Kubernetes Deployment (Examples)**

* Complete Minikube example with full SSO stack:
  * OpenLDAP with pre-seeded users and RBAC groups
  * Authelia configured with LDAP backend
  * Caddy as reverse proxy with TLS termination and forward auth
  * Dagster-AuthKit in proxy mode
* Comprehensive Makefile with build, deploy, connect, and monitoring targets
* Critical Kubernetes fixes documented:
  * `enableServiceLinks: false` to prevent deprecated env vars
  * Separate `/data` volume with `emptyDir` for writable storage
  * LoadBalancer service for proper HTTPS exposure
  * Sequential LDIF imports via ConfigMap with numbered files

**Authelia + Caddy Example (Docker)**

* Complete SSO integration with Authelia, Caddy, and OpenLDAP
* Caddy configured with `forward_auth` and header injection
* Test users with password123 mapped to RBAC roles (admin, editor, launcher, viewer)
* Optional `users_database.yml` for testing without LDAP

### Enhancements

**GraphQL Analysis**

* Replaced fragile regex parser with official `graphql-core` AST parser
* Added `GraphQLMutationAnalyzer` for accurate mutation detection
* Handles aliases, multiple mutations, and complex queries properly
* Added `list-permissions` CLI command to display RBAC matrix

**Redis Operations**

* Atomic `expire` with `nx=True` in rate limiter (sets TTL only on first increment)
* Fixed session revocation: properly clean user token sets before deletion
* Added Redis URL format validation in config

**Code Organization**

* Centralized all UI templates (HTML/CSS/JS) in `utils/templates.py`
* Removed 600+ lines of inline strings from routes and patch modules
* Cleaner separation between logic and presentation

**Observability**

* Added RBAC decision tracking via `track_rbac_decision()`
* Metrics now count allowed/denied mutations per role and action
* Better error logging with query truncation for debugging

### Documentation & Examples

* New `examples/authelia/` - Complete Authelia + Caddy + LDAP stack
* New `examples/kubernetes/` - Same stack running on Minikube
* Updated `examples/ldap/` with better OpenLDAP configuration
* Added `list-permissions` to CLI documentation
* Clearer backend matrix with proxy mode status

### Bug Fixes

* **GraphQL:** Replaced generic `unknown_mutation` with explicit `__UNPARSEABLE_QUERY__` sentinel
* **Middleware:** Fixed incorrect header extraction in proxy mode
* **Session:** Redis session revocation now properly removes user token mappings
* **Rate Limiter:** TTL now set correctly only on first attempt

### Configuration Changes

**New Environment Variables:**
```bash
# Proxy Mode
DAGSTER_AUTH_PROXY_USER_HEADER       # Header for username (default: Remote-User)
DAGSTER_AUTH_PROXY_GROUPS_HEADER     # Header for groups (default: Remote-Groups)
DAGSTER_AUTH_PROXY_EMAIL_HEADER      # Header for email (default: Remote-Email)
DAGSTER_AUTH_PROXY_NAME_HEADER       # Header for display name (default: Remote-Name)
DAGSTER_AUTH_PROXY_GROUP_PATTERN     # Pattern for LDAP group mapping
DAGSTER_AUTH_PROXY_LOGOUT_URL        # External logout URL for proxy mode
```

### Breaking Changes

* **GraphQL Error Format:** Unparseable queries now return `__UNPARSEABLE_QUERY__` instead of generic fallback
* **Redis Session Format:** Session data structure updated; existing Redis sessions will be invalidated on upgrade

---

## [0.2.0] - 2026-01-28

### Major Changes

**Multi-Backend Support (SQL & Redis)**

* Added **Peewee ORM** support, enabling connection to **PostgreSQL**, **MySQL**, and **MariaDB**.
* Added **Redis** backend for production-grade session storage (fixes the issue of logouts on server restart).
* Introduced `DAGSTER_AUTH_DB_CONNECTION_URL` for flexible database configuration.

**LDAP Integration (Experimental)**

* Added `ldap3` based backend for Active Directory/LDAP integration.
* *Note: Marked as Experimental/Alpha pending community validation.*

**Refined RBAC (4 Levels)**

* **New Role:** Added `LAUNCHER` role.
* **Updated Hierarchy:**
1. **Admin:** Full control.
2. **Editor:** Can edit code/assets and manage runs.
3. **Launcher:** Can launch/retry runs but cannot modify code/assets (New).
4. **Viewer:** Read-only access (GraphQL mutations blocked).



### Enhancements

**Health & Observability**

* **Fixed:** `/auth/health` and `/auth/metrics` endpoints were previously returning 404 due to middleware misconfiguration. They are now intercepted correctly.
* Health checks now return status for the specific backend in use (SQL, Redis, or LDAP).

**Developer Experience**

* Added `examples/` directory with ready-to-use Docker Compose stacks:
* `quickstart-sqlite`: Zero config.
* `postgresql_redis`: Production reference architecture.
* `ldap`: Local OpenLDAP testing setup.


* Added `Makefile` in example directories for easy startup (`make up`).

### Bug Fixes

* **Middleware Dispatch:** Fixed a critical bug where `call_next` was invoked for internal endpoints (`/auth/health`), causing Dagster to return 404.
* **Dependency Management:** Clarified optional dependencies in `pyproject.toml` (install via `[postgresql]`, `[redis]`, etc).

### Breaking Changes

* **Project Status:** Downgraded status label from "General Availability" to **BETA**. Use in production at your own risk.
* **RBAC Logic:** Existing users in database might need role migration if custom roles were manually hacked (standard roles map automatically).

---

## [0.1.0] - 2026-01-25

### Initial Release

First working version of dagster-authkit - community authentication for Dagster OSS.

### Features

**Authentication System**

- SQLite-based authentication backend with bcrypt password hashing
- Login/logout pages with clean UI
- Session management using cryptographically signed cookies (itsdangerous)
- Rate limiting for brute-force protection (5 attempts per 5 minutes)
- Automatic session expiration (24h default, configurable)

**Role-Based Access Control (RBAC)**

- Three roles: admin, editor, viewer
- GraphQL mutation detection and blocking for non-editors
- Proper error responses that stop UI loading states
- Viewer role can see everything but cannot modify (read-only)

**User Management CLI**

- `dagster-authkit init-db` - Initialize database with optional admin user
- `dagster-authkit add-user` - Add users with roles
- `dagster-authkit list-users` - List all users
- `dagster-authkit change-password` - Change user passwords
- `dagster-authkit delete-user` - Soft-delete users

**Audit Logging**

- Structured JSON audit logs to stdout
- Tracks: login attempts, logout, access control decisions, password changes, user management
- Ready for log aggregation systems (Datadog, Splunk, CloudWatch, ELK)

**Security Features**

- Bcrypt password hashing with SHA-256 pre-hash (prevents BCrypt 72-byte limit issues)
- Constant-time password comparison (timing attack prevention)
- Security headers: X-Frame-Options, CSP, X-Content-Type-Options
- Open redirect protection
- Username sanitization
- CSRF token generation (foundation for future CSRF protection)

**Monkey-Patching System**

- Dagster API compatibility detection layer
- Non-invasive middleware injection (first layer in ASGI stack)
- Route injection for /auth/* endpoints
- UI injection - user menu in Dagster sidebar with username, role, and logout

**Health & Monitoring**

- `/auth/health` - Unified health check endpoint
- `/auth/health?type=live` - Kubernetes liveness probe
- `/auth/health?type=ready` - Kubernetes readiness probe
- `/auth/metrics` - Basic metrics (login attempts, uptime, etc.)

**Docker/Kubernetes Support**

- Admin user bootstrap via environment variables
- `DAGSTER_AUTH_ADMIN_USER`, `DAGSTER_AUTH_ADMIN_PASSWORD` for IaC deployments
- Automatic database initialization on first run

### Architecture

**Modular Structure**

- `dagster_authkit/core/` - Core patching and middleware
- `dagster_authkit/auth/` - Authentication backends and security
- `dagster_authkit/api/` - Routes and health checks
- `dagster_authkit/cli/` - User management CLI
- `dagster_authkit/utils/` - Config, audit, logging

**Plugin System**

- Backend discovery via setuptools entry points
- Easy to add custom backends without modifying core code
- Dummy backend for development (admin/admin, editor/editor, viewer/viewer)

### Dependencies

**Core**

- `dagster>=1.10.0,<2.0.0`
- `dagster-webserver>=1.10.0,<2.0.0`
- `starlette>=0.27.0`
- `itsdangerous>=2.1.0`
- `python-multipart>=0.0.6`

**Optional**

- `bcrypt>=4.0.0` - For SQLite backend

### Known Issues

- **Monkey-patching fragility** - May break across Dagster versions (tested on 1.10-1.12)
- **In-memory rate limiting** - Does not work across multiple instances (use Redis for distributed)
- **GraphQL mutation detection** - Regex-based, may have edge cases
- **No fine-grained permissions** - Only 3 roles (admin/editor/viewer)
- **LDAP backend** - Stub only, not implemented
- **OAuth backend** - Stub only, not implemented

### Documentation

- README.md with quick start guide
- Inline code documentation (docstrings)
- CLI help messages (`dagster-authkit --help`)

### Configuration

All configuration via environment variables:

- Session management (SECRET_KEY, SESSION_MAX_AGE, cookie settings)
- Backend selection (AUTH_BACKEND)
- Rate limiting (RATE_LIMIT_*, configurable attempts/window)
- Audit logging (AUDIT_LOG_ENABLED)
- Admin bootstrap (ADMIN_USER, ADMIN_PASSWORD)

### Breaking Changes

N/A - Initial release

---

## [Unreleased]

### Planned Features

- Helm chart for Kubernetes deployments
- OIDC backend (native, beyond proxy mode)
- Fine-grained asset-level RBAC
