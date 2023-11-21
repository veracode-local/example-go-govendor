# [:] Example Go project using Govendor.

An example Go project using Govendor package manager to demonstrate [SourceClear](https://www.sourceclear.com) scans.

## Install and activate SourceClear
Follow the instructions under the section "Setup and Configuration" in https://www.sourceclear.com/docs/command-line-interface/ to install and activate our SourceClear agent.

## Scan this project
There are 2 ways to scan this project.

### 1. Using url option
`SRCCLR_FORCE_GO_INSTALL=true srcclr scan --url https://github.com/srcclr/example-go-govendor`

### 2. On local path
```
1. git clone https://github.com/srcclr/example-go-govendor/ $GOPATH/src/github.com/srcclr/example-go-govendor/
2. srcclr scan $GOPATH/src/github.com/srcclr/example-go-govendor/
```

test 12345
