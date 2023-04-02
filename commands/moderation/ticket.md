---
icon: triangle-right
label: Ticket
order: -300
author:
  - name: Oreo ™
    avatar: ../../static/oreo-avatar.png
---

# Ticket [!badge variant="dark" icon="../../static/staff-dark.png" text="Staff" iconAlign="right" margin="0 0 0 8" size="s"]

This command allows staff members to un/block a [!badge variant="info" text="Member" icon="person"iconAlign="right"] from tickets

||| :icon-codescan: Syntax
:icon-chevron-right:ticket [!badge text="Subcommand" icon="git-merge" iconAlign="right"] [!badge variant="danger" text="Member" icon="person" iconAlign="right"]
|||

### Subcommands

=== Block
Disallow a member from creating any more tickets in the server. This can also be done inside tickets using the ticket control panel.
=== Unblock
Allow a member to create tickets in the server (if already blocked)
===

## Usage

| Command                                                     | Job                                   |
| ----------------------------------------------------------- | ------------------------------------- |
| :icon-chevron-right:**`ticket block @TMS`**                 | **Block** **@TMS** from tickets       |
| :icon-chevron-right:**`ticket unblock 600707283097485322`** | **Unblock** from tickets using **ID** |
