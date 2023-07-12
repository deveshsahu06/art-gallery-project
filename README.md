# Virtual-Art-Gallery
You need to create an unordered list of your images.

<ul>
   <li>
       <img alt="Night away"  src="images/photodune-174908-rocking-the-night-away-xs.jpg">
       <p>Optional text. This will also show in the modal</p>
   </li>
   <li>
       <img alt="Yellow boy" src="images/photodune-287182-blah-blah-blah-yellow-road-sign-xs.jpg">
   </li>
   <li>
       <img "Some colors"  src="images/photodune-460760-colors-xs.jpg">
   </li>
</ul>

1) The Modal box that opens is always going to be the large modal. Images will scale up to 100% to fill the entire modal box. You still have the option of having a small thumbnail and linking to a different image for the large size  mainly for performance purposes.

2) A new plugin option called "fullHeight" that allows you to have different heights in the thumbnails inside the grid. Most people want to see uniform heights, so I default this value to "true". If you want to see dynamic heights, simply set this to "false". Note that this doesn't affect the modal images.

3) I've separated the styles into it's own stylesheet.Now have to include this stylesheet in your document or you can simply copy the contents into your own stylesheet. I tried making everything inline so you only have to include the JS file but it have been growing and having an external CSS is the only way to manage.

4) Added glyphicons for the "Next" and "Previous" links in the modal. This just looks better.

5) Images are required to have an alt tag, so I'm outputting the value of this into the modal as the title.

6) Now we can have additional text underneath the grid thumbnails by having a "p" tag with a class of "text". I grab this value and put it in the modal as well and also give it by name so that the image looking good.

