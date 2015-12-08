# Pretty Good Base Theme Orchard Theme How to...



This section deals with common scenarios you could encounter when you use PGBT as a base theme.


## ... use a custom favicon?

Just add a favicon.ico to the root of your theme's Images folder. **Actually for the sake of simplicity, please do add a favicon.ico to your own theme even if you use the default one** (just copy-paste the default one from the PGBT folder), otherwise a non-existent icon will be included!


## ...add own global shapes?

Place an Insertions.cshtml template into your theme's Views folder. This will override the default Insertions.cshtml. Look into it for how to add new shapes to the layout. If you want to keep the defaults, you should override AdditionalInsertions.cshtml.


## ...include own resources (stylesheets, scripts)?

Place a Resources.cshtml template into your theme's Views folder. This will override the default Resources.cshtml. Look into it for how to add resources to the document. If you want to keep the defaults, you should override AdditionalResources.cshtml.


## ...override or enhance default styling?

You have two options:

- If you want to add to the default styling and just want to override some properties, then just make a stylesheet Site.css in the root of your theme's Styles folder and write your styling there. As this stylesheet is included last, you can override anything.
- If you are dissatisfied with a bigger part of the styling, it's maybe better to completely override some stylesheets. Have a look at the Styles folder of PGBT. You can see a good number of stylesheets, each dealing with a specific part of the site's styling. You can completely override a stylesheet by placing your own one with the same name into your theme's Styles folder.