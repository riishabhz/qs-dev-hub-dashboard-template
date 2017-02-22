# qs-dev-hub-dashboard-template
DAR template for Qlik Sense dev hub


## FAQ

**How do I add or remove cards from the template**

DAR template is based on Bootstrap, it works with a simple row column system, please check http://getbootstrap.com/css/#grid for more info.

**My charts doesn't have title how do I adjust them to the cards?**

Locate your chart ID and remove "with-title" class from it

**I want to change KPI colors, how can I do it?**

DAR template ships with a prebuilt CSS color library (lines 302-359 in dashboard-template.css). To change colors you just need to update dashboard-template.html kpi class based on your preferred color.

**Can I customize the icons showed in the mashup?**

Sure you can. Icons are obtained from fontawesome.io icon font library, to update it and get your custom icons visit fontawesome.io and pick your favorites, then just update the icon name into the html file.

**I would like to use my custom font**

We are using google fonts to obtain a custom font. Feel free to update it, remember you should update the font name in the HTML file and then search and replace the font name in the css file as well.


**Known errors**

Misplaced selections bar
# Don't click on show selections bar or the selections toolbar will be misplaced.
