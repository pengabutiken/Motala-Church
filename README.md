# Motala Church procject

# Pourpose and goals of Motala Church website

I want this website to serve as an helping hand to anyone interested in the church. The website can work as both as an encyclopedia for people who might be interested in the history of the church and also for tourists or other potential visitors. Motala is a small swedish town but because of the towns sceenery and it's famous beach it's popular with tourists both international and domestic. With this website I hope to highlight another tourist attraction for people that might not be aware of it when visiting. So one goal is to drive the tourists to Motala Church.

Because I want tourists to visit the location, one thing I wanted to implement was a simple UI for them to get the information they need fast. Users are impatient and if the website is unclear or hard to use they will probably just close it down. I wanted to design the homepage just with that in mind. The user is greeted with a pictue of the church and a navigation bar to take them where they want.

This website has some potential monetary benefit in the future, one future goal could be to sell ads on the website for local hotels, resturants and or other tourist attractions. If the website gets enough trafic I could potentially ask other buiessness if they want to promote their buiesness on my website. Because the tourist that visit the Motala Church website might be interested in other Motala buiesness on their visit here.


![Photo showing website on multiple devices](/assets/images/responsiveness-to-website.png)

# Sections

## Homepage
The Homepage is what the user first see. Therefore I have a picture of the church so it can serve as visual help for the user to understand what the website is about. There is also a heading in the top left corner with the name of the website so people can connect a name to the picture. The homepage also has an short description of the church to give some quick information to the user about the website. The navigation bar is also visable here so the user can click on what section they want to access fast. 

## About Section
The "About" section is where the user can learn about the church. This section has two segments, the History segment and Today segment. 

History is where you can learn about the history of the church, for example when it was built, when it was reconstructed and who was behind it. The history segment is made for anyone who might need to research the church or just is intersted in the history. 

The today segment serve a simliar purpose as the history segment. To educate the user about the church but this segment is more focused on the present day, what happends in the church nowadays, when is it popular and what you can do there.

The about section is a block of text essentially. When you have a text based section on your website I think its important for the user to be able to read the actual text.



# Features



## Existing Features

## Navigation bar
The so called navbar is there to help the user find what they want on the website. There are four multiple clickable options for the user to find what they need as quick as possible. The navbar contains the Home button by clicking the "Motala Church" button, About, Contact and Gallery. By pressing these buttons you will be sent to your desired location. The navigation bar is very important to build an accsessable UI for users.

![Photo showing navbar](/assets/images/navbar.png)

## Question section
I wanted to make sure that potential tourist that want to visit the location don't have any unanswered questios ahead of their visit. The user only has to enter their email and the question they want answered. I have used a fieldset tag to contain the form tag. Inside the form tag there is a input with the type of email and a textarea tag to insert your question. The two text inputs are required which menas that you have to fill in a email and a write something in the textarea  before clicking the submit button under.
![Photo showing question section](/assets/images/questionbar.png)
## Visit boxes
If the user wants to visit the church but don't really know how to yet, this section will try to make up your mind by giving options and explaining the options. This section will serve as a helping hand to potential visitors.
![Photo showing the visit boxes](/assets/images/visit-boxes.png)
# Features Left to Implement
- Expansion of the gallery page
- Add more boxes to the visit boxes
- Feature to sell ads on website to try to have a monetary gain for the website

# Testing 
I have sent the link of my website to two of my mates to act as "playtester" for the website and they found no bugs on the website after trying it for about 10 minutes. They tried the features and tried on various browsers and on both PC and Iphone 12. This is understandable since the website is quite basic its just HTML code with some basic CSS. I'm sure the website would be riddled with bugs if the website had more features and had more coding languages incorperated.
## Bugs

### 1. Mobile responsiveness not working/ Media Query not working properly
When trying the mobile responsiveness on the website the media query tags were forgotten by the website when trying it. Developer tools also didn't see the media query tags that I've made for that particular max-width. I, of course was very frustrated because of this since I'm not that experinced with media queries in CSS so I thought it was my fault and started researching Media Queries in CSS. I tried a lot of different max-widths and none worked for anything below 700px so I continued my reseatrch on why Media Queries dont apply to my website.
Solution:
The solution I found was on a post on stackoverflow.com where a user said that if changes in CSS don't show try to update cache.And the solution was that easy. I often update cache but this time I didn't think about it. So I tried the CTRL+SHIFT+R command and everything work as it normally should.

## Validators

- W3C Validator showed no errors : https://validator.w3.org/nu/?doc=https%3A%2F%2Fpengabutiken.github.io%2FMotala-Church%2F
- Jigsaw Validator showed no errors : http://jigsaw.w3.org/css-validator/validator?lang=sv&profile=css3svg&uri=https%3A%2F%2Fpengabutiken.github.io%2FMotala-Church%2F&usermedium=all&vextwarning=&warning=1

## Lighthouse
Lighthouse results:
![Lighthouse results](/assets/images/lighthouse1.png)


![Lighthouse results2](/assets/images/lighthouse2.png)

Where the website is lacking is the preformance aspect and as the pictures shows it's because of images. To prevent this in the future I could use a website like (https://tinypng.com/) to minimaize the size of image files. I can even use smaller images if I want to have a gallery feature on my website to not make the performance even worse.

# Deployment
I used  GitHub which is a free developer website where you can host projects to deploy my website. GitHub have a feature called GitHub Pages where you can launch your repositry to a live website. 
## How To Deploy
On your chosen repositry page to the Settings tab in the GitHub repository, then click "Pages". Choose the "main" Branch from the drop-down menu for the source section. The page will automatically update and if everything is working accordingly there will be a link to your website. This link is sharable and can be used on all devices and browsers.

## Link To My Website
https://pengabutiken.github.io/Motala-Church/



# Credits

## Content
- The information in the about section was found on the official website of the Swedish Church (https://www.svenskakyrkan.se/motala/motala-kyrka)
- Before this project I didnt know much a about the Display CSS rule but after playing this game for about 40 minutes I really learned how to position diffrent things properly. The game is called Flexbox Froggy. (https://flexboxfroggy.com/)
- I used icons in the navigation bar and footer  taken from Font Awesome. (https://fontawesome.com/)
- I needed inspiration for my navigation bar so I watched one video about navbars and used some of his tips and tricks. The Youtube user is called "Web Master". (https://www.youtube.com/watch?v=ZotQNKyvZsw&ab_channel=WebMaster)
- I wanted to make my code look as professional as possible so I tried following some code etiquette taken from this website. (https://learn.shayhowe.com/html-css/writing-your-best-code/)
- To format my HTML and CSS I used free to use websites where you can paste your code and get your code back but constructed in a more professional way. The websites are called freeformatter.com (https://www.freeformatter.com/html-formatter.html#before-output) (For HTML) cleancss.com (https://www.cleancss.com/css-beautify/) (For CSS)

## Media
- Pictures in the Gallery and the image on the home page are pictures taken from the Swedish church, Motala Church's wikipedia page and the local newspaper called Motala Vadstena Tidning. (https://www.svenskakyrkan.se/motala/motala-kyrka     https://sv.wikipedia.org/wiki/Motala_kyrka      https://mvt.se/bli-prenumerant/artikel/r2p7413j/mvt-bf_3m3kr_e)


