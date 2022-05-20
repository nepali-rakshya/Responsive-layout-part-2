As we know that, 1vh and 1vw means 1% of height and 1% of width of the browser window respectively.

vmin and vmax performs similar functions but with some different concepts.

# VMIN :

# In case of vmin it checks whether the sides of the browser window that is the height or width is minimum and acts accordingly. if 1vmin is being given then whichever side whether be it width or height is smaller it occupies 1vw or 1vh for it.

# VMAX:

# Now vmax is opposite to the vmin. if 1vmax is given then it checks which side is larger either width or height then it goes along with the larger side.

<!-- !IMPORTANT NOTES!!! https://www.youtube.com/watch?v=waiZqfefo14&ab_channel=Minim -->

1. if the size of the viewport is 800px wide then width of 1vw is 8px.

2. 1vw is the 1% of the actual viewport and 100vw is 100% of the actual viewport.

3. Even in case of font sizes, the font size with the width of --vw adjusts according to the viewport of the browser window.+

<!-- ! Yahooo baba <3 https://www.youtube.com/watch?v=2CW2B7W4Vas&ab_channel=YahooBaba> -->

1. For instance,
   if width = 50vmax;
   it means, whosever size either be it width or height is bigger will be 50% of the viewport which will be the width.

<!-- Mostly used css properties are vh and vw, vmax and vmin aren't mostly used as they need a lots of testing and need to be watched carefully for their usage. -->
