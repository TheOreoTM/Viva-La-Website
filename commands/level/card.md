---
icon: triangle-right
label: card
order: -10
author:
  - name: Oreo ™
    avatar: ../../static/oreo-avatar.png
---

# Card

A command to customize your **rankcard**.

||| :icon-codescan: Syntax
:icon-chevron-right:card [!badge variant="danger" text="Subcommand Group" icon="workflow" iconAlign="right"] [!badge variant="danger" text="Subcommand" icon="git-merge" iconAlign="right"]\*
|||

<font size='2rem'>\*[!badge variant="info" text="Subcommand" icon="git-merge" iconAlign="right" size='xs'] is not required if the [!badge variant="info" text="Subcommand Group" icon="workflow" iconAlign="right" size='xs'] is `Reset`</font>

+++ Color

### Subcommands

==- Bg
Change your **background color**

||| :icon-codescan: Syntax
:icon-chevron-right:card [!badge variant="success" text="color" iconAlign="right" icon="typography"] [!badge variant="success" text="bg" iconAlign="right" icon="typography"] [!badge variant="danger" text="Hex Code" iconAlign="right" icon="paintbrush"]
|||
==- Font
Change your **font color**

||| :icon-codescan: Syntax
:icon-chevron-right:card [!badge variant="success" text="color" iconAlign="right" icon="typography"] [!badge variant="success" text="font" iconAlign="right" icon="typography"] [!badge variant="danger" text="Hex Code" iconAlign="right" icon="paintbrush"]
|||
==- Bar
Change your **progress bar color**

||| :icon-codescan: Syntax
:icon-chevron-right:card [!badge variant="success" text="color" iconAlign="right" icon="typography"] [!badge variant="success" text="bar" iconAlign="right" icon="typography"] [!badge variant="danger" text="Hex Code" iconAlign="right" icon="paintbrush"]
|||
==-
+++ Reset
Reset your rankcard to default

Change your background color

||| :icon-codescan: Syntax
:icon-chevron-right:card [!badge variant="success" text="color" iconAlign="right" icon="typography"] [!badge variant="danger" text="reset" iconAlign="right" icon="typography"]
|||
+++

## Usage

| Command                                           | Job                                            |
| ------------------------------------------------- | ---------------------------------------------- |
| :icon-chevron-right:**`card color bg #00ff00`**   | Set card **bg color** to **#00ff00**           |
| :icon-chevron-right:**`card color font #0c0c0c`** | Set card **font color** to **#0c0c0c**         |
| :icon-chevron-right:**`card color bar #00ffff`**  | Set card **progress bar color** to **#00ffff** |
| :icon-chevron-right:**`card reset`**              | Reset card                                     |
