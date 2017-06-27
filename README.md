# awesome-npx
🌟 packages and resources that work really well with https://github.com/zkat/npx 🕶

## npx itself is awesome
`npx` lets you execute npm package binaries without installing them. `npx` is the last thing you need to globally install:
`> npm i -g npx` (this command also updates npx)

Now you can execute tools from npm packages without having to install them globally:

```sh
> npx cowsay wow
npx: installed 1 in 1.413s
 _____
< wow >
 -----
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

you can even use `npx` to view this list of `awesome-npx` tools:
```sh
> npx awesome-npx
```

## packages which work well with npx
### [cowsay](https://github.com/piuccio/cowsay) - adds cow ascii art to your special message
`npx cowsay <text>`

### [figlet-cli](https://github.com/patorjk/figlet-cli) - the classic multi-line ascii text generator, with font support
`npx figlet-cli <text>`

### [shx](https://github.com/shelljs/shx) - portable shell commands like ls, cp, rm
`npx shx ls`
`npx shx rm -rf /tmp`


## articles and resources
- write one and we'll link it here!

## etc
Please read the [CONTRIBUTING.md](https://github.com/js-n/awesome-npx/blob/master/CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](https://github.com/js-n/awesome-npx/blob/master/CODE_OF_CONDUCT.md) docs. Everything in this repo is licensed [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/) unless otherwise noted. Thank you for being awesome!
