# Git Submodules 101

```
git submodule add https://github.com/openai/openai-cookbook README/openai-cookbook
git submodule add https://github.com/open-webui/open-webui README/open-webui
git submodule add https://github.com/openai/openai-agents-python README/openai-agents-python
git submodule add https://github.com/crewAIInc/crewAI-examples README/crewAI-examples
git submodule add https://github.com/letta-ai/letta README/letta
git submodule add https://github.com/microsoft/AI-For-Beginners README/AI-For-Beginners
```

## If someone else updated the submodule pointer

> To see the current commits that are checked out for all your submodules:

`git submodule status`

> To update the code of your submodules:

`git submodule update`

---

## Making it easier for everyone

It is sometimes annoying if you forget to initiate and update your submodules. Fortunately, there are some tricks to make it easier:

`git clone --recurse-submodules`
    
This will clone a repository and also init / update any possible
submodules the repository has.

`git pull --recurse-submodules`
    
This will pull the main repository and also it's submodules.

And you can make it easier with aliases:

```
git config --global alias.clone-all 'clone --recurse-submodules'
git config --global alias.pull-all 'pull --recurse-submodules'
```