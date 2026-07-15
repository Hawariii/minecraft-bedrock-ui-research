# Bindings

This document contains known binding names used by Minecraft Bedrock Edition JSON UI.

> **Status:** Work in Progress

Bindings connect UI controls with game data, values, states, and collections.

---

# Statistics

| Total | Confirmed | Community | Experimental | Unknown |
|-------:|----------:|----------:|-------------:|--------:|
| 9 | 9 | 0 | 0 | 0 |

---

# Known Bindings

## Global

---

## `#visible`

Controls whether a UI element is visible.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Boolean |
| Scope | Global |
| Source | Vanilla UI |

**Description**

Returns the visibility state of a control.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#visible",
      "binding_type": "view"
    }
  ]
}
```

---

## `#enabled`

Controls whether a UI element can be interacted with.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Boolean |
| Scope | Global |
| Source | Vanilla UI |

**Description**

Determines whether the control is enabled or disabled.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#enabled",
      "binding_type": "view"
    }
  ]
}
```

---

## `#text`

Provides text content for a control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | String |
| Scope | Global |
| Source | Vanilla UI |

**Description**

Used by text controls to display dynamic text.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#text",
      "binding_type": "view"
    }
  ]
}
```

---

## `#alpha`

Controls the transparency of a UI element.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Float |
| Scope | Global |
| Source | Vanilla UI |

**Description**

Controls opacity of UI controls.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#alpha",
      "binding_type": "view"
    }
  ]
}
```

---

## `#size`

Provides the size of a UI element.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Vector2 |
| Scope | Global |
| Source | Vanilla UI |

**Description**

Used to dynamically control element size.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#size",
      "binding_type": "view"
    }
  ]
}
```

---

## `#offset`

Provides the position offset of a UI element.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Vector2 |
| Scope | Global |
| Source | Vanilla UI |

**Description**

Controls dynamic positioning.

**Example**

```json
{
  "bindings": [
    {
    "binding_name": "#offset",
    "binding_type": "view"
    }
  ]
}
```

---

## `#collection_index`

Returns the current index inside a collection.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Collection Binding |
| Value Type | Integer |
| Scope | Collection |
| Source | Vanilla UI |

**Description**

Used by repeated UI elements.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#collection_index",
      "binding_type": "collection"
    }
  ]
}
```

---

## `#collection_name`

Returns the name of the current collection.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Collection Binding |
| Value Type | String |
| Scope | Collection |
| Source | Vanilla UI |

**Description**

Identifies the active UI collection.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#collection_name",
      "binding_type": "collection"
    }
  ]
}
```

---

## `#is_hovered`

Returns whether a control is currently hovered.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Boolean |
| Scope | Interactive Controls |
| Source | Vanilla UI |

**Description**

Used for hover state changes.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#is_hovered",
      "binding_type": "view"
    }
  ]
}
```

---

## `#is_selected`

Returns whether a control is currently selected.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Boolean |
| Scope | Interactive Controls |
| Source | Vanilla UI |

**Description**

Used to change UI appearance based on selection state.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#is_selected",
      "binding_type": "view"
    }
  ]
}
```

---

## `#is_checked`

Returns the checked state of a checkbox or toggle control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Boolean |
| Scope | Toggle Controls |
| Source | Vanilla UI |

**Description**

Used by checkbox and toggle elements.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#is_checked",
      "binding_type": "view"
    }
  ]
}
```

---

## `#toggle_state`

Returns the current toggle state.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Integer |
| Scope | Toggle Controls |
| Source | Vanilla UI |

**Description**

Used for controls with multiple toggle states.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#toggle_state",
      "binding_type": "view"
    }
  ]
}
```

---

## `#value`

Returns the current value of a control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Number / String |
| Scope | Input Controls |
| Source | Vanilla UI |

**Description**

Used by sliders, inputs, and value-based controls.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#value",
      "binding_type": "view"
    }
  ]
}
```

---

## `#max`

Returns the maximum value of a control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Number |
| Scope | Input Controls |
| Source | Vanilla UI |

**Description**

Commonly used with sliders and progress controls.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#max",
      "binding_type": "view"
    }
  ]
}
```

---

## `#min`

Returns the minimum value of a control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Number |
| Scope | Input Controls |
| Source | Vanilla UI |

**Description**

Defines the lowest allowed value.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#min",
      "binding_type": "view"
    }
  ]
}
```

---

## `#progress`

Returns the progress value of a control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Float |
| Scope | Progress Controls |
| Source | Vanilla UI |

**Description**

Used by progress bars and loading indicators.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#progress",
      "binding_type": "view"
    }
  ]
}
```

---

## `#current_index`

Returns the current index of a selected item.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Collection Binding |
| Value Type | Integer |
| Scope | Collections |
| Source | Vanilla UI |

**Description**

Used to track selected items in lists.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#current_index",
      "binding_type": "collection"
    }
  ]
}
```

---

# HUD

> No confirmed screen-specific bindings documented yet.

---

# Inventory

> No confirmed screen-specific bindings documented yet.

---

# Settings

> No confirmed screen-specific bindings documented yet.

---

# Experimental Bindings

```json
{}
```

---

# Unknown Bindings

```json
{}
```

---

# Inventory Bindings

## `#inventory_selected_slot`

Returns the currently selected inventory slot.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Integer |
| Scope | Inventory Screen |
| Source | Vanilla UI |

**Description**

Used by inventory controls to track the selected slot.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#inventory_selected_slot",
      "binding_type": "view"
    }
  ]
}
```

---

## `#item_name`

Returns the display name of an item.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | String |
| Scope | Inventory / Item Controls |
| Source | Vanilla UI |

**Description**

Used to display item names dynamically.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#item_name",
      "binding_type": "view"
    }
  ]
}
```

---

## `#item_count`

Returns the amount of an item stack.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Integer |
| Scope | Inventory / Item Controls |
| Source | Vanilla UI |

**Description**

Used for stack count labels.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#item_count",
      "binding_type": "view"
    }
  ]
}
```

---

## `#item_icon`

Returns the icon texture of an item.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Texture |
| Scope | Inventory / Item Controls |
| Source | Vanilla UI |

**Description**

Used by item renderer controls.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#item_icon",
      "binding_type": "view"
    }
  ]
}
```

---

## `#item_durability`

Returns the durability value of an item.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Number |
| Scope | Inventory / Item Controls |
| Source | Vanilla UI |

**Description**

Used to display durability bars.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#item_durability",
      "binding_type": "view"
    }
  ]
}
```

---

# Crafting Bindings

## `#recipe_selected`

Returns the selected recipe state.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Boolean |
| Scope | Crafting Screen |
| Source | Vanilla UI |

**Description**

Controls recipe selection states.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#recipe_selected",
      "binding_type": "view"
    }
  ]
}
```

---

## `#recipe_name`

Returns the name of the current recipe.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | String |
| Scope | Crafting Screen |
| Source | Vanilla UI |

**Description**

Used to display recipe names.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#recipe_name",
      "binding_type": "view"
    }
  ]
}
```

---

# Collection Bindings

## `#collection_length`

Returns the number of elements inside a collection.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Collection Binding |
| Value Type | Integer |
| Scope | Collections |
| Source | Vanilla UI |

**Description**

Used for lists, grids, and repeated controls.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#collection_length",
      "binding_type": "collection"
    }
  ]
}
```

---

## `#collection_selected`

Returns whether an item in a collection is selected.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Collection Binding |
| Value Type | Boolean |
| Scope | Collections |
| Source | Vanilla UI |

**Description**

Used by list and grid selection systems.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#collection_selected",
      "binding_type": "collection"
    }
  ]
}
```

---

# Updated Statistics

| Total | Confirmed | Community | Experimental | Unknown |
|-------:|----------:|----------:|-------------:|--------:|
| 22 | 22 | 0 | 0 | 0 |

---

# HUD Bindings

## `#hud_visible`

Controls HUD visibility.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Boolean |
| Scope | HUD |
| Source | Vanilla UI |

**Description**

Used to show or hide HUD elements.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#hud_visible",
      "binding_type": "view"
    }
  ]
}
```

---

## `#chat_visible`

Controls chat visibility.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Boolean |
| Scope | HUD / Chat |
| Source | Vanilla UI |

**Description**

Determines whether the chat UI should appear.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#chat_visible",
      "binding_type": "view"
    }
  ]
}
```

---

## `#paperdoll_visible`

Controls the Paper Doll display.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | Boolean |
| Scope | HUD |
| Source | Vanilla UI |

**Description**

Controls player model visibility on HUD.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#paperdoll_visible",
      "binding_type": "view"
    }
  ]
}
```

---

# Chat Bindings

## `#chat_message`

Returns current chat message text.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | String |
| Scope | Chat Screen |
| Source | Vanilla UI |

**Description**

Used to display chat messages.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#chat_message",
      "binding_type": "view"
    }
  ]
}
```

---

## `#chat_input`

Returns the current chat input.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | View Binding |
| Value Type | String |
| Scope | Chat Screen |
| Source | Vanilla UI |

**Description**

Used by chat input controls.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#chat_input",
      "binding_type": "view"
    }
  ]
}
```

---

# Settings Bindings

## `#setting_value`

Returns the current value of a setting.

| Property | Value |
|----------|-------|
| Status | ⚠️ Experimental |
| Type | View Binding |
| Value Type | Mixed |
| Scope | Settings Screen |
| Source | Community Research |

**Description**

Used by settings controls to display current values.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#setting_value",
      "binding_type": "view"
    }
  ]
}
```

---

## `#setting_name`

Returns the display name of a setting.

| Property | Value |
|----------|-------|
| Status | ⚠️ Experimental |
| Type | View Binding |
| Value Type | String |
| Scope | Settings Screen |
| Source | Community Research |

**Description**

Used by settings list entries.

**Example**

```json
{
  "bindings": [
    {
      "binding_name": "#setting_name",
      "binding_type": "view"
    }
  ]
}
```

---

# Experimental Bindings

```json
{
  "#setting_value": {
    "reason": "Observed in UI research but requires more verification."
  },
  "#setting_name": {
    "reason": "Observed in UI research but requires more verification."
  }
}
```

---

# Unknown Bindings

```json
{}
```

---

# Updated Statistics

| Total | Confirmed | Community | Experimental | Unknown |
|-------:|----------:|----------:|-------------:|--------:|
| 30 | 28 | 0 | 2 | 0 |


