# Background
Helper for setting background image style with React

Usage is simple:

```
npm install github:mika0x56/background
```

```
import background from 'background'

...

<div style={background('/public/myawesomepic.jpg')}
```

What it does is create a simple object like so:

```
{
    backgroundImage: "url('/public/myawesomepic.jpg')"
}
```
