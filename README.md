# A-Frame Ball Throw

<p align="center">
  <img src="http://i.imgur.com/NSCUTtb.gif"/>
</p>

Playable with **HTC Vive**.

This repository contains a small demonstration of A-Frame with vive controllers and physics powered by [A-Frame Extras](https://github.com/donmccurdy/aframe-extras) and [A-Frame Physics System](https://github.com/donmccurdy/aframe-physics-system). Grab a ball and chuck it at the stack of boxes!

### Expansion and Experimentation

Try forking this component and messing around with it. For instance, 

Change the force of gravity from 1.6 m/s^2 (similar to the Moon), to 9.8 m/s^2 (similar to the Earth).

```html
    <a-scene physics='gravity: -9.8' antialias='true'>
```

### Running locally

```bash
npm start
```

Open the URL `https://192.168.1.11:3000/` in Firefox and bypass the scary "certificate invalid" warning. WebVR seems to require `https` and achieving this on localhost involves generating a certificate (one that the browser won't automatically trust).

### Troubleshooting

#### The height is off

As of July 2020, I think Firefox computes height offset based on the headset's position at the time "Enter VR" is pressed. So if you enter VR with the headset on the floor, you'll be either too tall or too short. It seems to work better if you press "Enter VR" while wearing the headset.


