# @blitzjs/rpc

## 2.0.0-beta.23

### Patch Changes

- c3c789740: Updates internal functions and tests to support blitz apps that run tests with vitest
- Updated dependencies [c3c789740]
  - blitz@2.0.0-beta.23

## 2.0.0-beta.22

### Minor Changes

- 270361886: change rpc route basepath to be one folder higher when using includeRPC in monorepos

### Patch Changes

- Updated dependencies [989691ec8]
- Updated dependencies [8aa22a0b2]
  - blitz@2.0.0-beta.22

## 2.0.0-beta.21

### Patch Changes

- d692b4c1d: Fix suspense error codegen patch for nextjs versions 13-13.0.6
- 0025856b9: Support full api of tanstack invalidateQueries
- Updated dependencies [d692b4c1d]
- Updated dependencies [10f98c681]
- Updated dependencies [d5b8faa86]
  - blitz@2.0.0-beta.21

## 2.0.0-beta.20

### Minor Changes

- 6ece0961: Decoupled Blitz RPC from Blitz Auth to allow independent use.
- 03bad317: fix Cannot read properties of null (reading 'isReady') for pnpm/yarn v3

### Patch Changes

- 8c247e26: Switch from jest to vitest in new app templates
- 650a157e: fix: allow `GET` requests without `params` and `meta` keys
- Updated dependencies [74a14b70]
- Updated dependencies [6ece0961]
- Updated dependencies [a0596279]
  - blitz@2.0.0-beta.20

## 2.0.0-beta.19

### Minor Changes

- c1e00406: transpile packages to es2015 to support older browsers
- b493c93f: fix resolverPath:root and make it work with monorepo resolvers

### Patch Changes

- b33db082: Fix ambigious class warning log & upgrade superjson from 1.9.1 to 1.11.0
- Updated dependencies [c1e00406]
  - @blitzjs/auth@2.0.0-beta.19

## 2.0.0-beta.18

### Minor Changes

- 72a4e594: internal: remove unneeed useSession from useQuery hooks
- c0a3b1ee: Fix mutability bug in RPC configuration

### Patch Changes

- ed2b0e22: Add ability to put your query and mutation resolvers in a separate monorepo folder, allowing you to use them in multiple apps.
  - @blitzjs/auth@2.0.0-beta.18

## 2.0.0-beta.17

### Patch Changes

- 8b4bf999: Update dependencies
- Updated dependencies [8b4bf999]
- Updated dependencies [97469a12]
  - @blitzjs/auth@2.0.0-beta.17

## 2.0.0-beta.16

### Minor Changes

- 55a43ce1: maybe fix anon session CSRF issue + add ability to customize anon session expiry time

### Patch Changes

- ceb7db27: Add an opt-in GET request support to RPC specification by exporting a `config` object that has the `httpMethod` property.
  from `query` files.
- Updated dependencies [55a43ce1]
  - @blitzjs/auth@2.0.0-beta.16

## 2.0.0-beta.15

### Patch Changes

- @blitzjs/auth@2.0.0-beta.15

## 2.0.0-beta.14

### Patch Changes

- @blitzjs/auth@2.0.0-beta.14

## 2.0.0-beta.13

### Patch Changes

- 7b63f0f1: Allow the updater function in setQueryData to return undefined to match react-query typings
  - @blitzjs/auth@2.0.0-beta.13

## 2.0.0-beta.12

### Patch Changes

- @blitzjs/auth@2.0.0-beta.12

## 2.0.0-beta.11

### Patch Changes

- 1476a577: Fix release
- Updated dependencies [1476a577]
  - @blitzjs/auth@2.0.0-beta.11

## 2.0.0-beta.10

### Patch Changes

- 0edeaa37: Allow for custom page extensions for the wildcard blitz route. For example [...blitz].api.ts. For more information vist https://nextjs.org/docs/api-reference/next.config.js/custom-page-extensions
- aa34661f: Fix invalidateQuery generating wrong param when no param argument is passed
- 8e0c9d76: Migrate over recipe functionality from legacy framework & expose recipe builder helper functions that find and modify next.config.js, blitz-server & blitz-client.
- Updated dependencies [9fe0cc54]
  - @blitzjs/auth@2.0.0-beta.10

## 2.0.0-beta.4

### Patch Changes

- c213d521: Fix issue with the route name that's generated for nested routes in @blitzjs/rpc. This was causing issues for windows users.
- 0b94a450: Upgrade superjson to the latest version
- f6dac093: Improve RPC logging: print `resolverName()` insetad of `/resolverName()`
- Updated dependencies [713aead9]
  - @blitzjs/auth@2.0.0-beta.4

## 2.0.0-beta.3

### Patch Changes

- @blitzjs/auth@2.0.0-beta.3

## 2.0.0-beta.2

### Patch Changes

- db7233db: Bump react, react-dom, @types/react and next versions

  This fixes a console warning: `Warning: Received`true`for a non-boolean attribute`global`.` when using `styled-jsx`. Versions bump also fixes React Hydration error that happens on and off when using `redirectAuthenticatedTo`.

- Updated dependencies [db7233db]
  - @blitzjs/auth@2.0.0-beta.2

## 2.0.0-beta.1

### Patch Changes

- 0f4926fd: Set current Blitz tag to latest
- Updated dependencies [0f4926fd]
  - @blitzjs/auth@2.0.0-beta.1

## 2.0.0-beta.72

### Patch Changes

- 2cc888ef: Beta release
- Updated dependencies [2cc888ef]
  - @blitzjs/auth@2.0.0-beta.72

## 2.0.0-alpha.71

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.71

## 2.0.0-alpha.70

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.70

## 2.0.0-alpha.69

### Patch Changes

- 49028024: Add `getQueryData` utility to get an existing query's cached data
  - @blitzjs/auth@2.0.0-alpha.69

## 2.0.0-alpha.68

### Patch Changes

- 630c7181: Use internal branded blitz logger for @blitzjs/rpc
  - @blitzjs/auth@2.0.0-alpha.68

## 2.0.0-alpha.67

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.67

## 2.0.0-alpha.66

### Patch Changes

- 807a2b56: Fixes peer dependency warnings
- a3e6c49c: Fixes the supports-color warning for pnpm
- 9620ef6b: moves zod to devDependencies
- Updated dependencies [a3e6c49c]
  - @blitzjs/auth@2.0.0-alpha.66

## 2.0.0-alpha.65

### Patch Changes

- Updated dependencies [dd5f5174]
  - blitz@2.0.0-alpha.65
  - @blitzjs/auth@2.0.0-alpha.65

## 2.0.0-alpha.64

### Patch Changes

- Updated dependencies [54db8a46]
- Updated dependencies [62bf12b5]
  - blitz@2.0.0-alpha.64
  - @blitzjs/auth@2.0.0-alpha.64

## 2.0.0-alpha.63

### Patch Changes

- f52ca398: Upgrade react-query to v4
  - @blitzjs/auth@2.0.0-alpha.63
  - blitz@2.0.0-alpha.63

## 2.0.0-alpha.62

### Patch Changes

- Updated dependencies [365e6709]
  - blitz@2.0.0-alpha.62
  - @blitzjs/auth@2.0.0-alpha.62

## 2.0.0-alpha.61

### Patch Changes

- Updated dependencies [240f378b]
  - blitz@2.0.0-alpha.61
  - @blitzjs/auth@2.0.0-alpha.61

## 2.0.0-alpha.60

### Patch Changes

- Updated dependencies [1d863f35]
  - blitz@2.0.0-alpha.60
  - @blitzjs/auth@2.0.0-alpha.60

## 2.0.0-alpha.59

### Patch Changes

- 3b213a35: Remove debug console.log
  - @blitzjs/auth@2.0.0-alpha.59
  - blitz@2.0.0-alpha.59

## 2.0.0-alpha.58

### Patch Changes

- c721c104: Pass `signal` from useQuery to Blitz internal rpc client to be able to cancel queries on unmount
- Updated dependencies [83b35590]
  - blitz@2.0.0-alpha.58
  - @blitzjs/auth@2.0.0-alpha.58

## 2.0.0-alpha.57

### Patch Changes

- 716e188d: Fix queries/mutations lookup on Windows
- Updated dependencies [3511d5b6]
  - blitz@2.0.0-alpha.57
  - @blitzjs/auth@2.0.0-alpha.57

## 2.0.0-alpha.56

### Patch Changes

- Updated dependencies [3f20a474]
- Updated dependencies [abb1ad5d]
- Updated dependencies [abe2afcc]
- Updated dependencies [0ac6e171]
- Updated dependencies [8bcb471a]
  - @blitzjs/auth@2.0.0-alpha.56
  - blitz@2.0.0-alpha.56

## 2.0.0-alpha.55

### Patch Changes

- df7cee84: Fix pipe resolver return type
- Updated dependencies [8f166a5d]
- Updated dependencies [54a66a95]
- Updated dependencies [1c809094]
  - blitz@2.0.0-alpha.55
  - @blitzjs/auth@2.0.0-alpha.55

## 2.0.0-alpha.54

### Patch Changes

- 20fc9f80: Fix SSP / SP not prefetching queries correctly
- Updated dependencies [f397cc20]
- Updated dependencies [cacb65d6]
- Updated dependencies [348fd6f5]
- Updated dependencies [20fc9f80]
- Updated dependencies [a3bbe6ce]
- Updated dependencies [ffa7b5cc]
  - blitz@2.0.0-alpha.54
  - @blitzjs/auth@2.0.0-alpha.54

## 2.0.0-alpha.53

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.53
- blitz@2.0.0-alpha.53

## 2.0.0-alpha.52

### Patch Changes

- blitz@2.0.0-alpha.52
- @blitzjs/auth@2.0.0-alpha.52

## 2.0.0-alpha.51

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.51
- blitz@2.0.0-alpha.51

## 2.0.0-alpha.50

### Patch Changes

- c11f0401: Update Next.js version and addBasePath location
  - blitz@2.0.0-alpha.50
  - @blitzjs/auth@2.0.0-alpha.50

## 2.0.0-alpha.49

### Patch Changes

- bec9512e: Allow resolverPath to be a function which is ran for every file path that is converted to RPC Route
  - @blitzjs/auth@2.0.0-alpha.49
  - blitz@2.0.0-alpha.49

## 2.0.0-alpha.48

### Patch Changes

- Updated dependencies [93851d90]
  - blitz@2.0.0-alpha.48
  - @blitzjs/auth@2.0.0-alpha.48

## 2.0.0-alpha.47

### Patch Changes

- 1d9804a6: Remove references to the logging package
- Updated dependencies [1d9804a6]
  - blitz@2.0.0-alpha.47
  - @blitzjs/auth@2.0.0-alpha.47

## 2.0.0-alpha.46

### Patch Changes

- bee19a25: Support RPC error middleware
  - @blitzjs/auth@2.0.0-alpha.46
  - blitz@2.0.0-alpha.46

## 2.0.0-alpha.45

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.45
- blitz@2.0.0-alpha.45

## 2.0.0-alpha.44

### Patch Changes

- Updated dependencies [7817fe3a]
  - @blitzjs/auth@2.0.0-alpha.44
  - blitz@2.0.0-alpha.44

## 2.0.0-alpha.43

### Patch Changes

- Updated dependencies [527e48ac]
  - blitz@2.0.0-alpha.43
  - @blitzjs/auth@2.0.0-alpha.43

## 2.0.0-alpha.42

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.42
- blitz@2.0.0-alpha.42

## 2.0.0-alpha.41

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.41
- blitz@2.0.0-alpha.41

## 2.0.0-alpha.40

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.40
- blitz@2.0.0-alpha.40

## 2.0.0-alpha.39

### Patch Changes

- Updated dependencies [b918055b]
  - blitz@2.0.0-alpha.39
  - @blitzjs/auth@2.0.0-alpha.39

## 2.0.0-alpha.38

### Patch Changes

- 8aee25c5: getQueryClient function & queryClient codemod updates & shared plugin config
  - blitz@2.0.0-alpha.38
  - @blitzjs/auth@2.0.0-alpha.38

## 2.0.0-alpha.37

### Patch Changes

- Updated dependencies [a80d2a8f]
  - blitz@2.0.0-alpha.37
  - @blitzjs/auth@2.0.0-alpha.37

## 2.0.0-alpha.36

### Patch Changes

- 4cad9cca: Add queryClient to RPC Plugin exports
  - blitz@2.0.0-alpha.36
  - @blitzjs/auth@2.0.0-alpha.36

## 2.0.0-alpha.35

### Patch Changes

- blitz@2.0.0-alpha.35
- @blitzjs/auth@2.0.0-alpha.35

## 2.0.0-alpha.34

### Patch Changes

- dfd2408e: Add resolverBasePath to Blitz config to change the way rpc routes are generated
  - @blitzjs/auth@2.0.0-alpha.34
  - blitz@2.0.0-alpha.34

## 2.0.0-alpha.33

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.33
- blitz@2.0.0-alpha.33

## 2.0.0-alpha.32

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.32
- blitz@2.0.0-alpha.32

## 2.0.0-alpha.31

### Patch Changes

- 17ce29e5: Update RPC plugin setup in templates
  - blitz@2.0.0-alpha.31
  - @blitzjs/auth@2.0.0-alpha.31

## 2.0.0-alpha.30

### Patch Changes

- Updated dependencies [ce453683]
  - blitz@2.0.0-alpha.30
  - @blitzjs/auth@2.0.0-alpha.30

## 2.0.0-alpha.29

### Patch Changes

- Updated dependencies [962eb58a]
  - blitz@2.0.0-alpha.29
  - @blitzjs/auth@2.0.0-alpha.29

## 2.0.0-alpha.28

### Patch Changes

- blitz@2.0.0-alpha.28
- @blitzjs/auth@2.0.0-alpha.28

## 2.0.0-alpha.27

### Patch Changes

- 07292910: Add invokeWithCtx function
  - @blitzjs/auth@2.0.0-alpha.27
  - blitz@2.0.0-alpha.27

## 2.0.0-alpha.26

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.26
- blitz@2.0.0-alpha.26

## 2.0.0-alpha.25

### Patch Changes

- Updated dependencies [1436e761]
- Updated dependencies [1436e761]
  - blitz@2.0.0-alpha.25
  - @blitzjs/auth@2.0.0-alpha.25

## 2.0.0-alpha.24

### Patch Changes

- Updated dependencies [8490b072]
  - blitz@2.0.0-alpha.24
  - @blitzjs/auth@2.0.0-alpha.24

## 2.0.0-alpha.23

### Patch Changes

- Updated dependencies
  - blitz@2.0.0-alpha.23
  - @blitzjs/auth@2.0.0-alpha.23

## 2.0.0-alpha.22

### Patch Changes

- Updated dependencies
- Updated dependencies [89bf993a]
  - blitz@2.0.0-alpha.22
  - @blitzjs/auth@2.0.0-alpha.22

## 2.0.0-alpha.21

### Patch Changes

- blitz@2.0.0-alpha.21
- @blitzjs/auth@2.0.0-alpha.21

## 2.0.0-alpha.20

### Patch Changes

- testing set dist-tag
- Updated dependencies
  - blitz@2.0.0-alpha.20
  - @blitzjs/auth@2.0.0-alpha.20

## 2.0.0-alpha.19

### Patch Changes

- blitz@2.0.0-alpha.19
- @blitzjs/auth@2.0.0-alpha.19

## 2.0.0-alpha.18

### Patch Changes

- Updated dependencies
  - blitz@2.0.0-alpha.18
  - @blitzjs/auth@2.0.0-alpha.18

## 2.0.0-alpha.17

### Patch Changes

- blitz@2.0.0-alpha.17
- @blitzjs/auth@2.0.0-alpha.17

## 2.0.0-alpha.16

### Patch Changes

- Updated dependencies
  - blitz@2.0.0-alpha.16
  - @blitzjs/auth@2.0.0-alpha.16

## 2.0.0-alpha.15

### Patch Changes

- blitz@2.0.0-alpha.15
- @blitzjs/auth@2.0.0-alpha.15

## 2.0.0-alpha.14

### Patch Changes

- Updated dependencies
  - blitz@2.0.0-alpha.14
  - @blitzjs/auth@2.0.0-alpha.14

## 2.0.0-alpha.13

### Patch Changes

- Updated dependencies
  - blitz@2.0.0-alpha.13
  - @blitzjs/auth@2.0.0-alpha.13

## 2.0.0-alpha.12

### Patch Changes

- Updated dependencies
  - blitz@2.0.0-alpha.12
  - @blitzjs/auth@2.0.0-alpha.12

## 2.0.0-alpha.11

### Patch Changes

- @blitzjs/auth@2.0.0-alpha.11
- blitz@2.0.0-alpha.11

## 2.0.0-alpha.10

### Patch Changes

- blitz@2.0.0-alpha.10
- @blitzjs/auth@2.0.0-alpha.10

## 2.0.0-alpha.9

### Patch Changes

- Updated dependencies
  - blitz@2.0.0-alpha.9
  - @blitzjs/auth@2.0.0-alpha.9

## 2.0.0-alpha.8

### Patch Changes

- Updated dependencies
  - blitz@2.0.0-alpha.8
  - @blitzjs/auth@2.0.0-alpha.8

## 2.0.0-alpha.7

### Patch Changes

- Updated dependencies
  - blitz@2.0.0-alpha.7
  - @blitzjs/auth@2.0.0-alpha.7

## 2.0.0-alpha.6

### Patch Changes

- fix route manifest codegen
- Updated dependencies
  - blitz@2.0.0-alpha.6
  - @blitzjs/auth@2.0.0-alpha.6

## 2.0.0-alpha.5

### Patch Changes

- new app template
- Updated dependencies
  - blitz@2.0.0-alpha.5
  - @blitzjs/auth@2.0.0-alpha.5

## 2.0.0-alpha.4

### Patch Changes

- Updated dependencies
  - blitz@2.0.0-alpha.4
  - @blitzjs/auth@2.0.0-alpha.4

## 2.0.0-alpha.3

### Patch Changes

- Updated dependencies
  - blitz@2.0.0-alpha.3
  - @blitzjs/auth@2.0.0-alpha.3

## 2.0.0-alpha.2

### Patch Changes

- blitz@2.0.0-alpha.2
- @blitzjs/auth@2.0.0-alpha.2

## 2.0.0-alpha.1

### Patch Changes

- 46a34c7b: initial publish
- Updated dependencies [46a34c7b]
  - blitz@2.0.0-alpha.1
  - @blitzjs/auth@2.0.0-alpha.1
