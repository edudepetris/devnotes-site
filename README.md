## 💭 Use case

Every time I dive into a project, I create a folder and a file `devnotes/notes.md` at the root of the project, where I keep notes like credentials, remainder, chunks of code and more. Finally, I ignore the folder (gitignore) to avoid push it. 

## 💡 Solution

As I continue doing this process manually, why not create a CLI tool that creates this structure for me 🤷‍♀️. Born [Devnotes CLI](#devnotes-cli)

Sometimes I have the same project on different laptops. Why not push the "notes.md" to a kind of cloud 🤷‍♀️. Born [Devnotes](#dasboard).


## 🎉 Benfits 
I've tried Apple Notes, Google Keep, and so on, but I've noticed that keeping the notes along with my project (codebase), it's 💯 faster and easier to use, it's as simple as open the notes.md file with your text editor.

Also, using it as `.md` gives me highlight code and easy to export as HTML if I need to read, 💯 better than plain text.


# Devnotes CLI

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

![render1615968444434](https://user-images.githubusercontent.com/2192588/111435113-4096bf80-8765-11eb-852c-4d56736554e4.gif)

# Dasboard

* Open the [sign up](https://devnotes-production.herokuapp.com/users/sign_up) page.

![Screen Shot 2021-03-10 at 10 42 17 PM](https://user-images.githubusercontent.com/2192588/110609956-a4b00580-81f2-11eb-9538-1fc3f2c18a78.png)
