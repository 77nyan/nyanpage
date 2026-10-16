# nyanpage

> My personal website: a realistic Linux terminal in your browser, with a retro console game hidden inside.

**Live site:** https://nyanpage.pages.dev

<!-- Add a screenshot: save it as screenshot.png in this folder and remove the comment markers around the next line -->
<!-- ![Screenshot of nyanpage](screenshot.png) -->

## About

nyanpage is my personal website, designed and built by me as a solo developer. The page is a fake but realistic Linux terminal that runs entirely in the browser. It is written in plain HTML, CSS and JavaScript and hosted on Cloudflare Pages. It is a hobby project, so updates come when I have time.

## Try it

Open the site and type a command:

| Command | What it does |
| --- | --- |
| `cmd list` | Shows the available commands |
| `cmd list --advanced` | Shows the advanced commands |
| `myretroconsole launch` | Launches the retro console game |

You can also press `Ctrl+L` to launch the retro console game directly.

## Features

- A realistic Linux-style terminal in the browser
- A large set of built-in commands, listed with `cmd list` and `cmd list --advanced`
- A retro console game I built myself, started with `myretroconsole launch` or `Ctrl+L`
- Plain HTML, CSS and JavaScript

## Run it locally

This assumes `index.html` sits in the root of the repo.

```sh
git clone https://github.com/77nyan/nyanpage.git
cd nyanpage
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser. Press Ctrl+C in the terminal to stop the server. On Windows, use `python -m http.server 8000` in PowerShell.

## Deploy

The live site is hosted on [Cloudflare Pages](https://pages.cloudflare.com/). To host your own copy, fork this repo, create a Cloudflare Pages project, and connect it to your fork. For a plain static site, leave the build command empty and set the output directory to the folder that contains `index.html`.

## Feedback

Found a bug or have an idea? Open an issue.

## Credits

Designed and built by Jakub Ziaja ([@77nyan](https://github.com/77nyan)).

## License

The code is released under the [MIT License](LICENSE).

The license covers only what I made myself. Artwork, characters, music or other material made by someone else stays under its own owner's rights and is not covered by it.
