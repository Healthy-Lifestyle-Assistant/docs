# Development Guides

[Development Flow](#development-flow)  
[Working with Proposals](#working-with-proposals)  


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

## Working with Proposals

### Difference between Ideas and Proposals

**Ideas** are abstract concepts. 

**Proposals** are ideas + benefits for the project + ability to implement it + responsibility.

### What to Take into Account about Your Proposals

- Is it beneficial for the project? So it’s important to argue your proposals within the team and list benefits for the projects.
- Do you have expertise and enough time and motivation to implement your proposals? As an initiator you will be primarily responsible for an implementation of your proposals.
- What will it cost for other team members? Do we need to refactor and change much of what we already have?

### Typical Workflow on Proposals

- Schedule a call and discuss your proposals with the team. Explain your answers to the questions above.
- Create a separate branch, implement your proposals, test it, make a pull request.
- After successful review of other team members, the Project manager will merge your branch.
- To work on proposals for UI porotypes, use Figma.

### Backlog

The proposals team agreed with and which we don’t have time to implement are included in “backlog.md” in “docs” repository.
