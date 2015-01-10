# Embedding a chart in your Content Management System

## Making a chart using highcharts.js

Make a chart using the highcharts.js library. You can browse examples at [highcharts demos page](http://www.highcharts.com/demo). Once you have selected the right chart, use the "Edit in JSFiddle" button to customize your chart.

Once you have changed the data of your chart and tweakded its look-and-feel, you can copy the JavaScript portion of our JSFiddle and paste it into the designated area in your chart.html file. Then upload the chart.html to a public server and grab the public link.

It could look like this:
```
http://yoursite.com/interactives/2015/01/chart.html
```

##Embed code

You can use an `<iframe>` to embed your chart in your CMS. Copy the code you see below and replace the link in the tag attribute `src="http://yoursite.com/interactives/2015/01/chart.html"` with your link.

Paste this `<iframe>` into your Wordpress article page as HTML code. What this does is that it loads your chart into a window that is the width of the page and at a height of 400px, the same height that is specified in your chart.


```
<iframe src="http://yoursite.com/interactives/2015/01/chart.html" style="width:100%; height:400px">
</iframe>

```

Enjoy!

*This was developed for participants of the Alaska Press Club data journalism workhop, held in Anchorage, Alaska, Jan. 5-9, 2015.*