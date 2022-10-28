
a package to make the [rush build-cache](https://rushjs.io/pages/maintainer/build_cache/) work quickly.

first ensure you have setup something like [this](https://rushjs.io/pages/maintainer/build_cache/#enabling-the-local-disk-cache) the follow the steps below.


## Install

moste likely just:
```bash
rush add -m --dev -p nest-rushstack-rig
```

**you schouldn't do one of those**
```
pnpm install nest-rushstack-rig
npm install nest-rushstack-rig
yarn add nest-rushstack-rig
```

## Ussage


`<project-root>/config/rig.json`
```json
{
    "$schema": "https://developer.microsoft.com/json-schemas/rig-package/rig.schema.json",
    "rigPackageName": "nest-rushstack-rig"
}
```