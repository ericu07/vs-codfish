# vs-codfish

## Licence

**GPL-3**

## What is it?

Visual Studio Code workspace-file generator.

It's primary use-case is to re-generate on the fly your workspace file, carrying over all the settings, but only with the folders you need.

If you switch between complex projects multiple times a day, this might be for you! Regenerate your workspace file, and Visual Studio Code will automagically update its folder list.

## What can it do?

- Support emojis 🥳 - Emojis can be used as folder icons ;
- Supports multiple-root workspaces ;
- Supports remote folders with `Remote - SSH` extension (ID `ms-vscode-remote.remote-ssh`, [code.visualstudio.com/docs](https://code.visualstudio.com/docs/remote/ssh)) ;

## Dependencies

- Python3: tested with Python3.10, should work on all [non-deprecated python versions](https://devguide.python.org/versions) ;
- [PyYAML](https://pypi.org/project/PyYAML) if you use `.yaml` config files instead of `.json` config files ;
- 
