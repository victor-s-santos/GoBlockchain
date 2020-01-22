# GoBlockchain

# How To Run(Linux)

* ## First, Installing and Configuring Go

`-Go to oficial Golang page(https://golang.org/dl/);` 

`-Download the correct linux version go_installer;`

`-In the installer directory, run: sudo tar -xzvf go_installer.tar.gz -C /usr/local/`

`Wait the instalation be done.`

* ## Second, Create a Workspace:

`-In home directory:`

`-run: mkdir go && cd go && mkdir src pkg bin`

* ### Config the env:

`-In the home directory, run gedit .profile --and add the following lines at the end of the file:`

`export GOPATH=~/go`

`export PATH=$PATH:/usr/local/go/bin:$GOPATH/bin`;

`-save the changes, and run source .profile, "to commit" this changes;`

* ## To Create and Install new go application:

`-Following a pattern adopted by go, build the following directory scheme:`

`- /go/src/github.com/your-account-nickname/newprogramm`

`-Create a file.go`

`-To run this file: go run file.go;`

`-To install the file as a programm, run: go install .`




