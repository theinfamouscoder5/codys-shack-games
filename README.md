# Cody's Shack

![GitHub Repo size](https://img.shields.io/github/repo-size/theinfamouscoder5/codys-shack-games?style=flat&label=Repo%20size)
![GitHub Repo stars](https://img.shields.io/github/stars/theinfamouscoder5/codys-shack-games?style=flat&label=Repo%20stars&color=yellow&link=https%3A%2F%2Fgithub.com%2F3kh0%2F3kh0-lite%2Fstargazers)

Welcome to Cody's Shack, a self-deployable, good-looking game site based off of 3kh0 Lite.

## Features
- No tracking
- No ads
- Good-looking, fresh UI
- Cool CSS effects on some buttons
- Easily customizable

## Deploy it yourself

This site is supposed to be simple yet extendable. You can edit this to your heart's content, but I respectfully ask that you credit me somehow.
1. Fork this repo (give star pls :D)
2. Edit the files. (mainly the files in the `config` folder)
3. Optionally, add more games. ([Get some here](https://gitlab.com/3kh0/3kh0-assets))
4. Host it on your server or any static web host.
5. Enjoy!
It is recomened to deploy to Cloudflare. To do so, just fork this repo, sign in to Cloudflare, and deploy the repo as Pages (not Worker). Leave `build command` and `build output directory` blank.

> A known issue is game files; because some games are massive, they will fail on many services. There is no straightforward fix, but you can try to host the files on your server.
## Configuration

All the configuration is done in the `config` folder.
- `games.json`: It contains the games' names, icons, and link.
