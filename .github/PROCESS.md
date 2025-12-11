# Process

This document is to describe the internal process that the LinkUp team uses for issue management, project planning and the development workflow.

## Table of contents
 * [Project Boards](#project-boards)
 * [Managing Issues](#managing-issues)
 * [Workflow](#workflow)
 * [Environments](#environments)
 * [Releasing](#releasing)

## Project Boards

The project boards are located under the `Projects` tab in GitHub. It contains issues or pull requests related to the project. You can have many boards for different sprints/milestones. The each board includes 4 main columns.

### To Do

Contains issues that we believe we can accomplish in the current sprint. Issues should be manually moved to this column when we have our sprint planning meeting.

### In Progress

Issues and pull requests that are currently being worked on. Issues should be manually moved to this column and assigned to yourself when you begin working on them. Pull requests are automatically added to this column when added to the project board.

### Needs Review

Issues and pull requests that need review. Pull requests will automatically move here when a reviewer requests changes, or it no longer meets the minimum number of required approving reviews.

### Done

Issues and pull requests that are completed. Issues will automatically move here when they are closed. Pull requests will automatically moved here when they are merged or closed with unmerged commits.


## Managing Issues

### Issues

Issue can be created by anyone who have access to repository. When create issue you will see default template.

If the developer wants to add a new feature, or he found some bug then he creates a new issue and assigns somebody.

If QA found some bug or he suggest to add some feature to a project, he creates a new issue in GitHub repository. QA should set label and assign someone who will do it.

### Labels

We use 8 default labels which added to the repository when start developing.

- `bug` - Something isn't working
- `docs` - Improvements or additions to documentation
- `question` - Indicates that an issue or pull request needs more information
- `production` - Indicates that an issue happened on production
- `staging` - Indicates that an issue happened on staging
- `on hold` - Needs discuss or approvement
- `next phase` - Approved but will implement in the future
- `on testing` - Issue fixed but needs additional testing

### Projects

Issue can be related to GitHub projects. You can set it during issue creation.

### Milestone

We are working with small milestones for one or two or more weeks. So, when you add issue you can choose the current milestone or create a new one.

## Workflow

Follow [workflow process](PROCESS_WORKFLOW.md) instructions

## Environments

Follow [environments process](PROCESS_ENVIRONMENTS.md) instructions

## Releasing

Follow [releasing process](PROCESS_RELEASING.md) instructions
