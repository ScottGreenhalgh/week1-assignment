# week1-assignment

recreate the SpaceX website

<!-- Reflection

Main Thoughts

Creating the project initially was an interesting challenge.
Throughout the week we dabbled with various different css elements
which made creating the page itself relatively easy.
Each component covered throughout the week was in one way or
another used during this project.Flexbox and the positioning in CSS made
 structuring where each element sat on the page very easy to configure.

In terms of HTML, since this was a recreation of an existing page, this
part was relatively simple. All the content needed was already avaliable,
it was a just a choice of how to structure each element. I initially made
the choice to have two distinct sections in the body element, on for the
navigation bar and the other for the text and imaging. Using div elements
to further style this later down the line.

Errors and Bugs

As for the buttons on the page. I noticed very quickly that <a> elements
were needed for the clickable segments of the page that handled scrolling.
What I didn't immediatly clock was the buttons themselves should've also
been <a> rather than buttons to represent the sample page better. While
I could've ran with this design and added what I wanted it to do with
JavaScript instead, I opted to remain with the CSS and HTML elements. This
meant a little redesign of the CSS was necessary since I applied styling
directly to the <a> elements, a slight oversight.

A huge hurdle I encounted when styling the page was with position: fixed
sitting behind my position: relative elements. This was a major headscratcher
for a good while, but after a short google search and browsing a few
articles, I came across something called z-index. This is something I didn't
consider a 2D page would have. The Z axis is usually reserved for 3D elements
but here it makes perfect sense with layering.

I also noticed towards the end of my project that on mobile aspect ratio
the navigation element would wrap to the next line, damaging the style of
the page. This was not present on the sample, so I added prevented text
wrapping for this element.

There is one current bug. The audio I'm grabbing doesn't always load with
the page. It sometimes does and other times doesn't. Likely an issue with
my chosen source. I attempted adding the audio to Google Drive and importing
that this way (found at https://drive.google.com/file/d/1wHXKc91ivGzG_Mb9kxvee7AuKN20LozT/preview) however this method didn't work
at all. In future, I will probably consider adding local media to the
project instead.

Sources

I sourced a materials for this project. Google images for the background
images and soundimage.org for the royalty free audio sample. I then obtained
the social media icons from tablericons.com

Possible improvements

Another avenue I could've explored was text-transform: uppercase;
This is something I didn't use during the project simply because I
quickly noticed that all the text on the page was capitalised. In
retrospect, if I was to make this page again I would utilise this to
allow me an easy toggle between the two options.

There are a few text sizing readjustments that can be made to better
reflect the sample. The alignment of all the elements are also not
perfect but the generally represent what the sample page represented.

Conclusion

Overall I believe the recreation of the sample page I created is very
similar to the sample given. There are some very slight text size differences.

-->
