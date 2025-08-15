# my-website

Issues about the website that have been noted for improvement:

1. Issue with viewing the website on mobile (360px) - the text very small and it is hard to read

2. The second thing I would recommend is making the Wikipedia link more of an obvious link rather than it looking like a link to another page inside the website.

Adjustments made to correct website issues:

1. For the first issue the website's media queries have been adjusted to maintain a minimum pixel width for the images at 55px. The font sizes for the headers, paragraphs, and navigation links have had their clamp minimum set to 0.5em to maintain at least 8px size no matter what the size of the screen. Most of the remaining content is adjusted appropriately at the smaller screen sizes.

2. To help distinguish this link I included new pseudo-class adjustments to the link stylings and included the favicon used by wikipedia in front of the word in the navigation link.