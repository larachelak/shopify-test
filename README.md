# First + Third Shopify Developer Challenge
# What I did
I this test build I decided to implement a very basic PDP with a slider. I chose Swiper as it's a performant option that doesn't cause as many layout shift issues as other libraries.

I decided to include only some of the product data, to keep the UX light and clear. There is minimal styling involved but I chose to use BEM style CSS to keep everything organized nonetheless. I added a few quick utility classes as well, even though they're only implemented once in this case (force of habit!). Also, this project was obviously a little harder to debug, due to it not being a standard Shopify build. I had some issues with getting the `| money` filter to work.

My favorite part was actually seeing all of the data in an easily referenced .json file!

# What I would have done differently (if this were a real Shopify them)
* Include functionality to change the featured image on variant selection/change assuming that there were options for Color on an actual build.
* Add a .favicon, analytics, and schema markup specific to the PDP.
* Would use more custom utility classes to keep dev time low if they were used throughout the site.
* Would setup webpack, build processes, nesting, and npm based implementation rather than directly embedded scripts via CDN.
* Would probably avoid jQuery in the future but wanted to choose something quick in this instance.
* Would add stock detection for each variant option, not just at the top level product, to disable variant selection for out-of-stock variants.

Thank you!