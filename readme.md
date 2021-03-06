![awesome go lang](https://github.frapsoft.com/top/awesome-go.png?v=101)

# Awesome Go Lang

_List with awesome Go resources. Work in progress ..._

## IDE Extensions

### Vim

- [gocode](https://github.com/nsf/gocode) - Go autocompletion daemon
- [syntastic](https://github.com/vim-syntastic/syntastic) - Syntax checking
- [tagbar](https://github.com/majutsushi/tagbar) -  displays tags in a window, ordered by scope
- [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim compiler plugin for Go
- [vim-go-extra](https://github.com/vim-jp/vim-go-extra) - Extra plugin for golang
- [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim
- [vim-godef](https://github.com/dgryski/vim-godef) - godef support
- [vim-hugo-helper](https://github.com/robertbasic/vim-hugo-helper) - Set of helpers for Hugo Static Page Generator

###  Atom Extensions

- [go-plus](https://github.com/joefitzgerald/go-plus) - Makes working with Go in Atom awesome.
- [save-commands](https://atom.io/packages/save-commands) - Assign parametrized shell commands to file globs to be automatically run whenever the file is saved

#### [save-commands](https://atom.io/packages/save-commands) Example Configuration:

Create a `save-commands.json` in the root of your Go source folder:

```
{
    "commands": [
        "**/*.go : gofmt -w {absPath}{filename}",
        "**/*.go : go run {absPath}{filename}"
    ]
}
```

## Go Libraries

- [color](https://github.com/fatih/color) - Color package
- [gopm](https://github.com/gpmgo/gopm) - Go Package Manager
- [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications
- [spinner](https://github.com/briandowns/spinner) - Terminal Spinner
- [viper](https://github.com/spf13/viper) - Complete configuration solution


## Librarie Search

- [golanglibs.com](https://golanglibs.com/) - Search for Go Libraries

## Learning

### Websites

- [official Go Lang Site](https://golang.org/)
- [GoDoc](https://godoc.org)
- [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
- [Golang Tutorial](https://gist.github.com/honkskillet/bd1f72223dd8e06b5ce6)
- [gostart](https://github.com/alco/gostart)
- [Free Books](https://github.com/EbookFoundation/free-programming-books/blob/master/free-programming-books.md#go)

### Example Repositories

- [go-explore](https://github.com/ellerbrock/go-explore)
- [gobyexample](https://github.com/mmcgrana/gobyexample)
- [GolangTraining](https://github.com/GoesToEleven/GolangTraining)

##  Contact

[![Github](https://github.frapsoft.com/social/github.png)](https://github.com/ellerbrock/)[![Docker](https://github.frapsoft.com/social/docker.png)](https://hub.docker.com/u/ellerbrock/)[![npm](https://github.frapsoft.com/social/npm.png)](https://www.npmjs.com/~ellerbrock)[![Twitter](https://github.frapsoft.com/social/twitter.png)](https://twitter.com/frapsoft/)[![Facebook](https://github.frapsoft.com/social/facebook.png)](https://www.facebook.com/frapsoft/)[![Google+](https://github.frapsoft.com/social/google-plus.png)](https://plus.google.com/116540931335841862774)[![Gitter](https://github.frapsoft.com/social/gitter.png)](https://gitter.im/frapsoft/frapsoft/)
