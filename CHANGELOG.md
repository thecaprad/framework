# Changelog


## [main](https://github.com/nuxt/framework/compare/v3.0.0-rc.9...main)


### 🚀 Enhancements

  - **nuxt, vite:** Inline global and component styles in server response ([#7160](https://github.com/nuxt/framework/pull/7160))
  - **nuxt:** Custom `history` and `routes` for `app/router.options.ts` ([#7129](https://github.com/nuxt/framework/pull/7129))
  - **nuxt:** Router with hash mode ([#6980](https://github.com/nuxt/framework/pull/6980))
  - **nuxt:** Allow extending routes with custom alias ([#7074](https://github.com/nuxt/framework/pull/7074))
  - **test-utils:** Add `mockFn` and `mockLogger` utils ([#6235](https://github.com/nuxt/framework/pull/6235))
  - **nuxt:** Support experimental flag to render no client-side js ([#7248](https://github.com/nuxt/framework/pull/7248))
  - **kit:** Add `addImportsSources` utility ([#7270](https://github.com/nuxt/framework/pull/7270))
  - **nuxt:** Add `immediate` option for `useAsyncData` and `useFetch` ([#5500](https://github.com/nuxt/framework/pull/5500))
  - **nuxt:** Add `clearNuxtData` ([#5227](https://github.com/nuxt/framework/pull/5227))
  - Allow client-side sourcemaps in production ([#7313](https://github.com/nuxt/framework/pull/7313))
  - **nuxt:** Filter support for `clearNuxtData` ([#7323](https://github.com/nuxt/framework/pull/7323))
  - **cli:** Switch to `unjs/giget` for `nuxi init` ([#7361](https://github.com/nuxt/framework/pull/7361))

### 🔥 Performance

  - **nuxt:** Cache `createClientOnly` wrapper using weakmap ([#7297](https://github.com/nuxt/framework/pull/7297))
  - **vite:** Remove duplicate css links from rendered page when inlined ([#7264](https://github.com/nuxt/framework/pull/7264))

### 🩹 Fixes

  - **nuxt:** Update default redirect code of `navigateTo` to `302 Found` ([#7189](https://github.com/nuxt/framework/pull/7189))
  - **head:** Case `http-equiv` correctly ([#7190](https://github.com/nuxt/framework/pull/7190))
  - **kit, nuxi:** Semver regexp to support `nuxt-edge` current releases (bridge) ([#7193](https://github.com/nuxt/framework/pull/7193))
  - **vite:** Use baseURL + assetsDir as base in dev mode ([#7234](https://github.com/nuxt/framework/pull/7234))
  - **vite:** Pass ssr condition to `getModuleByUrl` ([#7260](https://github.com/nuxt/framework/pull/7260))
  - **nuxt:** Import and wrap client-only components once ([#7245](https://github.com/nuxt/framework/pull/7245))
  - **cli:** Pass value of `https` through to vite-node ([#7271](https://github.com/nuxt/framework/pull/7271))
  - **nuxt:** Don't override payload error if it is present ([#7290](https://github.com/nuxt/framework/pull/7290))
  - **nuxt:** Don't try to set cookie after redirect ([#7288](https://github.com/nuxt/framework/pull/7288))
  - **webpack:** Promisify webpack dev/hot handlers using `h3.promisifyHandler` ([#7275](https://github.com/nuxt/framework/pull/7275))
  - **schema:** Disallow setting vite server properties ([#7317](https://github.com/nuxt/framework/pull/7317))
  - **schema:** Mark vite server as optional ([#7327](https://github.com/nuxt/framework/pull/7327))
  - **nuxt:** Allow `abortMiddleware` to receive a nuxt error or error options ([#7335](https://github.com/nuxt/framework/pull/7335))
  - **webpack:** Don't parse styles for composable keys ([#7333](https://github.com/nuxt/framework/pull/7333))
  - **vite:** Allow overriding vite sourcemap ([#7342](https://github.com/nuxt/framework/pull/7342))
  - **schema:** Resolve `ssr` ([#7359](https://github.com/nuxt/framework/pull/7359))
  - **kit:** Add default config layer without `nuxt.config` file ([#7358](https://github.com/nuxt/framework/pull/7358))
  - **vite:** Update render if it is invalidated ([#7347](https://github.com/nuxt/framework/pull/7347))

### 💅 Refactors

  - **vite:** Reuse resolved server entry from context ([#7268](https://github.com/nuxt/framework/pull/7268))

### 📖 Documentation

  - Add note about `useFetch` auto generated key ([#7044](https://github.com/nuxt/framework/pull/7044))
  - **api:** Enhance `useHead` composable ([#7072](https://github.com/nuxt/framework/pull/7072))
  - Add note about fetching data on initial load ([#7120](https://github.com/nuxt/framework/pull/7120))
  - Document `external` option of `navigateTo` ([#7188](https://github.com/nuxt/framework/pull/7188))
  - **guide:** Add `.client` and `.server` components ([#7084](https://github.com/nuxt/framework/pull/7084))
  - Fix markdown file name ([#7231](https://github.com/nuxt/framework/pull/7231))
  - **api:** Navigate to first item in list ([#7232](https://github.com/nuxt/framework/pull/7232))
  - Extend description of server handlers ([#7187](https://github.com/nuxt/framework/pull/7187))
  - **api:** Add example for fetch interceptors ([#7180](https://github.com/nuxt/framework/pull/7180))
  - **deploy:** Add node cluster mode ([#7089](https://github.com/nuxt/framework/pull/7089))
  - **api:** Fix `useAsyncData` signature ([#7242](https://github.com/nuxt/framework/pull/7242))
  - Add `app-config` example ([#7247](https://github.com/nuxt/framework/pull/7247))
  - Fix typo ([#7262](https://github.com/nuxt/framework/pull/7262))
  - Fix typo in url ([#7272](https://github.com/nuxt/framework/pull/7272))
  - Rename `AppConfig` to `AppConfigInput` ([#7293](https://github.com/nuxt/framework/pull/7293))
  - **api:** Fix typo in use-fetch ([#7310](https://github.com/nuxt/framework/pull/7310))
  - **api:** Add `nuxi prepare` command ([#7349](https://github.com/nuxt/framework/pull/7349))
  - **head:** Enhance usehead and fix broken links ([#7364](https://github.com/nuxt/framework/pull/7364))

### 🏡 Chore

  - Lint ([#7213](https://github.com/nuxt/framework/pull/7213))
  - Fix docs lint issue ([94a992ec9](https://github.com/nuxt/framework/commit/94a992ec9))
  - Use latest nuxt and `@nuxt/ui` for examples ([a329b28dd](https://github.com/nuxt/framework/commit/a329b28dd))
  - Maintain lockfile ([33d915871](https://github.com/nuxt/framework/commit/33d915871))
  - **docs:** Fix link to vue router api ([#7289](https://github.com/nuxt/framework/pull/7289))
  - Update CodeSandbox links ([#7318](https://github.com/nuxt/framework/pull/7318))

### 📦 Build

  - **cli:** Add `node` to export conditions ([0cc49e2a2](https://github.com/nuxt/framework/commit/0cc49e2a2))

### ✅ Tests

  - Use semantic `runIf` and `skipIf` helpers ([#7312](https://github.com/nuxt/framework/pull/7312))
  - Fix dynamic dev paths ([#7314](https://github.com/nuxt/framework/pull/7314))

### ❤️  Contributors

- Adewale Abati
- Alex Kozack
- Alexander Lichter
- AndreyYolkin
- Anthony Fu
- Damian Głowala
- Daniel Roe
- Harlan Wilton
- HomWang
- Julien Huang
- Krutie Patel
- Kévin Schnekenburger
- Leon Si
- Mastercuber
- Pooya Parsa
- Ricardo Gobbo De Souza
- Sébastien Chopin
- Tobias Diez
- Tobias SN
- Vasily Stepanov
- Victorkwok97
- Vl4dimyr

