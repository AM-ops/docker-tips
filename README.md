# docker-tips 🐋

## Description 📝
A repository for Tips, Tricks, and Notes on Docker in a Q&A format. I will try to keep it up-to-date with the [Official Docker Documentation](https://docs.docker.com/), and always recommend industry standards as set out by the docs.

This project was built using [LaTeX](https://latex-project.org/), a high-level, descriptive markup language.

To view the latest complied PDF have a look at the [main.pdf](/main.pdf) file, or alternatively directly download it from [here](https://github.com/AM-ops/docker-tips/raw/main/main.pdf).

## Project Status 📶
As of December 2022 this project has the following status:

- Actively maintained
- Somewhat maintained ⬅️
- Minimally maintained
- Seeking co-maintainer(s)
- Seeking new maintainer
- Unsupported or Abandoned

## Project setup 🏗️

To get the project running on your local machine, follow the following steps:

### Prerequisites 🧑‍💻
Make sure your machine has the following already set up and ready to go:
- LaTeX, for OS specific details have a look at the [official docs](https://www.latex-project.org/get/)
- [git](https://git-scm.com/)
- [python](https://www.python.org/)
- [Pygments](https://pygments.org/), this can be installed using the python package-management system using the following terminal command:

```shell
pip install Pygments
```

### Up and running 🏃 

1. Clone the repository. The easiest option is using the following git command in your terminal/command prompt:
```shell
git clone https://github.com/AM-ops/docker-tips.git
```

2. Compile the `main.tex` file using the TeX typesetting engine [XeTeX](http://xetex.sourceforge.net/). This can be done using the following command (run twice if table of contents not visible):

```shell
xelatex -synctex=1 -interaction=nonstopmode -shell-escape main.tex
```

Note the flag(s) utilised in the command above. Additionally, a PDF file titled `main.pdf` will automatically be generated.

## License ©️
This project is licensed under the [MIT License](LICENSE).
