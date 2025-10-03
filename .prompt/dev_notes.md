--
Prompt 1:

"Swap the content of Homepage and About Me (I mixed them up). Then, in the homepage, within the main body, include the following context:

[My bio]

You have the creative freedom to try creating placeholders for a little bit of additional content within the page. You can take inspiration from your understanding of design for professionals to showcase themselves via a personal website to inspire any potential changes to this home page."

AI Output: 

"Reviewing the current structure to swap the Homepage and About Me content, then updating the homepage with your content.
Swap content between Homepage (index.html) and About Me (page1.html)
Update homepage with personal content about B.S. in Supply Chain Management and MSIS program
Add professional design elements and placeholders for additional content
Swapping Homepage and About Me content, then updating the homepage with your content.
Moving the dog content to the About Me page (page1.html).
Fixing the typo in page1.html.
Adding CSS for the new homepage sections."

Notes: I wanted to see how the AI (Cursor) would do if I gave it creative agency. Giving it a point of comparison seemed to aid in coming up with something interesting and aesthetically pleasing. It mixed up some navigation links in the process, but that was partially due to my changing the names in the files but not the .html's themselves. Also, some additional visual adjustments were needed.


--
Prompt 2:

"Now, on the Projects page, I want to showcase projects I have worked on. I've included three pdf's for this (they are the 3 in the content folder that are not the resume). Please showcase each of them on the page.

The process analysis one can be called "Operational Analysis of a Local Business"

The mind maps one can be called "Idea Mapping and Sustainable Energy"

The ITS-CA2 one can be called "Case Analysis of Kroger and Generative AI""

AI Output:

"Updating the Projects page to showcase the three projects using the provided PDFs.
Update Projects page to showcase three projects with embedded PDFs
Add project titles and descriptions for each PDF
Create professional layout for project showcase
Adding CSS for the projects layout.
Update Projects page to showcase three projects with embedded PDFs
Add project titles and descriptions for each PDF
Create professional layout for project showcase
Updated the Projects page to showcase your three projects."

Notes: The AI did a reasonably good job of satisfying my ask. There were some visual adjustments needed following this guidance, so I put Cursor in Ask mode and essentially asked it for advice on what it would recommend doing. The first two options were non-starters from a design perspective, but the third one -- arranging the displayed projects into twos if the screen was beyond a certain width -- made sense, so I made additional adjustments to accommodate that.


--
Prompt 3:

"Ok. Now, for the contact form, please include an aesthetically fitting section at the top to include links to my LinkedIn, email, and Github. Then in a separate section, have a cleaner version of the existing contact form. Submission (which should work if all fields are filled out as it does now) should reference the user to a "thankyou.html" page."

AI Output:

"Updating the contact page with a contact info section and a cleaner contact form.
Update contact page with contact info section and cleaner form
Add LinkedIn, email, and GitHub links section
Create cleaner version of existing contact form
Ensure form submission works and redirects to thankyou.html
Updating CSS for the contact page.
Update contact page with contact info section and cleaner form
Add LinkedIn, email, and GitHub links section
Create cleaner version of existing contact form
Ensure form submission works and redirects to thankyou.html
Updated the contact page with a contact info section and a cleaner form."

Notes: Like in the above prompt, the AI did a reasonably good job. At this point, I notice it tends to struggle to properly understand spacing. I had that same problem working with Cursor this last summer as well. Getting spacing right in HTML/CSS is inherently finicky. That said, I subsequently adjusted the layout of the page, and I've learned over time the importance of structuring your styling before getting into the finer details, because if you don't, it can take a very long time to get all your content aligned properly.


--
Prompt 4:

(In Ask mode) "Now, can you do a general evaluation of the codebase to see how the webpages would be viewed across different types of devices? Obviously I want to make sure that content is represented in a visually intuitive way regardless of laptop vs. tablet vs. phone viewership."

AI Output (just the summary part):

"📊 Overall assessment
Score: 8.5/10
✅ Good breakpoint coverage
✅ Logical layout changes by device
✅ Consistent behavior across pages
⚠️ Missing viewport meta tag
⚠️ Touch targets could be larger
⚠️ No fluid typography
The site is responsive and usable across devices. The main gaps are the viewport meta tag and touch target sizing."

Notes: After this, I had the AI make some adjustments based on what it flagged. I figured it would give a better result if I had it conduct a holistic analysis and then try to make adjustments, rather than asking it to do so in Agent mode outright. It struggled for a bit to find the actual root cause because it would latch onto the first probable thing it could find. But after asking it to examine ALL relevant code, it correctly identified and corrected the spacing errors.


--
Reflection: AI was a significant time saver for this project. I did not have to manually write a large amount of code, although I learned HTML/CSS fundamentals in S310 which helped when I did need to. Cursor is particularly capable for this type of design. Although we were given a wireframe to build out this assignment, the AI did a good job of handling the minutiae involved in writing syntax. For example, it knows how to easily embed a pdf, whereas I don't have the experience to know something like that off the top of my head, and it may take me time to figure out how.

As I've said before, the AI mainly made mistakes with spacing. Sometimes, the styling choice would be poor, it would misalign content within a certain subsection or visual "box", or it generally would fail to optimize to screen sizes. These can be corrected in part by using ask mode in the appropriate way, in part through effective prompt engineering, and in part through manual adjustments to structure. That is where the manual component of coding came in -- fixing small things the AI may overcomplicate, and helping to establish the baseline structure for it to act on.