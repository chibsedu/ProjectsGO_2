# Boilerplate

## Creer dans github.com un repository public sans Readme.md avec le nom: ProjectGO_2

$ cd go/src/github.com/chibsedu
$ mkdir -v ProjectsGO_2
$ cd ProjectsGO_2
$ echo "ProjectsGO_2" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M main
$ git remote add origin <https://github.com/chibsedu/ProjectsGO_2.git>
$ mkdir -v second
$ cd second/
$ go mod init ProjectGO_2/second

## Creer dans VSCode file: main.go

Pusher from VSCode
$ go run main.go
