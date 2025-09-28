# OhMyTasks
A simple application for keeping track of tasks.
I made this repo for testing Copilot's integration with MCP servers.
After setting it all up, Copilot was able to read the open issue and write code to solve it on its own. The MVC UI wasn't great, but it did technically solve the issue.

## Observations
MCP servers let LLMs call functions that give it real-time context. 
From my tests, I noticed that this keeps hallucinations to a minimum (is there a way to prove it won't ever hallucinate?) and keeps the LLM up to date on information that would otherwise be completely out of its scope, such as the server's current time or a GitHub repo's latest issues.
