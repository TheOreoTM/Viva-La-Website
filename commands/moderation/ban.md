---
icon: triangle-right
label: ban
order: -40
---

# Ban

This command allows staff members to **ban** a [!badge variant="info" text="Member" icon="person"iconAlign="right"] from the server

||| :icon-codescan: Syntax
:icon-chevron-right:ban [!badge variant="danger" text="Member" icon="person" iconAlign="right"] [!badge variant="ghost" text="Duration" icon="clock" iconAlign="right"] [!badge variant="ghost" text="Reason" icon="note" iconAlign="right"]
|||

## Usage

| Command                                                         | Job                                                              |
| --------------------------------------------------------------- | ---------------------------------------------------------------- |
| :icon-chevron-right:**`ban @Oreo`**                             | Ban **@Oreo**                                                    |
| :icon-chevron-right:**`ban 600707283097485322`**                | Ban **ID**                                                       |
| :icon-chevron-right:**`ban @Foo 2d`**                           | Ban **@Foo** for **2 days**                                      |
| :icon-chevron-right:**`ban 600707283097485322 Raiding`**        | Ban **forever** with **reason** using **ID**                     |
| :icon-chevron-right:**`ban @Bar 7d Too many infractions`**      | Ban **@Bar** for **7 Days** with reason **Too many infractions** |
| :icon-chevron-right:**`ban 876186555910348880 2h Being toxic`** | Ban for **7 Days** with reason **Being toxic** using **ID**      |

!!!info Info
If no reason is specified **No reason** will be used in modlogs and as a ban reason
!!!
!!!warning Warning
The bot will not be able to ban members that arent in the server
!!!