<p align="center">
    <br>
    <br>
    <samp>
    my setup environment, for the people who care.
    </samp>
</p>

## preface

i personally use 2 different operating systems, as i have a macbook as a laptop and a desktop pc. i use macos on my laptop and windows on my desktop pc.

## dev environment

- [visual studio code](https://code.visualstudio.com/) (ide)
  - theme: [material theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-community-material-theme) (darker high contrast)
  - extensions:
    - [github copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
    - [prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    - [tailwind css intellisense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
    - [discord presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode) (gotta flex on people yk)
- [git](https://git-scm.com/) (of course)
- [oh my zsh](https://ohmyz.sh/) (macos only, windows i use git bash)
  - theme: [bliss-zsh](https://github.com/jckli/bliss-zsh) (modified by me)
- [termius](https://termius.com/) (my ssh client of choice)

## tech stack

### languages

- python
  - main language for projects
  - backend: [sanic](https://sanic.dev/) or [flask](https://flask.palletsprojects.com/)
- javascript (mainly typescript)
  - website development
  - runtime: [bun](https://bun.sh/) (macos) or [node.js](https://nodejs.org/) (windows)
  - frontend: [next.js](https://nextjs.org/) (react framework) + [tailwindcss](https://tailwindcss.com/)
    - (i mainly use all the stuff in my [next-template](https://github.com/jckli/next-template))
- go
  - for efficient applcations
  - backend: [http-router](https://github.com/julienschmidt/httprouter)

i hate using raw html and css unless its in a javascript framework

### other stuff

- [cloudflare](https://www.cloudflare.com/) (for all my dns management)
- databases
  - mongodb
  - postgresql
- personal server
  - [proxmox](https://www.proxmox.com/) (main os)
  - [debian](https://www.debian.org/) (virtualized os, linux distro preference)
  - [wireguard](https://www.wireguard.com/) (vpn tunnel)
