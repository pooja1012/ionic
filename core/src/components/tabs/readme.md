# ion-tabs

Tabs are a top level navigation component for created multiple stacked navs.
The component is a container of individual [Tab](../Tab/) components.


<!-- Auto Generated Below -->


## Properties

| Property       | Attribute       | Description                                                                     | Type                  |
| -------------- | --------------- | ------------------------------------------------------------------------------- | --------------------- |
| `name`         | `name`          | A unique name for the tabs.                                                     | `string \| undefined` |
| `tabbarHidden` | `tabbar-hidden` | If `true`, the tabbar will be hidden. Defaults to `false`.                      | `boolean`             |
| `useRouter`    | `use-router`    | If `true`, the tabs will use the router and `selectedTab` will not do anything. | `boolean`             |


## Events

| Event              | Description                                                                |
| ------------------ | -------------------------------------------------------------------------- |
| `ionChange`        | Emitted when the tab changes.                                              |
| `ionNavDidChange`  | Emitted when the navigation has finished transitioning to a new component. |
| `ionNavWillChange` | Emitted when the navigation is about to transition to a new component.     |
| `ionNavWillLoad`   | Emitted when the navigation will load a component.                         |


## Methods

### `getRouteId() => Promise<RouteID | undefined>`



#### Returns

Type: `Promise<RouteID | undefined>`



### `getSelected() => Promise<HTMLIonTabElement | undefined>`

Get the currently selected tab

#### Returns

Type: `Promise<HTMLIonTabElement | undefined>`



### `getTab(tabOrIndex: string | number | HTMLIonTabElement) => Promise<HTMLIonTabElement | undefined>`

Get the tab at the given index

#### Parameters

| Name         | Type                                    | Description |
| ------------ | --------------------------------------- | ----------- |
| `tabOrIndex` | `HTMLIonTabElement \| number \| string` |             |

#### Returns

Type: `Promise<HTMLIonTabElement | undefined>`



### `select(tabOrIndex: number | HTMLIonTabElement) => Promise<boolean>`

Index or the Tab instance, of the tab to select.

#### Parameters

| Name         | Type                          | Description |
| ------------ | ----------------------------- | ----------- |
| `tabOrIndex` | `HTMLIonTabElement \| number` |             |

#### Returns

Type: `Promise<boolean>`



### `setRouteId(id: string) => Promise<RouteWrite>`



#### Parameters

| Name | Type     | Description |
| ---- | -------- | ----------- |
| `id` | `string` |             |

#### Returns

Type: `Promise<RouteWrite>`




----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
