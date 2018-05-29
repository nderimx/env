## Install Script for Go Development

The script is meant for a debian based os

#### Steps

update os
install latest version of go
set environment variables
install vs code
install vs code extensions (delve, gitlense, goimports, Go, markdownlint)
install git
install gotorch
install errcheck



#### Usage

`code .`                                            Open a dir with vs code 
`file <executable>`                                 Check what executable you compiled
`GOOS=<OS> go build`                                Cross-Compile (OS options: windows, linux, darwin)
`go install`                                        Puts the executable in your $GOBIN
`go get <repository>`                               Downloads in $GOPATH and install in $GOBIN
`gofmt -w <go_file>`                                Make code pretty
`go list -f '{{ join .Imports "\n" }}' <package>`   List of Dependencies
`go list -f '{{ .Doc }}' <empty/package>`           In terminal Documentation
`go doc <empty/package> <empty/function/struct>`    Full documentation in Terminal
`godoc -http :6060`                                 All documentations in html




### The Second Script is meant to install everything else needed to have fun while working

Spotify
VLC
Multitasking Gestures