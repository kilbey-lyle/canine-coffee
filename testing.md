## Testing
This document will capture and record the testing complete to ensure functionality of the Canine Coffee website.  A combination of validation testing, using online validator tools, and functional testing will be used.
### Bugs

#### Solved bugs
- The main logo does not do anything when clicked. It should take you to the home page.
    - href for anchor element contain logo update to 'index.html'
- When on reduced screen sizes lines appear in between sections of the footer.
    - Bug **not reproducible**, error found in testing with chrome developer tools. Footer responsively tested on real mobile devices, no lines appear when UI scale down.
- Default favicon should be replaced with styled favicon.
    - favicon.png file added to root dir. 
- Incorrect grammar in the why-3, we're barking mad, section of the home page.
    - 'Our' text removed from why-3 paragraph element.
- Fix menu introduction paragraph for grammar and spelling mistakes.
    - Paragraph rewritten and updated
- No action from form when clicking submit button. There should be feedback to user that this has successfully happened.
    - Action and method Attribute added to all forms. Code institutes form dump url used for this. 
- Links on navigation bar moving when being hover over. The links should only have a border added.
    - Reduced padding and margins when .navlink is in hover state. this account for the extra width of adding border. 


### Functional Testing

Function testing will be completed against the user stories defined in the README.md. This is to ensure the all desired functionality has been implemented in the final design and code base. If a test fails, it will be recorded as a bug within the bug section of this document. Once fixed that user story will be retested and documented below. 

Testing will be completed the different browsers of Chrome, Microsoft Edge and FireFox
#### Chrome
##### Initial Test Run

As Canine Coffee business owner, I want:
- a soft neutral design, to reflect the in-store experience.
    - **TEST PASSED**
- to receive any message from user to my company email, so I do not have to mange an additional inbox.
    - **Removed as requirement - not tested**
- the users to know our core values, to reinforce the brand of my business.
    - **TEST PASSED**

As a user, I want: 
- to easily know how to navigate around the website, so I can find the information I am looking for.
    - **TEST PASSED**
- to be able to contact coffee canine, so I can ask questions I need answers to.
    - **TEST PASSED**
- to be able to view the site form any device, so I can use my mobile, tablet or desktop to comfortably view the website.
    - **TEST PASSED**
- to know the what is available to purchase, so I can make an informed decision on if this business is for me.
    - **TEST PASSED**
- to know when the business is open, so I can plan my visit.
    - **TEST PASSED**
- to be able to access the site from any internet connection, so I can look at the website on the go.
    - Private Wifi: **TEST PASSED**
    - Public Network: **TEST PASSED**
    - 4G: **TEST PASSED**
- to enjoy the imagery and design of the site, so I feel positive when using the site.
    - **TEST PASSED**

#### Edge
##### Initial Test Run

As Canine Coffee business owner, I want:
- a soft neutral design, to reflect the in-store experience.
    - **TEST PASSED**
- to receive any message from user to my company email, so I do not have to mange an additional inbox.
    - **Removed as requirement - not tested**
- the users to know our core values, to reinforce the brand of my business.
    - **TEST PASSED**

As a user, I want: 
- to easily know how to navigate around the website, so I can find the information I am looking for.
    - **TEST PASSED**
- to be able to contact coffee canine, so I can ask questions I need answers to.
    - **TEST PASSED**
- to be able to view the site form any device, so I can use my mobile, tablet or desktop to comfortably view the website.
    - **TEST PASSED**
- to know the what is available to purchase, so I can make an informed decision on if this business is for me.
    - **TEST PASSED**
- to know when the business is open, so I can plan my visit.
    - **TEST PASSED**
- to be able to access the site from any internet connection, so I can look at the website on the go.
    - Private Wifi: **TEST PASSED**
    - Public Network: **TEST PASSED**
    - 4G: **TEST PASSED**
- to enjoy the imagery and design of the site, so I feel positive when using the site.
    - **TEST PASSED** 
#### Firefox
##### Initial Test Run

As Canine Coffee business owner, I want:
- a soft neutral design, to reflect the in-store experience.
    - **TEST PASSED**
- to receive any message from user to my company email, so I do not have to mange an additional inbox.
    - **Removed as requirement - not tested**
- the users to know our core values, to reinforce the brand of my business.
    - **TEST PASSED**

As a user, I want: 
- to easily know how to navigate around the website, so I can find the information I am looking for.
    - **TEST PASSED**
- to be able to contact coffee canine, so I can ask questions I need answers to.
    - **TEST PASSED**
- to be able to view the site form any device, so I can use my mobile, tablet or desktop to comfortably view the website.
    - **TEST PASSED**
- to know the what is available to purchase, so I can make an informed decision on if this business is for me.
    - **TEST PASSED**
- to know when the business is open, so I can plan my visit.
    - **TEST PASSED**
- to be able to access the site from any internet connection, so I can look at the website on the go.
    - Private Wifi: **TEST PASSED**
    - Public Network: **TEST PASSED**
    - 4G: **TEST PASSED**
- to enjoy the imagery and design of the site, so I feel positive when using the site.
    - **TEST PASSED** 

### HTML Validator Testing

Test complete on [W3C Markup Validation Service](https://validator.w3.org/) - **TEST PASSED**

### CSS Validator Testing

Test completed on [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) - **TEST PASSED**

### Lighthouse Validator Testing

Lighthouse is an in-built dev tool provided by Chrome. It will be used to valid accessibly and loading times of the web page. Anything marked red in lighthouse's traffic light system will be considered. 

##### INDEX Page

![Lighthouse results Index test 1](./assets/readme-imgs/lighthouse-test1.png)
###### Will Do
- Reduce image size of hero image.
    - Images processed by tiny png
- Reduce image size of profile images.
    - Images processed by tiny png
- Server image in next gen formats.
    - Images updated to webp format.
- Higher Contrast text color
    - 'why-content' css color attribute removed so Paragraphs contained in 'Why Canine coffee house' now inherits it's color from container which is set to the darker green color.

###### Won't Do
- Eliminate render-blocking resources.
    - unable to resolve, bootstrap resource required. Mitigation achieved by using CDN. Can be improved in future by only requesting required components.
- Preconnect to required origins (font awesome)
    - Can be implemented in future.
- Reduce unused CSS (font awesome).
    - can be done in future. Mitigation achieved by using CDN.
- Reduce unused Javascript.
    - Caused due to chrome extension, retest required in incognito window.

Results after Changes:

![Lighthouse results Index test 2](assets\testing-imgs\Lighthouse-index-test2.png)

##### Menu Page

![Lighthouse results Menu test 1](assets\testing-imgs\Lighthouse-menu-test1.png)

- No changes needed

##### Contact Page

![Lighthouse results Contact test 1](assets\testing-imgs\Lighthouse-contact-test1.png)

Areas of improvement:

![Lighthouse results Contact test 1](assets\testing-imgs\Lighthouse-contact-results.png)

Testing has confirmed these are due to the embedded map. No improvements possible at this stage. 




### Requirement Evidence

This section will provided screenshot evidence, where possible, that all user stories have been implemented. 

#### As Canine Coffee business owner, I want:

| Story | Evidence                               | 
| -------- | ------------------------------------- | 
| a soft neutral design, to reflect the in-store experience. | ![image](assets\testing-imgs\soft-design.png)  |
|to receive any message from user to my company email, so I do not have to mange an additional inbox.| Not in scope of this project.|
|the users to know our core values, to reinforce the brand of my business.| Image 1: ![image](assets\testing-imgs\values-1.png) Image 2: ![image](assets\testing-imgs\values-2.png)|

#### As a user, I want: 
 Story | Evidence                               | 
| -------- | ------------------------------------- | 
| to easily know how to navigate around the website, so I can find the information I am looking for.| ![image](assets\testing-imgs\nav-bar.png) Navigation bar used which follow the user as they scroll down the page.|
| to be able to contact coffee canine, so I can ask questions I need answers to.| ![image](assets\testing-imgs\Send-a-message.png) |
| to be able to view the site form any device, so I can use my mobile, tablet or desktop to comfortably view the website.| Mobile: ![image](assets\testing-imgs\responsive-design-1.png) Tablet: ![image](assets\testing-imgs\responsive-design-2.png) |
|to know the what is available to purchase, so I can make an informed decision on if this business is for me. | ![image](assets\testing-imgs\menu-page.png) |
| to know when the business is open, so I can plan my visit. | ![image](assets\testing-imgs\about-page.png) |
| to be able to access the site from any internet connection, so I can look at the website on the go.| Tested to be working against: Home Broadband, a ISO27100 certified Work Network, 5G ,4G, 3G. |
|to enjoy the imagery and design of the site, so I feel positive when using the site. | ![image](assets\testing-imgs\soft-design.png) |



