# elm-editors

Here we will provide (or link to) several syntax highlighters for Elm
using the following editors:

 - [gedit](gedit) is provided here, and is a derivative of the haskell syntax.
 - [vim](https://github.com/ElmCast/elm-vim/blob/master/syntax/elm.vim)
 - [micro](https://github.com/zyedidia/micro/blob/master/runtime/syntax/elm.yaml) terminal editor
 - [notepadqq](https://notepadqq.com/s/) natively supports elm.

and see [elm/editor-plugins](https://github.com/elm/editor-plugins) for a more comprehensive list.

Each language hosted locally has its own set of README instructions with corresponding 
files in the subfolders linked above, and you can follow the instructions
to have the editor render your Elm files.

## Install

Installation means simply copying the file into the language-specs folder
that your gedit installation uses. For example:

**1. Clone the Repository**

```bash
git clone https://github.com/vsoch/elm-editors
cd elm-editors
```

**2. Move the syntax file**

See the README in each subfolder for specific instructions! Generally the last
step of install is to move the file to some language spec folder of the software,
and then to restart the editor(s).

## Contributing

If you would like to add an editor, please open an issue or Pull Request if you
have an editor to contribute.
