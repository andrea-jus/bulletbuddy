# Bullet Journal

This is a PWA based on the analog organization system Bullet Journal. The
app aims to take the systems combination of calender, to-do list and notebook,
and emulate it's ease of use and handy method of 'Rapid Logging' in to a digital
format, that doesn't adversely affect the speed of using Bullet Journal, and
preserves the framework and it's modular system while still being customisable.

<div id="contents" />

# Contents

- [1.0 Tech Stack](#1.0)
- [2.0 System Design](#2.0)
- [3.0 Github Project Info](#3.0)
  - [3.1 Branching Strategy](#3.1)
  - [3.2 Install & Run](#3.2)
- [4.0 Trello Board](#4.0)
  - [4.1 Trello Process](#4.1)

---

<div id="1.0" />

# 1.0 Tech Stack

- [Nuxt.js (Vue.js Framework)](https://nuxtjs.org/guide)
- [Vue.js (Javascript SPA Framework)](https://vuejs.org/)
- [Vuex (Vue.js state management)](https://vuex.vuejs.org/en/)
- [SASS (Compiled CSS Language)](http://sass-lang.com/)
- [ESLint (Airbnb Javascript Style Guide)](https://github.com/airbnb/javascript)

[<-- Back to Contents](#contents)

---

<div id="2.0" />

# 2.0 System Design

[<-- Back to Contents](#contents)

---

<div id="3.0" />

# 3.0 Github Project Info

<div id="3.1" />

## 3.1 Branching Strategy

### Branches

`master`: The main branch that features, bug fixes and documentation updates
will be merged into.

### Creating a branch

Branches should be named by their type, following they're Trello ticket number,
and a few words describing that ticket.

Example: `feature/BU-92-example-branch-name`

### Branch Types

- `feature`: Code that contains new features or functionality to project code base.
- `task`: Changes to already existing components or functionality.
- `fix`: Fixes a broken feature or piece of functionality.

### Committing Code

Commits should be named with their Trello ticket number, as well as a short
description of what was achieved in this commit.

If a ticket is small enough of a task (like editing some docs/fixing typos etc)
one can commit straight to dev instead of opening a pull request.

e.g. `BU-94: Example git commit`

If the commit is small enough that it isn't worth a Trello Card and Pull Request
(fixing a README typo, removing old info/files), label it a PATCH and commit 
directly to dev.

e.g. `PATCH: Removing incorrect README info`

### Merging Code

To merge your branch, open a pull request on Github and change the title of the
pull request to match that of the Trello ticket, with square brackets around the
ticket number, and regular brackets around the type of card (feature/task/fix).

e.g. `[BU-92] (Feature) Example Pull Request Name`

When code has been reviewed (if necessary) select the option 'Squash and Merge'

[<-- Back to Contents](#contents)

---

<div id="3.2" />

# 3.2 Install & Run

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn run dev

# build for production and launch server
$ yarn run build
$ yarn start

# generate static project
$ yarn run generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).

[<-- Back to Contents](#contents)

---

<div id="4.0" />

# 4.0 Trello Board

Link to Bullet Journal Trello Board: https://trello.com/b/DnCjHNmi

<div id="4.1" />

## 4.1 Trello Process

In our Trello we currently have 5 columns: Backlog Refinement, ToDo, In
Progress, PR/QA, Done, Cancelled.

**Backlog Refinement**: New cards are created here. When creating a new card, you must label it with the
project initials, the card number, and a short description of what the card is
for.

e.g. BU-18: Update README with Trello Process

A full description must be added to the card as well as a label before it can be
moved to the ToDo column for a team member to pick up and complete.

**ToDo**: Card is ready to be picked up but has not yet been.

**In Progress**: Branch has been opened (if required) and a member is working on that ticket.

**PR/QA**: Requires a peer code review, and is currently in a  pull request from feature
branch to dev. (Not always a necessary step)

**Done**: Card has been completed and merged into `dev` branch.

**Cancelled**: Card has been cancelled and is no longer a ToDo. A comment must
be left on the card detailing reasons for its cancellation.


[<-- Back to Contents](#contents)

---
