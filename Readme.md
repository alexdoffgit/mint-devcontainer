# Mint VSCode Remote Container

This is a repository integrating mint with vscode devcontainer,
fork of https://github.com/mint-lang/mint-docker

# What did i do

I move all the content of workspace into parent folder. I then remove docker-compose.yml and Makefile.
And then i add .devcontainer/devcontainer.json

there is not much in devcontainer.json, i only give it name, the docker image mintlang/mint,
expose port 3000(mint default port), add mint-vscode extensions, and make default
shell to bash.

you might want to customize devcontainer.json according to your liking and need