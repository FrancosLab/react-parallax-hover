#Parallax Hover React Component
Inspired by @drewwilson’s [atvImg](https://github.com/drewwilson/atvImg), ported to React. Allows for non image based layers. Currently only supports mouse events. 

Pull requests and suggestions more than welcome :]

### Install
`npm install --save react-parallax-hover`

### Demo
http://codepen.io/TylerK/full/Gpdqqq

### Run the example locally
```
git clone https://github.com/tylerk/react-parallax-hover/
cd react-parallax-hover
npm install
npm start
```

### Usage
```
import ParallaxHover from 'react-parallax-hover';

<ParallaxHover width='500' height='500'>
    <img ref='image' src='...' />
    <div ref='text'>Some text</div>
</ParallaxHover>
```

### TODOs
- [ ] More robust configuration
- [ ] Touch event handling
- [ ] Github pages site with examples and demo's
- [ ] Animated gif hotness for this readme
