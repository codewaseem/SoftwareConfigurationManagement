## Keep "Everything" in Version Control

- Use the VC repo
- Capture the evolution in codelines
- Indentify Configurations or Baselines
- Use Meaningful Commit Messages

### The VC Repo

You should store all your work related to the product in the vc repo.
Things like source code, tests, database scripts, build and deployment scripts, documentations, libraries, configuration files, the compiler, and other tools.

"If it is not in the repository, it does not exist."

### Capture The Evolution in Codelines

Codelines is an evolution line of the software where at each point the software is complete, correct, and consistent.

A codeline can be a master branch in the git repo.

Ideally you should have one codeline to represent the state of the working, complete, correct software. Anything that is pushed to the master branch should be complete, correct and consistent.

You can branch out when working on refactoring, fixing-bugs, adding a new feature and once the work is complete it should be merged to the master and the branch should be deleted.

Branches allows team members to work parallelly. But don't have too many of them.

### Identify Configurations

A configuration is a snapshot of the system in a given point in time. Identifying configuration is knowing the known good state of a system so that we can easily refer back to it when necessary.

#### Labels and Tags

Assign label or tags to the state of the codeline at the time. These labels allow you to return to that specific point in time in the codeline's evolution.

#### Meaningful Commit Messages

Focus on `why` the change was made. Because the rest of the details like what, when, who are tracked by the vcs.

If your were to describe a change as "I did x because ..." you commit message should be what comes after "because".
