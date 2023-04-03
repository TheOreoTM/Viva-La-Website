---
icon: triangle-right
label: Stats
order: -10
author:
  - name: Oreo ™
    avatar: ../../static/oreo-avatar.png
---

# Suggest

View message stats of a [!badge variant="info" text="Member" icon="person" iconAlign="right"]/[!badge variant="info" text="Channel" icon="hash" iconAlign="right"]/[!badge variant="info" text="Role" icon="mention" iconAlign="right"]/[!badge variant="info" text="Server" icon="organization" iconAlign="right"] or the [!badge variant="info" text="Author" icon="person" iconAlign="right"]

||| :icon-codescan: Syntax
:icon-chevron-right:stats [!badge variant="danger" text="Subcommand" icon="git-merge" iconAlign="right"] [!badge variant="danger" icon="search" iconAlign="right" text="Target"]
|||

## Subcommands

==- Me - [!badge variant="info" text="Author" icon="person" iconAlign="right" size='xs']
Get stats about the [!badge variant="info" text="Author" icon="person" iconAlign="right"]
||| :icon-codescan: Syntax
:icon-chevron-right:stats [!badge variant="success" text="me"]
|||

==- User - [!badge variant="info" text="Member" icon="person" iconAlign="right" size='xs']
Get stats about a [!badge variant="info" text="Member" icon="person" iconAlign="right"]
||| :icon-codescan: Syntax
:icon-chevron-right:stats [!badge variant="success" text="user"] [!badge variant="ghost" text="Member" icon="person" iconAlign="right"]
|||

!!!info Info
If no [!badge variant="info" text="Member" icon="person" iconAlign="right"] is specified, it will default to the [!badge variant="info" text="Author" icon="person" iconAlign="right"]
!!!

==- Role - [!badge variant="info" text="Role" icon="mention" iconAlign="right" size='xs']
Get stats about a [!badge variant="info" text="Role" icon="mention" iconAlign="right"]
||| :icon-codescan: Syntax
:icon-chevron-right:stats [!badge variant="success" text="role"] [!badge variant="danger" text="Role" icon="mention" iconAlign="right"]
|||

==- Channel - [!badge variant="info" text="Channel" icon="hash" iconAlign="right" size='xs']
Get stats about a [!badge variant="info" text="Channel" icon="hash" iconAlign="right"]
||| :icon-codescan: Syntax
:icon-chevron-right:stats [!badge variant="success" text="channel"] [!badge variant="ghost" text="Channel" icon="hash" iconAlign="right"]
|||

!!!info Info
If no [!badge variant="info" text="Channel" icon="hash" iconAlign="right"] is specified, it will default to the [!badge variant="info" text="Channel" icon="hash" iconAlign="right"] **the command was ran in.**
!!!
==- Top - [!badge variant="info" text="Server" icon="organization" iconAlign="right" size='xs']
Get stats about the top 5 users and top 5 channels in the [!badge variant="info" text="Server" icon="organization" iconAlign="right"]
||| :icon-codescan: Syntax
:icon-chevron-right:stats [!badge variant="success" text="top"]
|||

==-

## Usage

| Command                                                    | Job                                      |
| ---------------------------------------------------------- | ---------------------------------------- |
| :icon-chevron-right:**`stats me`**                         | Get stats about **Command Author**       |
| :icon-chevron-right:**`stats user @Icarus`**               | Get **user** stats about **@Icarus**     |
| :icon-chevron-right:**`stats user 508552375397515285`**    | Get **user** stats using **ID**          |
| :icon-chevron-right:**`stats role @Staff`**                | Get **role** stats about **@Staff**      |
| :icon-chevron-right:**`stats role 634605860206804992`**    | Get **role** stats using **ID**          |
| :icon-chevron-right:**`stats channel #general`**           | Get **channel** stats about **#general** |
| :icon-chevron-right:**`stats channel 856722573576765450`** | Get **channel** stats using **ID**       |
| :icon-chevron-right:**`stats top`**                        | Get **top** stats                        |
