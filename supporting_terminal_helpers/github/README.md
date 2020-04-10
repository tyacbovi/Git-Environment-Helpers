# Git terminal shortcuts

## Description
For maximizing productivity while using GitHub, there is a need to utilize more of it's features via the terminal.
That could be accomplished via using [hub](https://github.com/github/hub), which has a couple of cool features like:
* `hub ci-status` - Display status of GitHub checks for a commit, very useful for monitoring your CI status for example in a CI board.
* `hub browse` - Open a GitHub repository on the current branch in your default web browser.
* `hub pull-request` + `hub pr`- Create and manage a GitHub Pull Request, this could be also supercharge with aliasing those commands together in a new command `pr` interface.
* `hub issue` - Manage GitHub Issues for the current repository.
* `hub release` - Manage GitHub Releases for the current repository.

## Further customizing
* `pr` - Create and manage a GitHub Pull Request via one interface by supercharge `hub pull-request` + `hub pr`, which could be done by aliasing that command and using a bash function for gluing them with this [guide](https://linuxize.com/post/how-to-create-bash-aliases/#creating-bash-aliases-with-arguments-bash-functions).
* `goto` - Aliasing the `hub browse` command for a faster way to jump into your browser.
