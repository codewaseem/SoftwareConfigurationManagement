## Avoid Committing Broken Code

- Use the Right Configuration
- Do Not Use Broken Code
- Validate Before Committing

### Use the Right Configuration

The right baseline on the right codeline.

Typically, you will be working on current development from the tip of the mainline, but occasionally you might need to fix a bug on a release that it is maintained on its own codeline.

### Do Not Use Broken Code

Retrieve the configuration from the vc repo only.

Confirm it builds and passes the tests.

In the continuous integration context, "known-good" means that the revision you are working on has passed all automated tests on your CI server.

### Validate Before Committing

First, validate the associated unit tests are passing.

If necessary, you might want to do a private build to detect integration errors before they affect other developers.

Run smoke tests.

Run unit tests.

Create a deployable artifact.
