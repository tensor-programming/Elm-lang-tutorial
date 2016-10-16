# Elm-lang-tutorial
A tutorial on [Elm-Lang](http://elm-lang.org/).

[Our channel Youtube is here](https://www.youtube.com/channel/UCYqCZOwHbnPwyjawKfE21wg)
[Our blog is here](http://tensor-programming.com)

# How to install Elm:
You can install Elm through NPM by running `npm install -g elm` or you can use the installers on [Mac](http://install.elm-lang.org/Elm-Platform-0.17.1.pkg) and [Windows](http://install.elm-lang.org/Elm-Platform-0.17.1.exe). Elm can also be built from [source](https://github.com/elm-lang/elm-platform)

# How to install Atom and configure it for Elm:
  1. Go to the [atom website](https://atom.io/) and install the atom editor. 
  2. Get NodeJS/Npm from [node.js](https://nodejs.org/en/) 
  3. Open a terminal or cmd shell and run `apm install language-elm`.
  4. Then run `npm install -g elm-oracle`
  5. Run `which elm-oracle` *mac or linux* or `where.exe elm-oracle` *windows* to get the path for elm-oracle
  6. Copy the elm-oracle path to the settings tab for language-elm inside of atom. 
  7. Next run `apm install elm-format` and navigate to https://github.com/avh4/elm-format to get elm-format
  8. Extract elm-format into your path so that you can easily see it and use it. 
  9. Run `which elm-format` *mac or linux* or `where.exe elm-format` *windows* to get the path for elm-format
  10. Paste the path of elm-format into the elm-format settings box in Atom. 
  11. Run `apm install linter-elm-make` and `which elm-make` or `where.exe elm-make`
  12. Copy make sure your elm-make is on your Path and copy the elm-make path into the settings box in the linter-elm-make settings box in atom.
  13. Open atom and make a *.elm* and save it with `ctr+c`, you should see elm-format and the autocompletion.
  
Here are the other text editor options and how to install the different packages for them:
    * [Brackets](https://github.com/lepinay/elm-brackets)
    * [Emacs](https://github.com/jcollard/elm-mode)
    * [IntelliJ](https://github.com/durkiewicz/elm-plugin)
    * [Lighttable](https://github.com/rundis/elm-light)
    * [Sublime Text](https://packagecontrol.io/packages/Elm%20Language%20Support)
    * [Vim](https://github.com/lambdatoast/elm.vim)
    * [VS Code](https://github.com/sbrink/vscode-elm)
