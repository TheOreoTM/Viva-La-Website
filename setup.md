---
label: 'Setup'
icon: checklist
order: 10000
---

# Setup

Gir-Unit includes a few modules and systems that you can setup individually.

==- Modules

- Moderation
- Welcome
- Leveling
- Level-Roles
- Ticket
- Suggestion
- Ignored-Channels
- ~~Party~~
  ==- Systems
- Automod
  ==-

---

## Setting up a module

To setup a module just run the command `/setup <module-name> <parameters>`

!!!danger Danger
Moderation commands will only work for admins and banned words wont be filtered if Moderation is not setup for the server
!!!

---

## Setting up a system

As of right now the only system in the bot is Automod. However, automod has various sub-systems that you can customize to your liking.
==- Sub-Systems

- Textwall
- World Limit
- New Line
- Banned words
- Invite Links
- Mass Mention
- Spam
- Quick Spam
  ==-

Each sub-system has the same options but they can function differently for the sub-system. To get more info about the effects of an option for a sub-system use the `/automod help` command

You can setup a logging channel for automod action by using the `/automod log-channel` command
