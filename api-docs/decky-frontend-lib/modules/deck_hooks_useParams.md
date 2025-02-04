[decky-frontend-lib](../README.md) / [Modules](../modules.md) / deck-hooks/useParams

# Module: deck-hooks/useParams

## Table of contents

### Functions

- [useParams](deck_hooks_useParams.md#useparams)

## Functions

### useParams

▸ **useParams**<`T`\>(): `T`

Get the current params from ReactRouter

**`Example`**

```ts
import { useParams } from "decky-frontend-lib";

const { appid } = useParams<{ appid: string }>()
```

#### Type parameters

| Name |
| :------ |
| `T` |

#### Returns

`T`

an object with the current ReactRouter params

#### Defined in

[src/deck-hooks/useParams.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-hooks/useParams.ts#L15)
