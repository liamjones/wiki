[decky-frontend-lib](../README.md) / [Modules](../modules.md) / utils/patcher

# Module: utils/patcher

## Table of contents

### Modules

- [&lt;internal\&gt;](utils_patcher._internal_.md)

### Interfaces

- [Patch](../interfaces/utils_patcher.Patch.md)
- [PatchOptions](../interfaces/utils_patcher.PatchOptions.md)

### Variables

- [callOriginal](utils_patcher.md#calloriginal)

### Functions

- [afterPatch](utils_patcher.md#afterpatch)
- [beforePatch](utils_patcher.md#beforepatch)
- [replacePatch](utils_patcher.md#replacepatch)

## Variables

### callOriginal

• **callOriginal**: `symbol`

#### Defined in

[src/utils/patcher.ts:3](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/utils/patcher.ts#L3)

## Functions

### afterPatch

▸ **afterPatch**(`object`, `property`, `handler`, `options?`): [`Patch`](../interfaces/utils_patcher.Patch.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `object` | `any` |
| `property` | `string` |
| `handler` | (`args`: `any`[], `ret`: `any`) => `any` |
| `options` | [`PatchOptions`](../interfaces/utils_patcher.PatchOptions.md) |

#### Returns

[`Patch`](../interfaces/utils_patcher.Patch.md)

#### Defined in

[src/utils/patcher.ts:38](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/utils/patcher.ts#L38)

___

### beforePatch

▸ **beforePatch**(`object`, `property`, `handler`, `options?`): [`Patch`](../interfaces/utils_patcher.Patch.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `object` | `any` |
| `property` | `string` |
| `handler` | (`args`: `any`[]) => `any` |
| `options` | [`PatchOptions`](../interfaces/utils_patcher.PatchOptions.md) |

#### Returns

[`Patch`](../interfaces/utils_patcher.Patch.md)

#### Defined in

[src/utils/patcher.ts:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/utils/patcher.ts#L24)

___

### replacePatch

▸ **replacePatch**(`object`, `property`, `handler`, `options?`): [`Patch`](../interfaces/utils_patcher.Patch.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `object` | `any` |
| `property` | `string` |
| `handler` | (`args`: `any`[]) => `any` |
| `options` | [`PatchOptions`](../interfaces/utils_patcher.PatchOptions.md) |

#### Returns

[`Patch`](../interfaces/utils_patcher.Patch.md)

#### Defined in

[src/utils/patcher.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/utils/patcher.ts#L52)
