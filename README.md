# llvm-vim

Collection of settings for the vim editor to work on llvm `*.ll` and tablegen
`*.td` files. It comes with [filetype detection rules] (ftdetect/),
[syntax highlighting](syntax), some
[minimal sensible default settings](ftplugin/) and
[indentation plugins](indent/).

To install copy all subdirectories to your $HOME/.vim, use your favorite plugin
package manager or if you prefer create symlinks to the files here.

**NOTE**: This is a copy of files included into llvm/llvm-project repo, which
is made to allow installation of these files using vim plugin package managers.

Files in this repo correspond to their original counterparts at revision
llvm/llvm-project@9a24488c.

## Contribution

I would prefer to keep this repo as close as possible to the original
llvm/llvm-project. So, for any file which was copied from there, it would be
better to contribute directly to llvm/llvm-project.

Contribution guides for llvm-project can be found in the official docs:
- [How to submit a bug report](https://llvm.org/docs/HowToSubmitABug.html)
- [How to submit a patch](https://llvm.org/docs/Contributing.html#how-to-submit-a-patch)

However, if you are not familiar with llvm-project, you can submit issues or
pull requests directly to this repo and I will forward them to the llvm-project.

