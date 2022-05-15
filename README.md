# Website to get a random name with a play on words
## What's this?
I made a website that spits out a random element from a list of names with plays on words.
I first made a [french version](https://nomavecjeudemotsdebile.pages.dev/), then I made [this english version](https://getanamewithapun.pages.dev/).

This repo contains the source code of the english version.

## How does it work?
### The website
The website chooses for you a random element from a list of names with plays on words.
The list is in Content/names.js.
### Hosting
I use [CloudFlare Pages](https://pages.cloudflare.com/#pricing).
The source code of the website is in the "Content" folder (vanilla HTML + JS and a bit of CSS) ; it is 100% front-end.
The deployment process is: CloudFlare copies what's in the "Content" folder on the server, and that's basicaly it.
(Well, it's a bit more subtle than that, but you get the idea. Read the official CloudFlare documentation to know more.)

## Can I participate?
Yes, you can!
If you want to add or modify anything (some names, some CSS, some fancy stuff), just submit an issue or a PR.

### I want to code, are there guidelines?
The (arbitrairy) guidelines are: no duplicates, and keep an alphabetical order.
And... that's it.
