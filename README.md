💭 My use case: every time I start a project, I create a folder with a file `devnotes/notes.md` where I keep all daily work notes or things that I will need (credentials, remainder, chunks of code ...).

I've tried Apple Notes, Google Keep, and so on, but I've noticed that keeping the notes along with my project (codebase), it's 💯 faster, easier to use and navigate, it's as simple as open the notes.md file with your favorite text editor.

Also, I've noticed that using it as `.md` gives me highlight code and easy to export as HTML if I need to read, 💯 better than plain text.

💡 As I have more than one computer, and sometimes the same projects, why not push those notes to a kind of cloud 🤷‍♀️. Born Devnotes dashboard.

💡 Sometimes I have the same project on different laptops. Why not push the "notes.md" to a kind of cloud 🤷‍♀️. Born Devnotes dashboard.

### CLI

* Installing using brew (recommended)
```console
$ brew install edudepetris/homebrew-brew/devnotes
```
* Installing using NPM
```console
$ npm install -g devnotes
```
* From any project's root folder
```console
$ cd devnotes.github.io/ # example using this repo.
$ devnotes init
```
* You can push your `notes.md` content to devnotes cloud (it requires [an account](#create-an-account) before)
```console
$ devnotes login
$ devnotes push
```

_check the full list of commands [here](https://github.com/edudepetris/notes-cli/blob/master/doc/commands.md#usage)_

##### Create an account

* Open the [sign up](https://devnotes-production.herokuapp.com/users/sign_up) page.

### Dasboard
![devnote-app](https://user-images.githubusercontent.com/2192588/110196137-5d024480-7ea7-11eb-8b94-a4e65a6f00b6.png)

