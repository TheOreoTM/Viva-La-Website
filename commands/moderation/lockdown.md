---
icon: triangle-right
label: Lock
order: -210
author:
  - name: Oreo ™
    avatar: ../../static/oreo-avatar.png
---

# Lockdown [!badge variant="dark" icon="../../static/staff-dark.png" text="Staff" iconAlign="right" margin="0 0 0 8" size="s"]

This command allows staff members to **lockdown** a [!badge variant="info" text="Server" icon="organization" iconAlign="right"]

||| :icon-codescan: Syntax
:icon-chevron-right:lockdown [!badge variant="ghost" text="Duration" icon="clock" iconAlign="right"] [!badge variant="ghost" text="Reason" icon="note" iconAlign="right"]
|||

## Usage

| Command                                              | Job                                                                |
| ---------------------------------------------------- | ------------------------------------------------------------------ |
| :icon-chevron-right:**`lockdown`**                   | Lockdown **server**                                                |
| :icon-chevron-right:**`lockdown ongoing raid`**      | Lockdown **server** with reason **ongoing raid**                   |
| :icon-chevron-right:**`lockdown 2m`**                | Lockdown **server** for **2 Minutes**                              |
| :icon-chevron-right:**`lockdown 24h Staff holiday`** | Lockdown **server** for **24 Hours** with reason **Staff holiday** |

!!!danger Danger
The bot is not able to understand whether the channel previously had a permission set to [!button variant="secondary" text="Inherit" icon="skip" size="xs"], its only able to see if the permission was [!button variant="success" text="Allowed" icon="check-circle" size="xs"] or [!button variant="danger" text="Denied" icon="x-circle" size="xs"]. Therefore, when the bot sets the permissions back after the [lockdown is lifted](./lockdown.md#lockdown-lift) the bot might set a permission to [!button variant="success" text="Allowed" icon="check-circle" size="xs"] instead of [!button variant="secondary" text="Inherit" icon="skip" size="xs"], but [!button variant="danger" text="Denied" icon="x-circle" size="xs"] will be set to [!button variant="danger" text="Denied" icon="x-circle" size="xs"]
!!!

## Lockdown lift

You can remove a lockdown by typing the following commands

|:icon-chevron-right:**`lockdown lift`**|
|:icon-chevron-right:**`lockdown clear`**|
|:icon-chevron-right:**`lockdown clear`**|
|:icon-chevron-right:**`lockdown remove`**|
|:icon-chevron-right:**`lockdown end`**|
