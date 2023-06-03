# Practicum Coffee Shop

This is the second project of the Web Development program at Practicum. It was created using HTML and CSS, based on the design brief.

## Project features

- Semantic HTML5
- Flexbox
- Positioning
- Flat BEM
- A custom form
- CSS animation and transform

## Plan on improving the project

<!-- - Part of the html structure is unclear. like the class="footer**social-heading" part, it supposes to has a container to wrap it with the class: "footer**list" container together, then the final outcome start to close to our giving brief demo. According to our current required syntax structure, I tried 10 times and failed 10 times. --> After calming down and anylizing the syntax structure of these two parts, I start to realize that maybe the "positioning" will be good to make them work. Bravo!!  I finally MADE IT!! I set positioning for the two containers: "footer__social-heading & footer__list" resepctively, and they are just right to put there.

- Speaking of the Menu and Footer part, what are the proper background height we suppoe to give? There is no reference value here. In my work, I gave them 50vh and 35vh resepctivly, and both of the sections' appearance proportion are as same as our giving demo.

- Since I removed all of the sections.css out of the index.css, and only left a bunch of @import url() outthere, the submit robot of this project didn't accept my work and shows a sentence like this: "The blocks folder is missing the following files: card.css, form.css, nav.css."

- like the background dimention of menu section, the proportion of its final work looks a little bit deform on the height direction. is it the value of its height too samll to make it right, or the giving dimentions for each of the elements in the block is too big. Hence. it's overflow after adding them up. Or, some of the css rules are incorrect cuz it overflow.
