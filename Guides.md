# Development Guides

## Development Flow

There is a typical process of working on a task:

- Pick an issue.
- Clarify requirements if needed with a team.
- In IDE firstly checkout to the “origin/main” branch and pull and merge any updates from the remote repository.
- Create a new branch from the “origin/main” following the naming conventions: 
	- `feature/1-name-of-the-task`, where `1` refers to a number of your issue. Instead of `feature` it might be `fix`, `build`, `docs` depending on the type of a task.
- Write code and tests.
- For backend - run auto tests with IDE, and run tests with GitBash command.
- For backend - test changes with Postman. 
- Test changes by running front and back.
- Commit changes, in the commit’s description copy the name and number of your issue. 
- Create a pull request. Ensure that GitHub Actions are passed. - If not passed, research and fix a cause of the failure.
- Request review from another developer.
- After review is completed, inform the Project manager. PM will merge your pull request to the main branch.
- After merging, return to IDE and checkout to the “origin/main” branch, pull and merge changes from the remote repository.
