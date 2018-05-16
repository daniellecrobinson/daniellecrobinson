Hey! This is where I am playing around with [Enoki](https://github.com/enokidotsite) to make a personal site. 
This site is based on Enoki / Jacinto. 

I've moved away from panel.enoki and I'm just editing my files locally. 

The first thing I wanted to do was remove the date stamps from the blog. It didn't make sense for me to have dated posts, but when I deleted them the website wasn't happy. I asked for help to figure out where dates were required and deleted a line from entry.js `<li>${date}</li>`
I also needed to add a `.datignore` file as the earlier enoki I was playign with didnt have one. 

## From Enoki:

Includes [Choo](https://github.com/choojs/choo) as a front-end framework, and [Sheetify](https://github.com/stackcss/sheetify) for css-in-js 

### Customization

If you created your site from the Enoki Panel, `cd` to the `source` directory and run `npm install`. Once the dependencies are installed, run `npm start` for development and `npm run build` for bundling.

To stay up to date, clone the [repository](https://github.com/jondashkyle/enoki-design-vacany) and `git pull origin master` changes.
