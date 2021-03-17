💭 My use case: every time I start a project, I create a folder with a file `devnotes/notes.md` where I keep all daily work notes or things that I will need (credentials, remainder, chunks of code ...).

I've tried Apple Notes, Google Keep, and so on, but I've noticed that keeping the notes along with my project (codebase), it's 💯 faster, easier to use and navigate, it's as simple as open the notes.md file with your favorite text editor.

Also, I've noticed that using it as `.md` gives me highlight code and easy to export as HTML if I need to read, 💯 better than plain text.

💡 As I have more than one computer, and sometimes the same projects, why not push those notes to a kind of cloud 🤷‍♀️. Born Devnotes dashboard.

💡 Sometimes I have the same project on different laptops. Why not push the "notes.md" to a kind of cloud 🤷‍♀️. Born Devnotes dashboard.

### CLI

* Installing using brew (recommended)
```console
brew install edudepetris/homebrew-brew/devnotes
```
* Installing using NPM
```console
npm install -g devnotes
```
* From any project's root folder
```console
cd devnotes.github.io/ # example using this repo.
devnotes init
```
* You can push your `notes.md` content to devnotes cloud (it requires [an account](#create-an-account) before)
```console
devnotes login
devnotes push
```

_check the full list of commands [here](https://github.com/edudepetris/notes-cli/blob/master/doc/commands.md#usage)_

![render1615965510940](https://user-images.githubusercontent.com/2192588/111430007-a3d12380-875e-11eb-9aee-29f097eaa4a1.gif)

### Dasboard

#### Create an account

* Open the [sign up](https://devnotes-production.herokuapp.com/users/sign_up) page.

![Screen Shot 2021-03-10 at 10 42 17 PM](https://user-images.githubusercontent.com/2192588/110609956-a4b00580-81f2-11eb-9538-1fc3f2c18a78.png)
![Simulator Screen Shot - iPhone 12 Pro Max - 2021-03-10 at 22 52 48](https://user-images.githubusercontent.com/2192588/110613625-5bfa4b80-81f6-11eb-848e-187d3471841f.png)




