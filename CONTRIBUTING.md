# Bullet Buddy: Contributing

Before reading, please familiarise yourself with the project via [the
documentation](./DOCUMENTATION.md).

**NOTE**:

The project is not currently accepting open source contributions. If you would
like to get in touch about possibly collaborating on the project in any way,
please privatley contact the repository owner.


# Contents

- [1.0 Git Project Info](#11-git-project-info)
  - [1.1 Branching Strategy](#11-branching-strategy)
  - [1.2 Install and Run](#12-install-and-run)
- [2.0 Trello Board](#20-trello-board)
  - [2.1 Trello Process](#21-trello-process)
- [3.0 Designs](#30-designs)

---

# 1.0 Git Project Info

## 1.1 Branching Strategy

### Branches

`master`: The main branch that features, bug fixes and documentation updates
will be merged into.

### Creating a branch

Branches should be named by their type, following they're Trello ticket number,
and a few words describing that ticket.

Example: `feature/BB-92-example-branch-name`

### Branch Types

- `feature`: Code that contains new features or functionality to project code base.
- `task`: Changes to already existing components or functionality.
- `fix`: Fixes a broken feature or piece of functionality.

### Committing Code

Commits should be named with their Trello ticket number, as well as a short
description of what was achieved in this commit.

e.g. `BB-94: Example git commit`

If the commit is small enough that it isn't worth a Trello Card and Pull Request
(fixing a README typo, removing old info/files), label it a PATCH and commit 
directly to `master`

e.g. `PATCH: Removing incorrect README info`

### Merging Code

To merge your branch, open a pull request on Github and change the title of the
pull request to match that of the Trello ticket, with square brackets around the
ticket number, and regular brackets around the type of card (feature/task/fix).

e.g. `[BB-92] (Feature) Example Pull Request Name`

When code has been reviewed (if necessary) select the option 'Squash and Merge'

[<-- Back to Contents](#contents)

---

# 1.2 Install and Run

Please see [section 2.0 of the documentation](./DOCUMENTATION.md#20-install-and-run)
for instructions.

[<-- Back to Contents](#contents)

---

# 2.0 Trello Board

Link to Bullet Buddy Trello Board: https://trello.com/b/DnCjHNmi

## 2.1 Trello Process

In our Trello we currently have 5 columns: Backlog Refinement, ToDo, In
Progress, PR/QA, Done, Cancelled.

**Backlog Refinement**: New cards are created here. When creating a new card, you must label it with the
project initials, the card number, and a short description of what the card is
for.

e.g. BB-18: Update README with Trello Process

A full description must be added to the card as well as a label before it can be
moved to the ToDo column for a team member to pick up and complete.

**To Do**: Card is ready to be picked up but has not yet been.

**In Progress**: Branch has been opened (if required) and a member is working on that ticket.

**Review**: Requires a peer code review, and is currently in a  pull request from feature
branch to dev. (Not always a necessary step)

**Done**: Card has been completed and merged into `master` branch.

**Cancelled**: Card has been cancelled and is no longer a ToDo. A comment must
be left on the card detailing reasons for its cancellation.


[<-- Back to Contents](#contents)

---

# 3.0 Designs

Designs and drafts are created on Figma, link here:
https://www.figma.com/file/Qlxt0d7Bmdw1k5NCU0rdJPZH/Bullet-Buddy?node-id=24%3A8

Contact the repository owner if you would like to contribute to the UI.

---

# Other Documents

- [README](./README.md)
- [Documentation](DOCUMENTATION.md)