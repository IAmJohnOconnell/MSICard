# MSICard

This is a relatively simple card made with HTML and CSS.
It was fun to build and required some careful consideration of how the component might be implemented in a production envionment
in order to determine the proper semantic elements to use. 

I interpreted this card as one component in a larger UI, so my tag 
and styling choices are with a modular, potentially, dynamic approach in mind.

I took a few small creative liberties by wrapping some text elements that were a bit long in 
certain cases, as well as a subtle border to add some seperation between list elements. 
These can be easily removed in favor of the pixel-perfect version, if that is preferred.

Most of these changes are handled with flex-wrap and a media query.

I had some trouble finding some good icons without spending too much time on them. 
So I found a few that I liked and used a CSS filter to make my icons more accurate to the spec.

When troubleshooting the responsiveness and mobile styles, I discovered that the responsive mode in the dev tools 
differs slightly from the actual layout on mobile devices. I use a smaller device, so I was pleasantly surprised 
to see the layout looking far more representative of the spec than was reflected in the browsers dev tools.

My guess is that this is caused by either browser vendor quirks, or most likely, the screen size of my mobile device (IPhone 13 Mini) 
and the smallest screen size in the dev tools (Mobile-S 320px), may differ slightly.
