## Integrate and Build Often

- Commit Frequently to the Mainline
- Build Often

To maintain the repo as the single source of truth, you need to commit your changes regulary to make them available to other team members.

You should commit to the mainline at least once a day.

#### Changeset

The group of changes, known as changeset, is committed entirely or it is not committed at all.

#### Commit Frequently

- Easier to roll back
- Reduce number of changes you need to keep track of
- Reduction of change conflicts

#### Build Often

An integration build runs automatically when changes are detected in the codeline.

#### Steps in the integration build

1. Update the source in an integration workspace

2. Builds the code

3. Runs unit, smoke, and integration tests

4. Perfroms static analysis on the source code

This process should be automated and quick, and failures should be addressed immediately.
