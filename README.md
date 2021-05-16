# Variable Fonts exercise

Update the typography so that it matches this screenshot:

<img alt="Desktop-sized screenshot of a site footer" src="./docs/mockup.png" style="" />

**The bulk of the styling has already been completed;** your goal is to add a variable web font to the project, and update the typographic styles to match.

Don't worry about mobile styles; this challenge is purely about the text.

## Setup Instructions

Because this project is pure HTML and CSS, you have two options:

1. You can open the `index.html` file directly in-browser
2. You can run `npm install` to install the `serve` dependency, and then run `npm run start` to start a local file server.

In order to keep things as simple and robust as possible, no hot-reload tools are being used.

## Finding the font

The font needed is called “Raleway”. You have two choices for how to use it.

### From Google Fonts

Raleway is hosted on Google Fonts at the following URL:

https://fonts.google.com/specimen/Raleway

Be sure to grab the variable font, below the individual weights and styles. You can read the docs about how to embed variable fonts here:

https://developers.google.com/fonts/docs/css2

(Their docs are a little unclear about how to include both weights _and_ italics. We'll cover this in the solution video, so don't worry too much if you can't figure it out.)

### Custom Embed

You can download the Raleway font package, including the variable font, from the foundry's site:

https://www.theleagueofmoveabletype.com/raleway

You'll want to use the `.woff2` font file, following the `@font-face` instructions in the course.
