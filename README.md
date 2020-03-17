# VSCode Python Extension Code Execution

This is a PoC of a code execution vulnerability discovered in the Visual Studio Code Python extension.
TL;DR: vscode may use code from a virtualenv found in the project folders without asking the user, for things such as formatting, autocompletion, etc.
You can read more about this vulnerability [on Doyensec blog](https://blog.doyensec.com).

## Howto

- `git clone https://github.com/doyensec/VSCode_codeexec_PoC_Oct2019.git`
- add the cloned repo to VSCode workspace
- open `test.py` in VScode
