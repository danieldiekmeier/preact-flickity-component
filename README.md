# Preact Flickity Component

This is an adaption of [@theolampert's](https://github.com/theolampert) [React Flickity Component](https://github.com/theolampert/react-flickity-component) that is compatible to [Preact](preactjs.com).

It doesn't use PropTypes, Portals or any of that fancy React stuff.

I built it because I needed to mount a Flickity Slider, and I'm afraid that I will have to do it again at some point in my career.

## Usage

```js
import { h, Component } from 'preact'
import Carousel from 'preact-flickity-component'

export default class CarouselContainer extends Component {
  render (props, state) {
    const flickityOptions: {
      pageDots: false,
      wrapAround: true
    }

    return <Carousel className="Slider" options={flickityOptions}>
      <div>1</div>
      <div>2</div>
      <div>3</div>
    </Carousel>
  }
}
```

## License Information:

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.html)

Flickity may be used in commercial projects and applications with the one-time purchase of a commercial license.
http://flickity.metafizzy.co/license.html
