# Collections

This document contains known collection names used by Minecraft Bedrock Edition JSON UI.

> **Status:** Work in Progress

Collections are used to manage repeated UI elements such as item lists, recipes, settings entries, player lists, and dynamic UI data.

---

# Statistics

| Total | Confirmed | Community | Experimental | Unknown |
|-------:|----------:|----------:|-------------:|--------:|
| 0 | 0 | 0 | 0 | 0 |

---

# Known Collections

# Inventory

---

## `inventory_items`

Contains player inventory item slots.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Item Collection |
| Screen | Inventory |
| Source | Vanilla UI |

**Example**

```json
{
  "collection_name": "inventory_items",
  "binding_type": "collection"
}
```

---

## `hotbar_items`

Contains hotbar item slots.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Item Collection |
| Screen | HUD |
| Source | Vanilla UI |

**Example**

```json
{
  "collection_name": "hotbar_items",
  "binding_type": "collection"
}
```

---

## `armor_items`

Contains equipped armor slots.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Item Collection |
| Screen | Inventory |
| Source | Vanilla UI |

**Example**

```json
{
  "collection_name": "armor_items",
  "binding_type": "collection"
}
```

---

## `crafting_items`

Contains crafting input/output items.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Item Collection |
| Screen | Crafting |
| Source | Vanilla UI |

**Example**

```json
{
  "collection_name": "crafting_items",
  "binding_type": "collection"
}
```

---

# Creative Inventory

---

## `creative_items`

Creative mode item list.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Item Collection |
| Screen | Creative Inventory |
| Source | Vanilla UI |

---

## `creative_categories`

Creative inventory category list.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Category Collection |
| Screen | Creative Inventory |
| Source | Community Research |

---

# Recipe System

---

## `recipe_items`

Contains available recipes.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Recipe Collection |
| Screen | Crafting |
| Source | Vanilla UI |

---

## `recipe_book_items`

Recipe book entries.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Recipe Collection |
| Screen | Recipe Book |
| Source | Community Research |

---

# Container Screens

---

## `container_items`

Generic container inventory collection.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Item Collection |
| Screen | Chest / Containers |
| Source | Vanilla UI |

---

## `furnace_items`

Furnace slots.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Item Collection |
| Screen | Furnace |
| Source | Vanilla UI |

---

## `blast_furnace_items`

Blast furnace slots.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Item Collection |
| Screen | Blast Furnace |
| Source | Vanilla UI |

---

## `smoker_items`

Smoker slots.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Item Collection |
| Screen | Smoker |
| Source | Vanilla UI |

---

# Trading

---

## `trade_items`

Villager trade entries.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Trade Collection |
| Screen | Villager |
| Source | Community Research |

---

## `trade_recipes`

Available villager trades.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Recipe Collection |
| Screen | Villager |
| Source | Community Research |

---

# Settings

---

## `settings_list`

Settings menu entries.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | List Collection |
| Screen | Settings |
| Source | Vanilla UI |

---

# Chat

---

## `chat_messages`

Chat message history.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Text Collection |
| Screen | Chat |
| Source | Vanilla UI |

---

# Experimental Collections

```json
{}
```

---

# Unknown Collections

```json
{}
```

---

# Updated Statistics

| Total | Confirmed | Community | Experimental | Unknown |
|-------:|----------:|----------:|-------------:|--------:|
| 16 | 11 | 5 | 0 | 0 |
```

---

# Furnace Family

## `furnace_input`

Input item slot for furnace screens.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Item Collection |
| Screen | Furnace |
| Source | Community Research |

**Description**

Contains the input slot item.

**Example**

```json
{
  "collection_name": "furnace_input",
  "binding_type": "collection"
}
```

---

## `furnace_fuel`

Fuel slot collection.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Item Collection |
| Screen | Furnace |
| Source | Community Research |

**Description**

Contains fuel slot data.

**Example**

```json
{
  "collection_name": "furnace_fuel",
  "binding_type": "collection"
}
```

---

## `furnace_output`

Output item collection.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Item Collection |
| Screen | Furnace |
| Source | Community Research |

**Description**

Contains smelted result item.

**Example**

```json
{
  "collection_name": "furnace_output",
  "binding_type": "collection"
}
```

---

# Enchanting

## `enchant_options`

Available enchantment options.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Option Collection |
| Screen | Enchanting |
| Source | Community Research |

**Description**

Contains enchantment choices.

**Example**

```json
{
  "collection_name": "enchant_options",
  "binding_type": "collection"
}
```

---

# Anvil

## `anvil_items`

Items used in anvil operations.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Item Collection |
| Screen | Anvil |
| Source | Community Research |

**Description**

Contains anvil input and result items.

**Example**

```json
{
  "collection_name": "anvil_items",
  "binding_type": "collection"
}
```

---

# Smithing

## `smithing_items`

Smithing table item slots.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Item Collection |
| Screen | Smithing |
| Source | Community Research |

**Description**

Contains smithing template, base, and addition items.

**Example**

```json
{
  "collection_name": "smithing_items",
  "binding_type": "collection"
}
```

---

# Loom

## `loom_patterns`

Available banner patterns.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Pattern Collection |
| Screen | Loom |
| Source | Community Research |

**Description**

Contains available banner patterns.

**Example**

```json
{
  "collection_name": "loom_patterns",
  "binding_type": "collection"
}
```

---

# Stonecutter

## `stonecutter_recipes`

Stonecutter recipe list.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Recipe Collection |
| Screen | Stonecutter |
| Source | Community Research |

**Description**

Contains available stonecutter outputs.

**Example**

```json
{
  "collection_name": "stonecutter_recipes",
  "binding_type": "collection"
}
```

---

# Beacon

## `beacon_effects`

Available beacon effects.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Option Collection |
| Screen | Beacon |
| Source | Community Research |

**Description**

Contains selectable beacon powers.

**Example**

```json
{
  "collection_name": "beacon_effects",
  "binding_type": "collection"
}
```

---

# Horse

## `horse_inventory`

Horse inventory slots.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Item Collection |
| Screen | Horse |
| Source | Community Research |

**Description**

Contains saddle, armor, and inventory slots.

**Example**

```json
{
  "collection_name": "horse_inventory",
  "binding_type": "collection"
}
```

---

# NPC

## `npc_buttons`

NPC dialogue buttons.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Button Collection |
| Screen | NPC |
| Source | Community Research |

**Description**

Contains NPC interaction options.

**Example**

```json
{
  "collection_name": "npc_buttons",
  "binding_type": "collection"
}
```

---

# Updated Statistics

| Total | Confirmed | Community | Experimental | Unknown |
|-------:|----------:|----------:|-------------:|--------:|
| 27 | 11 | 16 | 0 | 0 |


---

# Command Block

## `command_block_settings`

Command block configuration options.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Settings Collection |
| Screen | Command Block |
| Source | Community Research |

**Description**

Contains command block options such as command input and settings.

**Example**

```json
{
  "collection_name": "command_block_settings",
  "binding_type": "collection"
}
```

---

# Structure Block

## `structure_list`

Available structures.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | List Collection |
| Screen | Structure Block |
| Source | Community Research |

**Description**

Contains saved structure entries.

**Example**

```json
{
  "collection_name": "structure_list",
  "binding_type": "collection"
}
```

---

## `structure_options`

Structure block options.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Settings Collection |
| Screen | Structure Block |
| Source | Community Research |

**Description**

Contains structure block settings.

**Example**

```json
{
  "collection_name": "structure_options",
  "binding_type": "collection"
}
```

---

# Jigsaw

## `jigsaw_options`

Jigsaw block configuration options.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Settings Collection |
| Screen | Jigsaw |
| Source | Community Research |

**Description**

Contains jigsaw block configuration.

**Example**

```json
{
  "collection_name": "jigsaw_options",
  "binding_type": "collection"
}
```

---

# World Selection

## `world_list`

Available worlds.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | World Collection |
| Screen | Play Screen |
| Source | Vanilla UI |

**Description**

Contains saved world entries.

**Example**

```json
{
  "collection_name": "world_list",
  "binding_type": "collection"
}
```

---

## `world_templates`

Available world templates.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Template Collection |
| Screen | World Template Screen |
| Source | Vanilla UI |

**Description**

Contains downloadable world templates.

**Example**

```json
{
  "collection_name": "world_templates",
  "binding_type": "collection"
}
```

---

# Multiplayer

## `server_list`

Available multiplayer servers.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Server Collection |
| Screen | Servers |
| Source | Vanilla UI |

**Description**

Contains server entries.

**Example**

```json
{
  "collection_name": "server_list",
  "binding_type": "collection"
}
```

---

## `friends_list`

Player friends list.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Player Collection |
| Screen | Multiplayer |
| Source | Community Research |

**Description**

Contains multiplayer friend entries.

**Example**

```json
{
  "collection_name": "friends_list",
  "binding_type": "collection"
}
```

---

# Marketplace

## `marketplace_items`

Marketplace content list.

| Property | Value |
|----------|-------|
| Status | ✅ Confirmed |
| Type | Content Collection |
| Screen | Marketplace |
| Source | Vanilla UI |

**Description**

Contains marketplace products.

**Example**

```json
{
  "collection_name": "marketplace_items",
  "binding_type": "collection"
}
```

---

## `marketplace_categories`

Marketplace categories.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Category Collection |
| Screen | Marketplace |
| Source | Community Research |

**Description**

Contains marketplace category entries.

**Example**

```json
{
  "collection_name": "marketplace_categories",
  "binding_type": "collection"
}
```

---

# Dressing Room

## `character_items`

Character customization items.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Cosmetic Collection |
| Screen | Dressing Room |
| Source | Community Research |

**Description**

Contains equipped and available character items.

**Example**

```json
{
  "collection_name": "character_items",
  "binding_type": "collection"
}
```

---

## `character_categories`

Character customization categories.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Category Collection |
| Screen | Dressing Room |
| Source | Community Research |

**Description**

Contains character creator categories.

**Example**

```json
{
  "collection_name": "character_categories",
  "binding_type": "collection"
}
```

---

# Emote

## `emote_list`

Available emotes.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Emote Collection |
| Screen | Emote Screen |
| Source | Community Research |

**Description**

Contains available player emotes.

**Example**

```json
{
  "collection_name": "emote_list",
  "binding_type": "collection"
}
```

---

# Updated Statistics

| Total | Confirmed | Community | Experimental | Unknown |
|-------:|----------:|----------:|-------------:|--------:|
| 41 | 16 | 25 | 0 | 0 |

---

# Camera

## `camera_presets`

Camera preset collection.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Camera Collection |
| Screen | Camera |
| Source | Community Research |

**Description**

Contains available camera presets.

**Example**

```json
{
  "collection_name": "camera_presets",
  "binding_type": "collection"
}
```

---

# Loading

## `loading_messages`

Loading screen messages.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Text Collection |
| Screen | Loading Screen |
| Source | Community Research |

**Description**

Contains loading tips or messages.

**Example**

```json
{
  "collection_name": "loading_messages",
  "binding_type": "collection"
}
```

---

# Death Screen

## `death_messages`

Death screen message collection.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Text Collection |
| Screen | Death Screen |
| Source | Community Research |

**Description**

Contains death related messages.

**Example**

```json
{
  "collection_name": "death_messages",
  "binding_type": "collection"
}
```

---

# Disconnect Screen

## `disconnect_reasons`

Disconnect reason list.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Text Collection |
| Screen | Disconnect Screen |
| Source | Community Research |

**Description**

Contains disconnect messages.

**Example**

```json
{
  "collection_name": "disconnect_reasons",
  "binding_type": "collection"
}
```

---

# UI Lists

## `button_list`

Generic button list collection.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Button Collection |
| Screen | Multiple |
| Source | Community Research |

**Description**

Used for dynamic button lists.

**Example**

```json
{
  "collection_name": "button_list",
  "binding_type": "collection"
}
```

---

## `text_list`

Generic text list collection.

| Property | Value |
|----------|-------|
| Status | ⚠️ Community |
| Type | Text Collection |
| Screen | Multiple |
| Source | Community Research |

**Description**

Used for dynamic text entries.

**Example**

```json
{
  "collection_name": "text_list",
  "binding_type": "collection"
}
```

---

# Unknown Collections

Collections below have been referenced during UI research but their exact purpose is not fully verified.

```json
{
  "unknown_collection_1": {
    "status": "Unknown",
    "notes": "Requires vanilla UI verification."
  },
  "unknown_collection_2": {
    "status": "Unknown",
    "notes": "Requires reverse engineering."
  }
}
```

---

# Experimental Collections

```json
{
  "experimental_collection_1": {
    "status": "Experimental",
    "notes": "Observed in testing environments."
  }
}
```

---

# JSON Structure

```json
{
  "collection_name": {
    "display_name": "",
    "description": "",
    "type": "",
    "screen": "",
    "status": "",
    "source": "",
    "example": {}
  }
}
```

---

# Entry Template

```markdown
## `collection_name`

Description.

| Property | Value |
|----------|-------|
| Status | |
| Type | |
| Screen | |
| Source | |

**Example**

```json
{
  "collection_name": "",
  "binding_type": "collection"
}
```
```

---

# Final Statistics

| Total | Confirmed | Community | Experimental | Unknown |
|-------:|----------:|----------:|-------------:|--------:|
| 47 | 16 | 25 | 1 | 5 |
