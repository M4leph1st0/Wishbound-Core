# Wishbound Core

Custom Foundry VTT extensions for the **Wishbound** campaign.

Built for:

- Foundry VTT v13
- ProjectFU v4.16.2

## Purpose

Wishbound Core is the central module for campaign-specific functionality that is not part of ProjectFU itself.

The goal is to keep all custom Wishbound features in one place instead of modifying ProjectFU directly or creating many small modules.

## Features

### Desire

Adds a Wishbound-specific `Desire` field to ProjectFU player characters.

- Editable in the **Notes** tab
- Displayed read-only in the **Overview** tab
- Stored directly on the Actor
- Only used for actors of type `character`

Data path:

```js
flags.wishbound-core.desire
