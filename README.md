# Raccoons CI CD Code Review Template

## Summary
This is the repository with the configuration and instructions on how to add automatic code review for pull requests in GitHub. Please follow next instructions to implement this in your repository.

Automatic code review is performed via Cursor CLI Agent.

## Installation

### Admin preparations
1. Open Cursor Integrations page https://cursor.com/dashboard?tab=integrations.
2. Click on `New User API Key` and create new API key, copy and save it after that.
3. As owner of repository - go to Repository Settings -> Secrets and variables -> Actions
4. Click on `New repository secret` and fill Name with `CURSOR_API_KEY` and Secret with the API Key of Cursor you saved

### Development preparations
1. Clone this repository: `git clone https://github.com/raccoons-games/Raccoons.CI.CodeReview.git`
2. Copy all the contents in folder `root` and paste in your repository root (folders might be hidden by your OS, make hidden files visible)
3. Commit it. And that's it - you will have review for next PR :)