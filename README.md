# A-Frame Ball Throw

<p align="center">
  <img src="http://i.imgur.com/NSCUTtb.gif"/>
</p>

Playable with **HTC Vive**.

This repository contains a small demonstration of A-Frame with vive controllers and physics powered by [A-Frame Extras](https://github.com/donmccurdy/aframe-extras). Grab a ball and chuck it at the stack of boxes!

### Expansion and Experimentation

Try forking this component and messing around with it. For instance, 

Change the force of gravity from 1.6 m/s^2 (similar to the Moon), to 9.8 m/s^2 (similar to the Earth).

```html
    <a-scene physics='gravity: -9.8' antialias='true'>
```

### Local Development

To serve the site from a simple Node development server:

    npm start

Then launch the site from your favourite browser:

[__http://localhost:3000/__](http://localhost:3000/)

If you wish to serve the site from a different port:

    PORT=8000 npm start


## License

This program is free software and is distributed under an [MIT License](LICENSE).
