<h1 align="center">🤖 Fix! 🩹</h1>

<p align="center">
    AI fixing your issues.
</p>

<p align="center">
    <a href="https://github.com/tom-doerr/fix/stargazers"
        ><img
            src="https://img.shields.io/github/stars/tom-doerr/fix?colorA=2c2837&style=for-the-badge&logo=starship style=flat-square"
            alt="Repository's starts"
    /></a>
    <a href="https://github.com/tom-doerr/fix/issues"
        ><img
            src="https://img.shields.io/github/issues-raw/tom-doerr/fix?colorA=2c2837&style=for-the-badge&logo=starship style=flat-square"
            alt="Issues"
    /></a>
    <a href="https://github.com/tom-doerr/fix/blob/main/LICENSE"
        ><img
            src="https://img.shields.io/github/license/tom-doerr/fix?colorA=2c2837&style=for-the-badge&logo=starship style=flat-square"
            alt="License"
    /><br />
    <a href="https://github.com/tom-doerr/fix/commits/main"
		><img
			src="https://img.shields.io/github/last-commit/tom-doerr/fix/main?colorA=2c2837&style=for-the-badge&logo=starship style=flat-square"
			alt="Latest commit"
    /></a>
    <a href="https://github.com/tom-doerr/fix"
        ><img
            src="https://img.shields.io/github/repo-size/tom-doerr/fix?colorA=2c2837&style=for-the-badge&logo=starship style=flat-square"
            alt="GitHub repository size"
    /></a>
</p>

<p align="center">
    <img src='https://github.com/tom-doerr/bins/raw/main/fix/all.gif'>
    <p align="center">
        You just need to prepend `fix` to your command and the AI will suggest solutions.
    </p>
</p>





## What is it?

This is a program that suggests solutions for errors in the command line. It is using OpenAI's Codex AI to come up with suggestions.

## Installation

1. Get access to OpenAI's [Codex API](https://openai.com/blog/openai-codex/).
2. Clone the repository
3. Add `main.py` to your path, e.g. by running `cp $PWD/main.py ~/.local/bin/fix`.


## How to use it
```
$ fix <program>
```
To fix the last command:
```
$ fix !!
```


## How it works

This script executes your program and generates potential solutions using OpenAI's [Codex AI](https://openai.com/blog/openai-codex/).
































































































