## Testing
This document will capture and record the testing complete to ensure functionality of the Canine Coffee website.  A combination of validation testing, using online validator tools, and functional testing will be used.
### Bugs
- Included more imagery to make the site more engaging

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



#### Unresolved bugs


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
    - **TEST FAILED**
        - As a user I would like more imagery as only a few images have been included. 

### HTML Validator Testing

### CSS Validator Testing

### Lighthouse Validator Testing
