---
icon: triangle-right
label: lock
order: -200
author:
  - name: Oreo ™
    avatar: ../../static/oreo-avatar.png
---

# Lock

This command allows staff members to **lock** a [!badge variant="info" text="Channel" icon="hash" iconAlign="right"]

||| :icon-codescan: Syntax
:icon-chevron-right:lock [!badge variant="danger" text="Channel" icon="hash" iconAlign="right"] [!badge variant="ghost" text="Duration" icon="clock" iconAlign="right"] [!badge variant="ghost" text="Reason" icon="note" iconAlign="right"]
|||

## Usage

| Command                                                                         | Job                                                                                  |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| :icon-chevron-right:**`lock #general ongoing raid`**                            | Lock **#general** with reason **ongoing raid**                                       |
| :icon-chevron-right:**`lock #memes 2m`**                                        | Lock **#memes** for **2 Minutes**                                                    |
| :icon-chevron-right:**`lock #general-2 24h everyone go to #general`**           | Lock **#general** for **24 Hours** with reason **everyone go to #general**           |
| :icon-chevron-right:**`lock 907414829445283870 ongoing raid`**                  | Lock channel with reason **ongoing raid** using **ID**                               |
| :icon-chevron-right:**`lock 918705444132896778 2m`**                            | Lock channel for **2 Minutes** using **ID**                                          |
| :icon-chevron-right:**`lock 519754831393456129 24h everyone go to #general-2`** | Lock channel for **24 Hours** with reason **everyone go to #general-2** using **ID** |

!!!info info
If no reason is specified **No reason** will be used
!!!
