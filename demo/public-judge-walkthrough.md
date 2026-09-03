# Public judge walkthrough

This repository holds synthetic examples for [Repo Board](https://github.com/zac/webmcp-repo-board), a real-time GitHub task board for people and browser-native agents.

Open the [public Repo Board demo](https://webmcp-repo-board.zacwhite.workers.dev/boards/zac/test-repo-board) to inspect the workflow without signing in.

The board keeps one example in each column:

- Todo has an unplanned request.
- Ready has a human-approved implementation plan.
- In progress has a durable agent assignment and reported progress.
- In PR follows an open GitHub pull request.
- Done follows a merged pull request.

Anonymous visitors can read the board and inspect tasks through WebMCP. Creating tasks or changing workflow state requires GitHub authentication and repository permission.
