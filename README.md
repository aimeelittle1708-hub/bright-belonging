# bright-belonging
🌈 Bright Belonging — Sensory-Inclusive Guidance for Parents & Teachers

Bright Belonging is a fictional educational website designed to help parents, teachers, and caregivers understand and support the sensory needs of children in inclusive environments. This repository contains the source code, content, and design assets for the site.

<h2>⭐ Primary Goal </h2>

Bright Belonging aims to make sensory inclusivity accessible and easy to understand. The platform provides clear, research-informed guidance so adults can create environments where every child feels safe, supported, and able to thrive.

<h3>Business Goal </h3>

Showcase the resources avaliable
Provide essential information
Equip adults with practical, evidence-informed tools
Promote awareness and inclusion
Encourage group visits + event participation
Support inclusive educational practices for all children

<h2>User Personas </h2>

[ ] As a young person with sensory differences I want clear explanations of sensory terms and self‑help tools so that I can better understand and communicate my needs.

[ ] As a parent I want to find local support groups, therapists and events near me so that I can build a local network of help.

[ ] As a classroom teacher I want downloadable lesson plans and activity modifications so that I can include students with sensory needs easily.

<h3> User stories <h3>
<img src="assets/images/user-stories.png">


<h2>UXP design choices </h2>
<p>The completed 3 day sprint was composed of 6 separate items taken from business goal and user personas. Having used the MoSCoW approach to prioritisation, a Kanban board was created. 4 issues were classified as "Must-Have" making up less than 60% of the tasks as recommended. The rest of the first sprint was made up of "Should-Have" and "Could-Have" items. There were 0 remaining backlog items.</p>

<img alt="bb kanban" src="assets\images\bb-kanban.png">

<h3>Wire frame designs</h3>
phone=
<img alt="wireframe for phone" src="assets/images/wireframephoneBBnoback.png"/> 
Mediumn screens and tablets=

<img alt="wireframe for ipad and medium screens" src="assets/images/new-wireframe2.png"/>

Desktops and large screens=

<img alt="wireframe for desktop and large screens" src="assets/images/new-wireframe3.png"/>

The site layout will look like this
<img alt="nav tree" src="assets/images/treeofpages.png"/>

<h3>Colour pallette</h3>

Color pallette selected and check for WCAG standards to ensure accessibility.
<img alt="pallette evidence" src="assets/images/newpallet.png"/>
Checked with https://colorlabs.net/ 

<h3>Fonts</h3>

<h2>Features </h2>

<h3> Home page </h3>
Homepage showing;
-nav bar, subscribe button in prominant place with clear accessible colours and high quality images.
<img src="assets/images/homeshot.png" alt="home page">
Clearly defined Events in a table with map location and booking form button.
<img src="assets/images/eventsshot.png" alt="events">
Booking form button will lead to form page
<img src="assets/images/bookingshot.png">
Which when completed will lead to a "Success page"
<img src="assets/images/successshot.png">
About with cards shoing strategies for different possible difficulties children may face.
<img src="assets/images/aboutshot.png" alt="about">
Resources Page
<img src="assets\images\resourcesshot.png">
Footer with clear contact information which appears on all pages.
<img src="assets/images/footer2.png" alt="footer">
Finally, a modal pop up which also links to the success page which the subscribe button is clicked.
<img src="assets/images/modalshot.png">

<h2> Future features </h2>
<p>On returning to this project, items I would like to include would be; 
</p>
<ul>
<li>Blog page- to add own articles </li>
<li>Rolling carousel of images in the header of the homepage </li>
<li>Bank of reources to download</li>
<li>links/ embedded youtube videos </li>
<li>Related games for neurodiverse children </li>

<h2>Use of Copilot and AI tools</h2>
<p>The use of generative AI played a key role in the development of this project. AI allowed me to stay efficient and keep working to deliver maximum output on the short deadline that this assignment had:</p>

<h4>Image Generation:</h4> 
<p>I used AI to generate a variety of photos to fit the needs of the project using specific prompts to extract what I needed from Chat GTP.</p>

<h4>Text Content Creation:</h4> 
<p>I used ChatGPT to help me draft the content for the cards and the header text for each page.</p>

<h4>Layout and Scaffolding: </h4>
<p>When dealing with complex layouts, I asked Copilot to generate me the rough grid structure in HTML and Bootstrap classes. These often has small styling issues, so a full understanding of Bootstrap and HTML was required from me in order to tweak the styles to exactly how I wanted them.</p>

<h4>Code Corrections & Readability </h4>
AI tools suggested cleaner code syntax, helping to correct small errors that affected functionality.
It also improved readability and consistency, ensuring the HTML and CSS followed semantic and accessible coding standards.
This made the project easier to maintain and validate using standard tools.

<h4>Encountered Problems </h4>
<p> I had originally tried to use a carousel of images in the header, but this created problems afterwards. I tried using AI to fix these issues, however it added lots of custom CSS styles which conflicted with the Bootstrap classes. I decided to revert back to the page before I added the carousel.

<h2> Testing </h2>
<h3>Reponsive tesing </h3>
<p> Alongside the built in Bootstrap responsive CSS, Chrome dev tools were used frequently to test the site at standard screen sizes and the site was manually viewed on laptops, tablets and phones. </p>


<h3>Lighthouse testing</h3>
<p>Light house performace testing showed 99 rating</p>
<img alt="lightouse score 99" src="assets/images/lighthousescorebb.png">
The lower score when checked for Best practises was because third party sources were used- ie-google maps.
<h3>Validator testing </h3>
HTML validation shows 2 errors to do with the map.
<img src="assets/images/htmlvalid.png"> 
 No errors found in CSS when validated.
<img src="assets\images\cssvalid.png">
<h2> Deployment</h2>
<p>Hosted on GitHub Pages.
Version controlled with GitHub.
Static-only (no backend required).</p>
