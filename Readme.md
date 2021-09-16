# Lavalink on Replit

How to install and run lavalink on replit.

You need to have the basic knowlage of lavalink. and you need to know how to make your bot connect via https.

## Installation

Fork this github repository. then create a new replit project.

or [click me](https://replit.com/@ThnksCJ/LavaLink-On-Replit) Go Straight to the project.

## Your Replit Lavalink Connect Should Loom Like This:

  Lavalink: {
    id: "Main",
    host: "lavalink-on-replit.thnkscj.repl.co",
    port: 477,
    pass: "WHATEVERYOUWANT", 
    secure: true // Set this to true if you're self-hosting lavalink on replit.
  },


### Initialisations
```bash
chmod +x start.sh
```

## Usage

```bash
./start.sh
```

- - -

## Note & such
The default port to connect is `443` and the default password is `maybeiwasboring`


You can’t change the lavalink port! it will default to 443 due to how replit work.


## License
[MIT](https://choosealicense.com/licenses/mit/)
