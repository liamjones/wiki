[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/Field](../modules/deck_components_Field.md) / FieldProps

# Interface: FieldProps

[deck-components/Field](../modules/deck_components_Field.md).FieldProps

## Hierarchy

- `HTMLAttributes`<[`HTMLDivElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\>

- [`FooterLegendProps`](deck_components_FooterLegend.FooterLegendProps.md)

  ↳ **`FieldProps`**

## Table of contents

### Properties

- [actionDescriptionMap](deck_components_Field.FieldProps.md#actiondescriptionmap)
- [bottomSeparator](deck_components_Field.FieldProps.md#bottomseparator)
- [childrenContainerWidth](deck_components_Field.FieldProps.md#childrencontainerwidth)
- [childrenLayout](deck_components_Field.FieldProps.md#childrenlayout)
- [className](deck_components_Field.FieldProps.md#classname)
- [description](deck_components_Field.FieldProps.md#description)
- [disabled](deck_components_Field.FieldProps.md#disabled)
- [highlightOnFocus](deck_components_Field.FieldProps.md#highlightonfocus)
- [icon](deck_components_Field.FieldProps.md#icon)
- [indentLevel](deck_components_Field.FieldProps.md#indentlevel)
- [inlineWrap](deck_components_Field.FieldProps.md#inlinewrap)
- [label](deck_components_Field.FieldProps.md#label)
- [onButtonDown](deck_components_Field.FieldProps.md#onbuttondown)
- [onButtonUp](deck_components_Field.FieldProps.md#onbuttonup)
- [onCancelActionDescription](deck_components_Field.FieldProps.md#oncancelactiondescription)
- [onCancelButton](deck_components_Field.FieldProps.md#oncancelbutton)
- [onGamepadBlur](deck_components_Field.FieldProps.md#ongamepadblur)
- [onGamepadDirection](deck_components_Field.FieldProps.md#ongamepaddirection)
- [onGamepadFocus](deck_components_Field.FieldProps.md#ongamepadfocus)
- [onMenuActionDescription](deck_components_Field.FieldProps.md#onmenuactiondescription)
- [onMenuButton](deck_components_Field.FieldProps.md#onmenubutton)
- [onOKActionDescription](deck_components_Field.FieldProps.md#onokactiondescription)
- [onOKButton](deck_components_Field.FieldProps.md#onokbutton)
- [onOptionsActionDescription](deck_components_Field.FieldProps.md#onoptionsactiondescription)
- [onOptionsButton](deck_components_Field.FieldProps.md#onoptionsbutton)
- [onSecondaryActionDescription](deck_components_Field.FieldProps.md#onsecondaryactiondescription)
- [onSecondaryButton](deck_components_Field.FieldProps.md#onsecondarybutton)
- [padding](deck_components_Field.FieldProps.md#padding)
- [spacingBetweenLabelAndChild](deck_components_Field.FieldProps.md#spacingbetweenlabelandchild)
- [verticalAlignment](deck_components_Field.FieldProps.md#verticalalignment)

## Properties

### actionDescriptionMap

• `Optional` **actionDescriptionMap**: `unknown`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[actionDescriptionMap](deck_components_FooterLegend.FooterLegendProps.md#actiondescriptionmap)

#### Defined in

[src/deck-components/FooterLegend.ts:50](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L50)

___

### bottomSeparator

• `Optional` **bottomSeparator**: ``"standard"`` \| ``"thick"`` \| ``"none"``

#### Defined in

[src/deck-components/Field.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L7)

___

### childrenContainerWidth

• `Optional` **childrenContainerWidth**: ``"min"`` \| ``"max"`` \| ``"fixed"``

#### Defined in

[src/deck-components/Field.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L13)

___

### childrenLayout

• `Optional` **childrenLayout**: ``"below"`` \| ``"inline"``

#### Defined in

[src/deck-components/Field.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L12)

___

### className

• `Optional` **className**: `string`

#### Overrides

HTMLAttributes.className

#### Defined in

[src/deck-components/Field.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L16)

___

### description

• `Optional` **description**: `ReactNode`

#### Defined in

[src/deck-components/Field.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L8)

___

### disabled

• `Optional` **disabled**: `boolean`

#### Defined in

[src/deck-components/Field.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L9)

___

### highlightOnFocus

• `Optional` **highlightOnFocus**: `boolean`

#### Defined in

[src/deck-components/Field.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L17)

___

### icon

• `Optional` **icon**: `ReactNode`

#### Defined in

[src/deck-components/Field.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L10)

___

### indentLevel

• `Optional` **indentLevel**: `number`

#### Defined in

[src/deck-components/Field.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L18)

___

### inlineWrap

• `Optional` **inlineWrap**: ``"keep-inline"`` \| ``"shift-children-below"``

#### Defined in

[src/deck-components/Field.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L11)

___

### label

• `Optional` **label**: `ReactNode`

#### Defined in

[src/deck-components/Field.tsx:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L6)

___

### onButtonDown

• `Optional` **onButtonDown**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onButtonDown](deck_components_FooterLegend.FooterLegendProps.md#onbuttondown)

#### Defined in

[src/deck-components/FooterLegend.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L56)

___

### onButtonUp

• `Optional` **onButtonUp**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onButtonUp](deck_components_FooterLegend.FooterLegendProps.md#onbuttonup)

#### Defined in

[src/deck-components/FooterLegend.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L57)

___

### onCancelActionDescription

• `Optional` **onCancelActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onCancelActionDescription](deck_components_FooterLegend.FooterLegendProps.md#oncancelactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L52)

___

### onCancelButton

• `Optional` **onCancelButton**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onCancelButton](deck_components_FooterLegend.FooterLegendProps.md#oncancelbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L59)

___

### onGamepadBlur

• `Optional` **onGamepadBlur**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onGamepadBlur](deck_components_FooterLegend.FooterLegendProps.md#ongamepadblur)

#### Defined in

[src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L64)

___

### onGamepadDirection

• `Optional` **onGamepadDirection**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onGamepadDirection](deck_components_FooterLegend.FooterLegendProps.md#ongamepaddirection)

#### Defined in

[src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L62)

___

### onGamepadFocus

• `Optional` **onGamepadFocus**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onGamepadFocus](deck_components_FooterLegend.FooterLegendProps.md#ongamepadfocus)

#### Defined in

[src/deck-components/FooterLegend.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L63)

___

### onMenuActionDescription

• `Optional` **onMenuActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onMenuActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onmenuactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L55)

___

### onMenuButton

• `Optional` **onMenuButton**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onMenuButton](deck_components_FooterLegend.FooterLegendProps.md#onmenubutton)

#### Defined in

[src/deck-components/FooterLegend.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L65)

___

### onOKActionDescription

• `Optional` **onOKActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOKActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onokactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L51)

___

### onOKButton

• `Optional` **onOKButton**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOKButton](deck_components_FooterLegend.FooterLegendProps.md#onokbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L58)

___

### onOptionsActionDescription

• `Optional` **onOptionsActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOptionsActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onoptionsactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L54)

___

### onOptionsButton

• `Optional` **onOptionsButton**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOptionsButton](deck_components_FooterLegend.FooterLegendProps.md#onoptionsbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L61)

___

### onSecondaryActionDescription

• `Optional` **onSecondaryActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onSecondaryActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onsecondaryactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L53)

___

### onSecondaryButton

• `Optional` **onSecondaryButton**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onSecondaryButton](deck_components_FooterLegend.FooterLegendProps.md#onsecondarybutton)

#### Defined in

[src/deck-components/FooterLegend.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/FooterLegend.ts#L60)

___

### padding

• `Optional` **padding**: ``"standard"`` \| ``"none"`` \| ``"compact"``

#### Defined in

[src/deck-components/Field.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L15)

___

### spacingBetweenLabelAndChild

• `Optional` **spacingBetweenLabelAndChild**: ``"none"``

#### Defined in

[src/deck-components/Field.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L14)

___

### verticalAlignment

• `Optional` **verticalAlignment**: ``"none"`` \| ``"center"``

#### Defined in

[src/deck-components/Field.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/deck-components/Field.tsx#L19)
