## Step 3: Isolate to Control Changes

- Work in Private Workspace
- Branch Out When Necessary
- Stay in Sync with the Codeline

### Work in Private Workspace

In distributed VCS, this can be the local repo on your hard-disk. Your private should have all the dependencies you need to work independently, including the following:

- Souce code
- Build tools
- Dependencies
- Configuration files

### Branching

Sometimes, one or more people working on part of a codeline need to make disruptive changes that you would prefer to delay adding to the mainline until your work is complete.

You still, however, need to commit and share changes on that part of the codeline as you go. In other words, you need to work in parallel--on a separate branch--isolated from the rest of the development work.

Once the work is complete, the changes should be merged into the ancestor codeline (master/mainline) from where the branch originated.

Avoid branching for every single feature, or team member. The more branches you have the more integrations risk you get.

#### Two good reasons to branch

1. ##### Task Branch

   A task branch should be short-lived and used only when its benefit outweighs the associated overhead of merging and keeping track of the branch.

2. ##### Release Branches

   Long-lived branches are reserved for releases where you want to fix problems found in production.

   The fixes introduced into this branch, called a release line, are eventually merged into the mainline.

   Critical defect fixes might also be merged from the mainline into release branches.

### Stay in Sync

**The Need to Balance Isolation and Integration.**

Although working in isolation has its benefits, these benefits decrease rapidly the longer you wait to synchronize with other's work.

This is especially important when you have been working on a task branch or when, despite working on a single codeline, you have been delaying integration for too long.

As other team members commit their changes to the codeline, you should update your workspace frequently to minimize future integration problems.

Check for changes several times throughout the day and again before committing your changes.
