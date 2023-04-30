HOW TO MAKE A WEBSITE WITH NAMECHEAP
=========================================

Common Cents Party
--------------------
The band, Common Cents Party, has asked you to work on two webpages for their website. Now that you have been introduced to some fundamental HTML elements, you are ready to help the band. Let’s get started.


Start by creating the page structure.
-------------------------------------

In index.html, there are currently three divs on the page. The div with class container has two children. Set the class of the first child div to nav. Set the class of the second child div to main.



<div class="nav">
 
</div>
<div class="main">
 
</div>


Inside the div with class nav, create an h4 element which displays “Common Cents Party” to serve as the navbar heading.

<div class="nav">
   <h4>...</h4>
</div>

Below the h4, create a ul element with li items for different pages the site offers:

Home
Shows
Albums
Gallery
Bio
Blog

<ul>
   <li>item 1</li>
   <li>item 2</li>
   <li>item 3</li>
</ul>

The ul will be inside the div with class nav, one line below the closing </h4> tag.

Next, inside the div with class main, create an h1 heading element that displays “Common Cents Party”.

<div class="main">
   <h1>...</h1>
</div>

... is a placeholder for heading text.

Below the h1 heading, create an image element that has the following image URL as its src attribute:

 https://content.codecademy.com/projects/make-a-website/lesson-1/band.jpg

Here is a reminder of how to create img elements:

<img src="..."/>


... is a placeholder value. Your src value will need to be the image URL listed above. Also, don’t forget to put the image URL in quotation marks!

Below the image of the band, create a paragraph element to include a recent review:

“Common Cents Party, a hard-hitting acoustic punk/electronic four-piece from Atlanta, Georgia, combines an unleashed live performance with edgy lyrics, unforgettable hooks and well-studied synth-rock sounds. A must-see, must-hear new band.” -Screech Magazine

p elements have an opening <p> and a closing </p> tag, with text in between.

After creating the p element, there should be three elements inside the div with class main:


h1 heading
img that displays a photo of the band
p which displays the Screech Magazine review


Next, create an anchor element that links users to a list of the band’s upcoming shows.

The href attribute for the anchor element should be set to shows.html. The text for the anchor could say “Here’s a list of upcoming shows”.

Test out your anchor element in the web browser.

<a href="shows.html">Here's a list of upcoming shows</a>

You can add the anchor element one line below the closing </p> tag.


The band has asked you to include video from a recent live performance.

In the file shows.html, below the h1 heading that displays “Upcoming Shows”, create a video element.

Play with the height and width attributes until the video’s size looks right to you. Then, set the video source to:

 https://content.codecademy.com/projects/make-a-website/lesson-1/liveshow.mp4 

Play the video in the web browser to make sure it works.


Below is an example of how to create a video element:

<video width="450px" height="350px" controls>
   <source src="..." type="video/mp4">
</video>


... is a placeholder value. You will need to replace it with the video URL. Don’t forget to put the video URL in quotation marks!”



















