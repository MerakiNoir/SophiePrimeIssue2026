BELLA'S BIRTHDAY WEBSITE
========================

HOW TO PREVIEW
1. Extract this ZIP folder.
2. Open index.html in Chrome or another browser.
3. Scroll down to the letter section and click the envelope.
4. The envelope opens, butterflies fly out, and the letter appears.

HOW TO ADD BELLA'S PHOTOS
1. Put three photo copies in the same folder as index.html.
2. Name them exactly:
   bella-1.jpg
   bella-2.jpg
   bella-3.jpg
3. Open index.html in Notepad.
4. Find each photo placeholder section and replace the placeholder <div> with:
   <div class="photo-placeholder"><img src="bella-1.jpg" alt="Bella photo 1"></div>
   Change the filename for the second and third photos.
5. Save the file and refresh the browser.

You can use .png instead, but update the matching filename in index.html.
Use photos Bella would be comfortable having on the website. If you publish it online,
remember that anyone with the link may be able to view it.

PUBLISHING WITH GITHUB PAGES
1. Create a new GitHub repository.
2. Upload index.html and the three photo files.
3. Open repository Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish the site and open the generated website link.

The fonts are loaded from Google Fonts when online; the site has fallback fonts too.
