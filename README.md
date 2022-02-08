# Hello world script

A simple script showing the basic Hello World! example for the Nextflow framework.

This fork includes a devcontainer configuration which will create a GitHub Codespace for Nextflow development!

Devcontainer specs:
- [DevContainer config](.devcontainer/devcontainer.json)
- [Dockerfile](.devcontainer/Dockerfile)

# Getting started
- Create a new repo in Github using this [template](https://github.com/pjirsa/hello/generate).
- Open the repo in Codespaces
- Once Codespace is open, enter this into the terminal:
`~/nextflow main.nf`

expected output:
```
N E X T F L O W  ~  version 21.10.6
Launching `main.nf` [fervent_ardinghelli] - revision: d3a65fa206
executor >  local (4)
[3c/886523] process > sayHello (4) [100%] 4 of 4 ✔
Hello world!

Ciao world!

Bonjour world!

Hola world!
```
