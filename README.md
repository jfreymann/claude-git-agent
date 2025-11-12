# Claude Git agent - WIP
Simple agent for managing git commits. This agent will validate any security concers, craft commit messages based on the work done and commit said changes to the projects remote repo. 

## Requirements
If you want autonomous commits, you need to set up ssh keys and allow the agent access to the repo. 

## Addons
I also give these directions to the agent to ensure that I can execute "push code" without interruption and there are no unnecessary claude code attributes added to the commit messages. 

``` bash
Do not include the Claude Code attribution footer or Co-Authored-By line in commit messages. I'll create clean, standard commit messages without any Claude-related references.
```

``` bash
Also, when I type "push code" without quotes I want you to execute all the necessary functions of the git-commit-writer agent including push to the remote repository.
```
