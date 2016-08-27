# board  
_A surfbird is nothing without its board!_ 

Default theme of Surfbird, can be used as theme scaffold.

## Prerequisites

* Node.js (really, just any version should be fine)
* Gulp (`npm i gulp --global`)

If you don't want to use Gulp to compile the assets you can also
use tools like [Prepros](https://prepros.io/) (the trial really is enough for stuff)

## Getting it to work

_This is mostly for theming purposes, the actual building is in the main Surfbird repository_

* `npm install`/`npm i` to install needed assets and packages
* `gulp sass` to compile the style.scss into `dist/style.css`
* `gulp watch` to compile `style.scss everytime a file changes

If you want to add a new component or extra file, add it as
`components/_componentname.scss`, the underscore prevents the
file from being compiled as a seperate file. Then don't forget
to import your new file in `style.scss`!

## Theming

The most basic theming of board can be done with just looking at every 
component and changing the variables on top (the names should be descriptive
enough), if you want to delve more into changing specific parts about it, 
just go ahead and do it, scroll down and see everything!

## Contribute

Found a mistake in the style? Anything you think that would look way better?
Don't hesitate to make a Pull Request with your changes or open an issue to
discuss certain parts of the design!

Made a nice theme? Go ahead to [the website repository](https://github.com/surfbirdapp/website) 
and open an issue to be added to the theme listing!

## License

board is licensed under the aGPLv3 license.


