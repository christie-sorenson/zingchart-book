# Custom Charts

So you’ve decided to buy ZingChart and make our charts part of your app or website. Congratulations! Now we can help you take your custom charts to the next level. We’re sharing information on how to make your charts match your company’s branding even more closely.


ZingChart offers granular styling for nearly every chart element. This allows you to customize charts in very detailed ways. For example, you can match colors and other branding elements from your company. Our JSON syntax does a great job of laying out exactly what can be customized and how, in terms of chart elements.

But ZingChart allows more customization beyond colors and sizing.


## Custom Charts: Options


### Watermark


The ZingChart logo appears as a watermark at the bottom-right corner of our charts. It appears by default on all unlicensed charts when loaded into the web browser.

![](../images/context-menu.gif)

To remove the ZingChart logo watermark, you will need to buy a license key. Once you have your license key, set it in the `ZC.LICENSE` variable, e.g., 
`ZC.LICENSE = ["569d52cefae586f634c54f86dc99e6a9"]`.

If you still see the watermark, make sure the key is placed before the render method. Also, double check that it is placed in every page that renders charts.

### Custom Chart Context Menu
In ZingChart, users can right-click on a chart to access a menu of extra options. We call this the context menu. By default, “About ZingChart” appears as the last item in the menu on all unlicensed charts. You’ll see this when your chart is loaded into the web browser.