## Logs
2020.05.13
- change primary and secondary header font-size

2020.05.12
- change **bold** font-weight to 500 in markdown
- change parenthsis highlight to bottom-border
- change body font-size to 300 (according to iOS guidelines)
- change code highlighting in markdown to the same color as in code cell
- change title hierarchy font properties

### Jupyter-Notebook-Xcode-Theme
([Original blog](https://navoshta.com/jupyter-notebook-xcode-theme/))
Personal theme that I use for Jupyter notebooks, modified version of `Neil Panchal`'s scheme (see fork origin). I've basically tried to replicate syntax highlighting in Xcode where possible — with a couple of other minor modifications.

![Notebook Design Screenshot](screenshot.png "Notebook Design")

### Installation instructions
https://github.com/nsonnad/base16-ipython-notebook

```sh
cd ~/.jupyter/
mkdir custom
cd custom
curl -O https://raw.githubusercontent.com/type-null/Jupyter-Notebook-Xcode-Theme/master/custom.css
```
