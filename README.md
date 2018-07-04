# My Top Spotify Node.js Server

[![GitHub](https://img.shields.io/badge/GitHub-Accudio-0366d6.svg)](https://github.com/Accudio) [![Twitter](https://img.shields.io/badge/Twitter-@accudio-1DA1F2.svg)](https://twitter.com/accudio) [![Website](https://img.shields.io/badge/Website-accudio.com-4B86AF.svg)](https://accudio.com) [![Donate](https://img.shields.io/badge/Donate-Paypal-009cde.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=alistair.shepherd@hotmail.co.uk&item_name=Supporting+open+source+projects+by+Alistair+Shepherd&currency_code=GBP)

Server for [mytopspotify.io][url]. Based on [Spotify's][spotifyurl] 'authorization_code' [Developer Authentication Example][spotifyauthexamples]. Built by [Alistair Shepherd][alistairshepherdurl] from [Accudio][accudiourl].

## Installation

This server runs on Node.js. On [its website](http://www.nodejs.org/download/) you can find instructions on how to install it. You can also follow [this gist](https://gist.github.com/isaacs/579814) for a quick and easy way to install Node.js and npm.

Once installed, clone the repository and install its dependencies running:

    $ npm install

### Using your own credentials
You will need to register your app and get your own credentials from the Spotify for Developers Dashboard.

To do so, go to [your Spotify for Developers Dashboard](https://beta.developer.spotify.com/dashboard) and create your application.

Once you have created your app, replace the `client_id`, `redirect_uri` and `client_secret` in app.js with those obtained from My Applications.

## Running the examples
To start the server, run `app.js`:

    $ node app.js

Then open `http://localhost:8888` in a browser.

## Version History

- v0.2.0 - Local-compatible beta release
- v0.1.0 - Initial Release

[url]:https://mytopspotify.io/
[spotifyurl]:https://www.spotify.com/
[spotifyauthexamples]:https://github.com/spotify/web-api-auth-examples
[alistairshepherdurl]:https://alistairshepherd.co.uk/
[accudiourl]:https://accudio.com/