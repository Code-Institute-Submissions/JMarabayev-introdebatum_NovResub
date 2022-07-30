# Introdebatum!

Introdebatum is an online static platform for social gatherings and indiciduals wishing to challenge themselves to explore different concepts and debate topics based on their interests. The reason why I chose to go down this path is due to the fact that I am an introverted individual and usually find it difficult to initiate deep conversations with my peers, as most gatherings ususally result in series of small talks, but when I do succeed to interest someone in a deep conversation and a debate about the stars, technology the future and anything else that tantilises the mind, I end up having an amazing evening and walk away happy that I managed to engage in an interaction that meant something to me and broadened my understanding of the world around me.

Introdebatum aims to help people engage in these conversations by giving them a slight push through providing some relevant material and asking follow up questions to which there could be a series of answers. It is an ongoing project where fellow people would be able to add the topics they found to be interesting to discuss to systemically grow the platform, which is the step I hope to achieve in the future. Through collaboration and common effort Introdebatum can become a Wikipedia for debates which can be used by both the social and the education sectors. 

![Responsice Mockup](https://github.com/lucyrush/readme-template/blob/master/media/love_running_mockup.png)

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - Featured on all four pages, the navigation bar makes it easy to jump from section to section. On the home page the navigation bar can take you to the "About" section with brief instructions and introduction to the page; the "topics section which has a selection of topics to explore for your debates; the "contact" section where anyone can fill out a form to further improve the website or to contact the developer (me). Each of the child pages (Topics) has a "Home" button on top left to take the user back to the home page. Each child page also has a "Back to Top" button to help them navigate back to the top where they can go down the list of topics once again or opt to go back to homepage using the nav bar at the top.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](/workspace/introdebatum/assets/images/navbar.png)
![Back to Top](/workspace/introdebatum/assets/images/navbar.png)

- __The landing page__

  - The lander arrives at a textured background displaying the name of the website and its slogan. 
  - This section introduces the user to Introdebatum with a minimalistic greeting.

![Landing Page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_landing.png)

- __About Section__

  - The about section gives the user a bit more information on how to use the platform and aims to inspire them to explore. 
  - This user would get accustomed to the format and layout of the website and navigate to where they see fit in order to achieve their desired goal. 

![Club Ethos](https://github.com/lucyrush/readme-template/blob/master/media/love_running_ethos.png)

- __Contact Section__

  - This section would allow users to write a custom message and leave their contact information in order to give feedback to the developer. 
  - The responses from this section would be monitored and reviewed and best suggestions would be implemented into the website to allow the user to interact with the platform better. 

![Meetup Times](https://github.com/lucyrush/readme-template/blob/master/media/love_running_times.png)

- __The Footer__ 

  - The footer contains information saying that Introdebatum does not own any of the information provided and the rights to the information are reserved with their original author. 
  - The footer also gives the developer's initials for future recognition.

![Footer](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- __Topic Sections__

  - Each topic has several subtopics which are accompanied by fullscreen YouTube videos embedded into the page. 
  - Below each video there is some written supporting information which summarises the topic in a paragraph and provides a hyperlink that opens a new tab with the original article in case the user wants more information on the topic.
  - Below each paragraph there is a series of three questions that aim to spark a debate about a given topic, wether to use these questions or to resort to their own is at the discretion of the user. 

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

### Features Left to Implement

- Interactive design with animations.
- Allow for user interaction through adding their own topics and questions (Similar to Wikipedia).
- Random Topic selector similar to Google.com "I'm feeling Lucky" in which the user presses the button and a random topic and subtopic are displayed.
- Live chatrooms with people discussing a topic of their choice.

## Testing 

Through the completion of the project all features were tested using the temporary server upload with the command (python3 -m http.server). All hyperlinks work as intended and take the user to the correct section. Back to top button works, the user however may choose to scoll a little but up in order to reveal the nav bar for the respective page. All images are of the apropriate size for their intended purpose.
Upon resizing the browser window the text shifts to fit the width of the scren and side scrolling is not necessary. The topics are done as inline-block and thus shift from horizontal to a vertical alignment which facilitates easy scrolling. As mentioned in the unfixed bugs section the home page has some dead space and an option to scroll sideways, I was unable to reduce the width of the page to fix this. All Youtube embedded videos work as intended and are responsive to screen size. Since it is an embedded Youtube video, the controls are inherit. Autoplay is disabled for user experience.
The contact form is also correct in a sense that it allows for input. Given that I do not yet have a data dump to post the responses into I have used the one from the Coders Coffeehouse project from Code Institute HTML and CSS Essentials Curriculum.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjmarabayev.github.io%2Fintrodebatum%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator] (https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjmarabayev.github.io%2Fintrodebatum%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

One feature that I was unable to fix was the scale of the webpage in which there is some dead space to the right of the home page, as well as the homepage being a little askew on some mobile devices (iphone 7, samsung galaxy s21). I tried many approaches such as encasing the whole page in a div, or playing with width and media settings, but none yielded effective results. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://jmarabayev.github.io/introdebatum/ 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the subtopic was taken from external sources which are hyperlinked under each paragraph.
- Instructions on how to implement a responsive iframe were taken from https://www.w3schools.com/howto/howto_css_responsive_iframes.asp*/

### Media

- The photos used on the home and sign up page are from This Open Source site unsplash.com
- The images used for the gallery page were taken from this other open source site unsplash.com
