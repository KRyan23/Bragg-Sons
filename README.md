
#Bragg&sons
***
##Ux

###Project Goals

* The primary goal of the project is to provide an easy to use central point of contact for new and existing customers.



###Business Goals
* The main purpose of the project is to give the Bragg&Sons business a central  area where they can direct new and existing customers to.
* With the company expanding it aims to modernise its information gathering and use the website to later on build a digital database of it customers.
* To clearly display its services and showcase the result of its efforts in a gallery.






####User Stories

As a member of the Business.

* To be able to get a clearer picture ahead of time as to what staff are needed for the ammount of work booked in for the comming weeks/month.
* The idea of the website is an exploratory one for the business, we want to start with something relativlty basic that meets our current needs and in the future if it works for us we would like to build on it to take payments from customers.
* We know the staff pride themselves in the work they do, but we would like to show some of that off to the greater public.
* Theres rarely a bad word to be said about the service we provide and again we would like to get that message out there.
* Social Media is a great communicator but the various pages we have on facebook,twitter and instagram just feel too fragmented we need a website to tie them together.

As a new or existing customer.

  * Bragg and Sons are great I've been using them for years but you never really know which family member to contact about getting the place painted, it would be better there was one number to ring instead of a mobile.
  * Ive heard good stories about them but I wouldnt mind seeing some examples of their work before I ring them.
  * We used to live in a flat that I got Bragg&Sons to paint a few years ago, but since then we moved to a much larger place. With the new baby we are not sure we could afford their service, it would be nice if there was an easy way to get a fast quote.
  * I have a mobile phone number for Bragg&Sons that someone gave to me, the last time I rang it it went straight to voicemail, do they have an office I can just ring.
  * I have an apartment as well as a family home in the city, I would like to know the  cost to paint both.
  * As a new customer Ive rang a few times and they allways seem nearly too busy to talk, id like to just be able to book a painter in on a specific date.





Please find the 5 strategy planes discussing the scope and needs of the project.


### Strategy
#### Focus
- They want more of an online presence
- They would like to sell more services
- Automate certain tasks
- Get a clearer indication of the work needed
#### What are we creating
- We are creating a custom site rather than relying on facebook
#### Is it Valuable
- Make it easier to sell more of what we do
- Make giving esitamates easier on both business and the end user
- Give the user an easier oportunity to purchase a services
- Showcase some of our work in a gallery page.
<br><br><hr>
### Scope
#### Features
- Provide a quick online quote
- To sumbit a form outlining work required
#### Content
- Provide business details, phone number, address, email.
- Photos of completed work and projects
- User testimonials
<br><br><hr>
### Structure
#### Information architecture
- Were choosing the tree Structure, not the best for mobile but its a small site
- Group content for our sites audience
- Create the correct structure for our objectives and user needs
- Prioritse the upfront information
---

### Skeleton

* Create Wireframes for

* Mobile
* Tablet
* Desktop



###Surface

- Decide on the colour scheme
- Decide on the Topography
- Add any effects at this stage
- Put in the imagery for the site
- Reinforces the meaning of the content
- Guides the user throught the content in an intuitive way
- Minimise cognitive overload while maximising intuitive learning
- Concerned with appropriate content at all times

---
### Wireframes
Please find links to the wireframes below, all were created using Balsamic 4.2.1 on Windows.


* [Desktop - Tablet -Mobile]("C:\Users\User\Desktop\CodeInst\MileStoneProject1\MileStone For real project\Bragg & Sons Idea\Wireframe Pdfs\Phone Wireframes\MobilePhonePages.pdf")

---


##Features

###Existing Features

* The company wanted an easy central way to allow people to get in touch, this is atchieved using the contact form.
* Bragg&Sons wanted to showcase some their work, this is implemented in the gallery section.
* One of the main asks was to provide customers with the abilty to get a quick and accurate quote online by filling out a form.


###Features Left to Implement

If the Bragg&Sons website proves valuable for the business they would like to add an ecommerce module so they can take payments online.

They would also be interested in implementing building up a database on new and existing customers and not to so heavily rely on email and paper based records.

---
##Technologies Used

* Atom - As the main editor, mainly because it is confgurable to what you need, its fast and works seamlessly with GitHub integration.
* GitHub was used for change control and as a requirement of the course.
* I also used, Onedrive and Dropbox to backup the project local data twice daily.



Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.


For the html5 code I used https://validator.w3.org/ and used the direct input method, scanning the errors and trying to understand how the flow of the page was interrupted by usually a stray or missing closing tag.
Ususally correcting one of these fixed more than 1 error found by the validator, I then updated my project with each fix found.

For the CSS3 code I used https://jigsaw.w3.org/css-validator/ and again used the direct input method rather than uploading the file. Here I found some parse errors from not giving the parameters a value under 2 of the media queries.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

##Testing Section:

####The Contact Page:

The form was tested many times in the different browsers and I used the formdump from codeinstitute to validate that the from was sent / recieved.
Along with this the necessary "required" fields prevented users submitting a half filled form.
The reset button on the form was also tested and did indeed clear the form so the user could re-enter their details.

####The Quote Page:

For checking the Html5 code on the page we used: https://validator.w3.org/#validate_by_uri
For checking the acessibility colour on the page we used: https://color.a11y.com/?wc3
For checking the CSS3 code on the page we used: https://jigsaw.w3.org/css-validator/
For checking the acessibility n the page we used: https://www.aditus.io/aria/aria-label/
The quote form was also tested many times in the different browsers and again I used the formdump from codeinstitute to validate that the from was sent / recieved.
Along with this I set the necessary radio groups buttons to "required" to prevent a half filled form being submitted.
The "Colour Palette Link" on the quote from page was tested with various browsers to make it opened up a as intended.

###Cross Browser Testing:


I mainly used Chrome and its dev tools from the entireity of the project since it was just faster to use the responsive method to check aligment on differnt viewports configurations.

Since I used Atom for all the development (beacuse of the 50hr monthly limit in Gitpod) I was able to run a local webserver which was great for checking compatibility in other browsers.

These included:

* Chrome
* Opera
* Firefox
* Edge
* IE11



One of the initial challenges which im sure is quiet normal when writing code was the accidental deletion or addition of a parenthesis,
when editing code. The knockon effect being the whole layout of the site suddenly not looking right.
Intially I tried to find these manually until the Css file grew quite large and it took longer and longer to find the issue.
I realised that I could just use the online css/html code validators and use the direct input method to quickly scan the code which saved a lot of time, the "Parse Error" output would then help you zone in on the issue.

<li>Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Code was run locally using Atom-Live-Server from Atom itself.
<hr>
##Credits
###Content
The text for all sections was created by myself derived from a conversation with a local painter.
###Media

The braggandsons logo was borrowed from, I addded the text and style.
[BrandCrowd](https://www.brandcrowd.com)

The pictures on the home page

1.The testimonails and gallery pages images, screenshot were taken of the finshed pages, edited and made new images from.
[2. Main Picture - IsStockPhotos](https://www.istockphoto.com/)

The pictures on the testimonails page were borrowed from the following sources
[1. - DreamsTime](https://www.dreamstime.com/)
[2. - Hackesack Meridian Health](https://www.hackensackmeridianhealth.org/)
[3. - HomeCareAssistanceRoseville](https://www.homecareassistanceroseville.com/)
[4. - TropicalSky](https://www.tropicalsky.i)
[5. - SportsKeyDevelopment](ttps://1220hslgc6sportkeydevelopment.wordpress.com/staff/)
[6. - I DentistClinicBar](https://www.facebook.com/identistclinicbarlad/)
[7. - Shutterstock](https://www.shutterstock.com/)
[8. - 123rf](https://www.123rf.com/)

 testimonails on the about page were created by myself just the images we borrowed by doing a google search of "picture of a happy person", "picture of a smiling person", picture of a smiling older person, "picture of a smiling couple in new house", "picture of a smiling older couple"

The colour palette to create the colour-scheme.pdf was borrowed from here
[Lakelandfurniture](https://www.Lakelandfurniture.co.uk)

The pictures on the services page were borrowed from the following sources
[1 - istockphoto](https://istockphoto.com)
[2 - indiamart](https://www.indiamart.com/)

The pictures on the gallery page were from the following sources
[1 - Perfecthome](https:www.perfecthome.ie)
[2 - PowellPaintingAndHomeServices](https://powellpaintingandhomeservices.com/)
[3 - YainnovationPainting](https://www.yainnovationpainting.com/)
[4 - TheGasCompany](https://www.thegascompany.ie)
[5 - Pinterest](https://www.pinterest.ie/)
[6 - HighHeelsToHotWheels](http://highheelstohotwheels.com/)
[7 - HelixPainting](https://helixpainting.com)

###Code

[A Code snippit for the shrink effect on the links was modified and used from here](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/)

###Acknowledgements
I received inspiration for this project from a conversation with a local painter and from my own experiences with painting my house over the years.

Fenton - A blog post in stack overflow for the soloution on how to wrap the button in a form so it conforms to html standards.

The name Bragg&Sons and any contact information does not represent the actual painters details and no he doesnt have a website at present!

This readme.md was written using Atoms Markdown Preview Enhanced package.
