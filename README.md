<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues-open][issues-open-shield]][issues-url]
[![Issues-closed][issues-closed-shield]][issues-url]


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Israel-Laguan/dotfiles">
    <img src="./docs/img/folder.png" alt="Logo"  height="80">
  </a>

  <h1 align="center">
	Israel Laguan Linux's dotfiles!
  </h1>

  <p align="center">
    Collects all my important cross-distro system configurations
    <br />
	  <!-- 🖊️
    <a href="https://">Read the article</a> -->
    🐞
    <a href="https://github.com/Israel-Laguan/dotfiles/issues">Report a Bug</a>
    🙋‍♂️
    <a href="https://github.com/Israel-Laguan/dotfiles/issues">Request Feature</a>
  </p>
</p>

## Table of Contents

1. [The Project](#the-project)
2. [Features](#features)
3. [Prerequisites](#prerequisites)
4. [Getting Started](#getting-started)
5. [Author](#author)
6. [Contributing](#contributing)
7. [Show your support](#show-your-support)
8. [License](#license)

# The Project

These are my dotfiles. Take anything you want, but at your own risk. It targets debian systems, but 
it should work on *nix as well (with apt-get).

I've been using bash on-and-off for a long time (since Slackware Linux was distributed on 1.44MB floppy disks). In all that time, every time I've set up a new Linux or OS X machine, I've copied over my .bashrc file and my ~/bin folder to each machine manually. And I've never done a very good job of actually maintaining these files. It's been a total mess.

I finally decided that I wanted to be able to execute a single command to "bootstrap" a new system to pull down all of my dotfiles and configs, as well as install all the tools I commonly use. In addition, I wanted to be able to re-execute that command at any time to synchronize anything that might have changed. Finally, I wanted to make it easy to re-integrate changes back in, so that other machines could be updated.

# Features

- Aliases
- Prompt theme
- `bash` functions
- `vscode` settings
- `vscode` snippets (Based on [this repo][snippets-repo])

# Prerequisites

- Debian 8+ or derivatives. It should work on *nix as well
- `git`
- `vscode`

# Getting Started

For now copy paste as needed! (WIP: make an autoinstall script!)

# Author

| [Israel Laguan][author-github] | ![email-icon][] Email me to [contact@israellaguan.com][author-email] / ![linkedin-icon][] Connect to [my LinkedIn][author-linkedin] |
| :----------------------------: | :---------------------------------------------------------------------------------------------------------------------------------: |
|        ![author-pic][]         |                                                              ![banner]                                                              |

<!-- MARKDOWN LINKS & IMAGES -->

[author-pic]: https://avatars2.githubusercontent.com/u/36519478?s=460&v=4
[author-github]: https://israel-laguan.github.io
[author-linkedin]: https://www.linkedin.com/in/israellaguan
[author-email]: mailto:contact@israellaguan.com
[banner]: https://github.com/Israel-Laguan/Israel-Laguan/raw/master/docs/banner.jpg
[linkedin-icon]: https://img.icons8.com/color/20/000000/linkedin.png
[email-icon]: https://img.icons8.com/color/20/000000/message-squared.png


# Contributing

🤝 Contributions, issues and feature requests are welcome!
Feel free to check the [issues page][issues-url].

# Show your support

🤗 Give a ⭐️ if you like this project!

## Icons made by 

- <a href="https://www.flaticon.com/authors/dinosoftlabs" title="DinosoftLabs">DinosoftLabs</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>

- <a href="https://www.flaticon.com/authors/itim2101" title="itim2101">itim2101</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>

- <a href="https://www.flaticon.com/authors/pixel-perfect" title="Pixel perfect">Pixel perfect</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>

- <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>

## Ideas for dotfiles

- Clone Function by [Phillip Krueger][clone-unction]
- Arch Linux [Documentation on Prompt Customization][arch-prompt]
- VSCode [official documentation about setup extentions][vscode-extentions]

# License

📝 This project is licensed under the [MIT](LICENSE)\
Feel free to fork this project and improve it

[snippets-repo]: https://github.com/Israel-Laguan/vscode-extension-react-snippets

[clone-unction]: https://www.phillip-kruger.com/post/some_bash_functions_for_git/
[arch-prompt]: https://wiki.archlinux.org/index.php/Bash/Prompt_customization
[vscode-extentions]: https://code.visualstudio.com/docs/editor/extension-gallery

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/Israel-Laguan/dotfiles?style=for-the-badge
[contributors-url]: https://github.com/Israel-Laguan/dotfiles/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Israel-Laguan/dotfiles?style=for-the-badge
[forks-url]: https://github.com/Israel-Laguan/dotfiles/network/members
[stars-shield]: https://img.shields.io/github/stars/Israel-Laguan/dotfiles?style=for-the-badge
[stars-url]: https://github.com/Israel-Laguan/dotfiles/stargazers
[issues-open-shield]: https://img.shields.io/github/issues/Israel-Laguan/dotfiles?style=for-the-badge
[issues-url]: https://github.com/Israel-Laguan/dotfiles/issues
[issues-closed-shield]: https://img.shields.io/github/issues-closed/Israel-Laguan/dotfiles?style=for-the-badge
