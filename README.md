# Random User-Agent

## Disclaimer 

Based on tarampampam's project using WTFPL

### Warning

Depending on your threat model, faking your user agent might make you _more_ fingerprintable, not less. There are ways other than `User-Agent` sniffing to determine what browser you're using, so malicious sites could learn what browser you're _really_ using through other means and then combine that with your randomly changing `User-Agent` to pretty effectively track you. For background, see [this GitHub issue](https://github.com/tarampampam/random-user-agent/issues/47). You've been warned.

### Building from sources

For a building extension from sources _(and pack as a `zip` file)_ use next commands:

```bash
$ cd /path/to/the/sources
$ npm install
$ gulp
```

> You can install `gulp` globally with next command: `$ sudo npm install -g gulp`
