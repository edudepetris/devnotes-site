💭 My use case: every time I start a project, I create a folder with a file `devnotes/notes.md` where I keep all daily work notes or things I will need (credentials, remainder, chunks of code ...).

I've used Apple Notes, Google Keep, and so on. But I've noticed that having the notes along with your project, it's 💯 faster, easier to use and navigate, as simple as open a file with your favorite text editor.

I've noticed that using a `.md` is better than plain text, as I've used to do it a couple of years ago.

💡 As I continue doing these processes manually, why not create a CLI tool that creates this structure for me 🤷‍♀️. Born Devnotes CLI

💡 As I have more than one computer, and sometimes the same projects, why not push those notes to a kind of cloud 🤷‍♀️. Born Devnotes dashboard.

### CLI
_check the full list of commands [here](https://github.com/edudepetris/notes-cli/blob/master/doc/commands.md#usage)_

* Install 
🍺 `$ brew install edudepetris/homebrew-brew/devnotes`

* Move to the root folder of any project and init devnotes
`$ devnotes init`

* You can push your `notes.md` content to devnotes cloud
```console
$ devnotes login
$ devnotes push
```

### Dashboard
