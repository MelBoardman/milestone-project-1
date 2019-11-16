Milestone Project 1

Build a website for The Gym
•	Product Objectives
    o	Attract and retain customers.
•	User Needs
    o	The site's users are gym members and potential members, who want to know more about the gym and its procedures.

UX

SCOPE (CONTENT REQUIREMENTS - WHAT PEOPLE WILL VISIT THE SITE TO FIND OUT)
•	Gym Information (primarily for attracting new customers)
    o	About (ethos)
    o	Aims (how it differs from competitors)
    o	Unique Selling point (USP)
•	Opening Hours
•	Contact Information
•	Class information
•	Class timetable
•	Membership Options
•	Location information 

STRATEGY (WHAT WILL BE ON EACH PAGE AND HOW TO NAVIGATE THE SITE)

•	Home page (Fun, attractive., retain interest, contain most things users are looking for.)
    o	Gym images – possible image carrousel
        	CTA – take to gallery page
    o	USP - What makes this Gym special. Just few sentences
        	CTA – join our Gym - About
    o	Contact information and opening hours
        	Location Information 
        	CTA – take to Contact us page

•	About
    o	Membership options 
    o	Class information
    o	Downloadable Class timetable

•	Gallery
    o	Images of people working out
        	Use Fancy box
        	Maybe add a CTA to Membership
    o	Videos (optional)

•	Contact Information
    o	Manager details
    o	Phone number
    o	Email address
    o	Location information Embedded map
    o	Ask us / get in touch form – email phone number etc.. (include check for correct information, however, does not need to be functional)  


Navigation – Nav bar with links to all pages on each page.

See /assets/milestone-project-1-planning-doc.docx for information on the UX design process and wireframes etc

FEATURES
    Navbar
        Allow users to navigate to each page of the site. This is the same on each page aside from the active page setting. I utilized bootstrap navbar components to construct this. 

    Home page
        The aim is for this page to be attactive and keep the user interested. So at the top I added an image carosel, using bootstrap.
        https://getbootstrap.com/docs/4.3/components/carousel/ (with indicators)
        
        below this I added a button link to the Gallery page - This button is not a primary focus of this page and therefore is smaller and is the same colour as the background until hovered over.  
      
        Next I wanted to give a snippit of information about the gym to give the user a feel for it without including to much information. Then the button below this takes the user to the about page where they can find information about the membership options and classes.

        It was important for the user to find the information that they are after as quickly as possible and so I have included the location and contact information on this page also. 

    About page
        The aim of this page is to provide information regarding membership and classes. I decided to not inlude any images on this page to allow the information to be clear and simple without distractions. This is inkeeping with the desire to have a simple minimalist feel and allow the site to be easy to navigate and understand for the user whist remaining stylish.

        On this page I have made use of the bootstrap grid to allow items to be displayed nicely on differnt devices.
        I decided to add colour and invert the text to highlight each item as it is hovered on using CSS3. I believe this improves the users experience when viewing the information.

        There are 3 membership options and beneath these I have added a button that leads to the contact us page. A future enhancement would be to have the contact us form as a pop up from this button.

        Below this is the Class information. This lists the classes and information about each one.
        I was initially going to include the timetable on this page but during development I decided that this works better as a PDF. Therefore the button below the class information opens the PDF in another window. 

    Gallery
        I decided to include a gallery page with all the images accross the site and some additional  to motivate and encourage exisiting and new members. I have used fancybox to create this. 
        
        A future enhancement here could be to display these a little better and perhaps add some videos. 


    Contact
        Gym image with 'contact us' over it.
        emmbedded google map.
        contact details.
        Contact form.


Contents
In this section, you should go over the different parts of your project, and describe each in a sentence or so.
Existing Features
Feature 1 - allows users X to achieve Y, by having them fill out Z
...
For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.
In addition, you may also use this section to discuss plans for additional features to be implemented in the future:
Features Left to Implement
Another feature idea
Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.
JQuery 
The project uses JQuery to simplify DOM manipulation.

TESTING

**Create validation plan spreadsheet to go through each feature/function and expected outcome. Test in each different screensize and complete. 

Add validation spreadsheet to GIT Repository.

click on each link from the nav bar from each page to ensure the correct page was displyed.


In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.
Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.
For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:
Contact form: 
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.
You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.
If this section grows too long, you may want to split it off into a separate file and link to it from here.

DEPLOYMENT

For this project I have used GitHub pages to deploy the site.
when I started to create the site I used created a github repository and thoughout the development I have periodically added and commited changes. 
It is a straight forward process to deploy a GitHub repository to GitHub pages.
I Logged in to the git hub website and selected the correct repository 'the-gym'. 
On the settings tab I scrolled down to the 'GitHub Pages' section. In this section I clicked on the 'source' button and selected 'master branch' as this is where the files I wanted to deploy have been commited to.

As this is a fairly small project with a limited amount of files and content I have only been using the master branch within the github repository. I understand that with more complex sites and data it may be prudent in the future to introduce different branches.
Therefore the deployed version of the site is identical to the files located within the repository.

To view the site offline all the files and folder structure located within the origin master branch can be downloaded and placed in a folder and viewed offline. 

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).
In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
Different values for environment variables (Heroku Config V.ars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

CREDITS

Content
The text for section Y was copied from the Wikipedia article Z



Media

As this is not a fully functioning site I just selected images that i liked from a google image search.
For a commercial site i would find images that are free to use and reference accordingly.

The photos used in this site were obtained from ...

image1
https://www.colourbox.com/image/group-of-smiling-people-working-out-with-barbells-image-8313407

image2
https://image.freepik.com/free-photo/people-working-out-at-spinning-class_13339-2540.jpg

image3
https://o2fitnessclubs.com/wp-content/uploads/2018/10/Group-Fitness-Instructor.jpg

image4
https://shawglobalnews.files.wordpress.com/2018/02/people-working-out.jpg?quality=70&strip=all&w=720&h=480&crop=1

image5
https://s3-eu-central-1.amazonaws.com/evohp/wp-content/uploads/sites/2/2017/07/13095936/EVO_July_banner_27.jpg 

image6
https://media2.s-nbcnews.com/i/newscms/2017_36/2144546/170905-working-out-group-ac-512p_2b5db137b66bedb7f1d96c24b8ca1b8a.jpg

image7
https://leaderfitness.net/wp-content/uploads/2018/02/battle-rope.jpg

image8
https://freedesignfile.com/upload/2018/03/Young-people-working-out-in-the-gym-Stock-Photo-05.jpg

image9
https://www.fitfatherproject.com/wp-content/uploads/2017/09/storyblocks-group-of-multiracial-sports-people-working-out-with-barbells-in-the-gym_rAewgChTcb-min-2400.jpg

image10
https://images.thestar.com/content/dam/thestar/news/world/2013/01/08/7_surprising_benefits_to_working_out/gymclass.jpeg 


Acknowledgements
I received inspiration for this project from:

https://davesgym.co.uk/ This is a gym that is local to me. As my imaginary gym 'the Gym' in my imagination is a small gym and not part of a franchise I want to look at 'competitor' sites for inspiration. I looked at this to see what sort of content there was. To be honest it feels a bit cluttered and old fashioned with dated fonts. I feel there is too much content and it isnt straightforward for the user. This helped me determine that I wanted a simple site with a nice font and limited colour pallet. 

https://the-works-gym.co.uk/ This is also an idependant gym that is local to me. 
I prefered the look of this site. It is more simplistic and attactive. However, i found some aspects of this site to be a bit 'clunky' or did not function correctly. And some of the text colours clashed and were difficult to read. 
I did like the 'contact' page and reused the text 'We are only a phone call away. We are a responsive company who like to deal with enquiries promptly' as i thought this was nice and conveyed what I wanted it to. 

I also looked at a lot of franchise gym sites to see what content was common and how it had been displayed and also what I liked and disliked as a user. I then refered to the breif and the UX UI training and stepped through the 5 planes to determine what I was going to produce. Also the meetings with my mentor helped to finalise the design. 




