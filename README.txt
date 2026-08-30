NSR AUTOMOTIVE — FREE STATIC WEBSITE

FILES
- index.html — complete website (HTML + CSS + JavaScript in one file)
- images/nsr-logo.jpg — logo image

PUBLISH ON NETLIFY
1. Log in to Netlify.
2. Open https://app.netlify.com/drop
3. Drag this whole folder (or ZIP contents) into the drop area.
4. Netlify will give you a live .netlify.app address.

EDITING
Open index.html in a text editor. Search for the exact heading/text you want to change.
Phone: +91 98201 29679
Email: nitish.nsrauto@gmail.com

PHOTO GALLERY
The gallery currently contains clean placeholders because the uploaded screenshots are website screenshots, not actual workshop photographs.
To add real photos:
1. Create images/gallery1.jpg, gallery2.jpg, etc.
2. Replace each <div class="gallery-item">...</div> with:
   <div class="gallery-item"><img src="images/gallery1.jpg" alt="NSR Automotive workshop"></div>
3. Add this CSS if needed:
   .gallery-item img{width:100%;height:100%;object-fit:cover}

Then drag the updated folder to the Netlify site's Deploys page to publish the update.
