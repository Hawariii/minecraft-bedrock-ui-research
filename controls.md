# Controls

This document contains known control types used by Minecraft Bedrock Edition JSON UI.

> **Status:** Work in Progress

Controls are the building blocks of Minecraft Bedrock UI. They define layout, rendering, interaction, input handling, and special game-related UI behavior.

---

# Statistics

| Total | Confirmed | Community | Experimental | Unknown |
|-------:|----------:|----------:|-------------:|--------:|
| 0 | 0 | 0 | 0 | 0 |

---

# Known Controls

# Base Controls

---

## `panel`

Basic UI container.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Container |
| Children | Yes |
| Source | Vanilla UI |

**Description**

A container used to hold child controls.

**Example**

```json
{
  "main_panel": {
    "type": "panel",
    "controls": []
  }
}
```

---

## `image`

Texture rendering control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Display |
| Children | No |
| Source | Vanilla UI |

**Description**

Displays textures, icons, and UI graphics.

**Example**

```json
{
  "background": {
    "type": "image",
    "texture": "textures/ui/background"
  }
}
```

---

## `label`

Text rendering control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Text |
| Children | No |
| Source | Vanilla UI |

**Description**

Displays static or dynamic text.

**Example**

```json
{
  "title": {
    "type": "label",
    "text": "Example"
  }
}
```

---

## `button`

Interactive button control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Interactive |
| Children | Yes |
| Source | Vanilla UI |

**Description**

Receives user interaction and triggers actions.

**Example**

```json
{
  "play_button": {
    "type": "button"
  }
}
```

---

## `custom`

Custom UI control.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Custom |
| Children | Unknown |
| Source | Community Research |

**Description**

Used for custom behaviors or unsupported UI elements.

**Example**

```json
{
  "custom_control": {
    "type": "custom"
  }
}
```

---

# Layout Controls

---

## `stack_panel`

Automatic layout container.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Layout |
| Children | Yes |
| Source | Vanilla UI |

**Description**

Arranges child controls vertically or horizontally.

**Example**

```json
{
  "menu_list": {
    "type": "stack_panel",
    "orientation": "vertical"
  }
}
```

---

## `grid`

Grid based layout.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Layout |
| Children | Yes |
| Source | Vanilla UI |

**Description**

Used for inventory and item layouts.

**Example**

```json
{
  "inventory_grid": {
    "type": "grid"
  }
}
```

---

## `scroll_panel`

Scrollable container.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Layout |
| Children | Yes |
| Source | Vanilla UI |

**Description**

Allows scrolling through child elements.

**Example**

```json
{
  "scroll_area": {
    "type": "scroll_panel"
  }
}
```

---

## `collection_panel`

Collection based container.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Collection |
| Children | Yes |
| Source | Vanilla UI |

**Description**

Displays repeated elements from collections.

**Example**

```json
{
  "items": {
    "type": "collection_panel",
    "collection_name": "inventory_items"
  }
}
```

---

# Statistics Update

| Total | Confirmed | Community | Experimental | Unknown |
|-------:|----------:|----------:|-------------:|--------:|
| 9 | 8 | 1 | 0 | 0 |

---

# Input Controls

---

## `edit_box`

Text input control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Input |
| Children | No |
| Source | Vanilla UI |

**Description**

Used for entering text such as chat messages and search queries.

**Example**

```json
{
  "text_input": {
    "type": "edit_box"
  }
}
```

---

## `slider`

Numeric value input control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Input |
| Children | No |
| Source | Vanilla UI |

**Description**

Used for adjusting values like volume and brightness.

**Example**

```json
{
  "volume_slider": {
    "type": "slider"
  }
}
```

---

## `toggle`

Boolean switch control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Input |
| Children | No |
| Source | Vanilla UI |

**Description**

Used for on/off settings.

**Example**

```json
{
  "toggle_option": {
    "type": "toggle"
  }
}
```

---

## `checkbox`

Checkbox input control.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Input |
| Children | No |
| Source | Vanilla UI |

**Description**

Used for selecting multiple options.

**Example**

```json
{
  "checkbox_option": {
    "type": "checkbox"
  }
}
```

---

## `radio_button`

Single selection input control.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Input |
| Children | No |
| Source | Community Research |

**Description**

Used for mutually exclusive selections.

**Example**

```json
{
  "radio_option": {
    "type": "radio_button"
  }
}
```

---

# Inventory Controls

---

## `item_renderer`

Renders an item stack.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Minecraft Specific |
| Children | No |
| Source | Vanilla UI |

**Description**

Used by inventory, crafting, and container screens.

**Example**

```json
{
  "item": {
    "type": "item_renderer"
  }
}
```

---

## `inventory_grid`

Inventory slot grid.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Minecraft Specific |
| Children | Yes |
| Source | Community Research |

**Description**

Displays multiple inventory slots.

**Example**

```json
{
  "inventory": {
    "type": "inventory_grid"
  }
}
```

---

## `hotbar`

Player hotbar control.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Minecraft Specific |
| Children | Yes |
| Source | Community Research |

**Description**

Displays hotbar slots.

**Example**

```json
{
  "hotbar": {
    "type": "hotbar"
  }
}
```

---

## `slot`

Inventory slot container.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Minecraft Specific |
| Children | Yes |
| Source | Community Research |

**Description**

Represents a single item slot.

**Example**

```json
{
  "slot": {
    "type": "slot"
  }
}
```

---

# Progress Controls

---

## `progress_bar`

Displays progress values.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Display |
| Children | No |
| Source | Vanilla UI |

**Description**

Used for loading, progress, and durability indicators.

**Example**

```json
{
  "progress": {
    "type": "progress_bar"
  }
}
```

---

# Statistics Update

| Total | Confirmed | Community | Experimental | Unknown |
|-------:|----------:|----------:|-------------:|--------:|
| 20 | 14 | 6 | 0 | 0 |


