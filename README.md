# Canine Coffee House - Milestone Project One

This project was complete as part of Code Institute's level 5 web application course. It is a a static front-end project focusing on HTML and CSS technology's and was written by Lyle Kilbey.   

## Overview

This is a web application for coffee shop and restaurant "Canine Coffee". Calling one of brighton's prime dog walking areas, Preston Park, home Canine Coffee aims themselves towards local customers and their furry friends. Offering locally sourced food,  a bespoke doggy menu and a range of coffee and teas Canine Coffee would like build upon their home away from home branding. The overall purpose of this site is to attract new customers, while also giving existing customers a place to get in contact and stay updated. 

## Design

The design of the site should mimic the soft, homely feel of the Canine Coffee brand. Using Neutral colours and simplistic design to allow users the space to perceive their own feelings home will create unity between experiences online and in-store. 

### User Stories

As Canine Coffee business owner, I want:
- a soft neutral design, to reflect the in-store experience.
- to receive any message from user to my company email, so I do not have to mange an additional inbox.
- the users to know our core values, to reinforce the brand of my business.

As a user, I want: 
- to easily know how to navigate around the website, so I can find the information I am looking for.
- to be able to contact coffee canine, so I can ask questions I need answers to.
- to be able to view the site form any device, so I can use my mobile, tablet or desktop to comfortably view the website.
- to know the what is available to purchase, so I can make an informed decision on if this business is for me.
- to know when the business is open, so I can plan my visit.
- to be able to access the site from any internet connection, so I can look at the website on the go.
- to enjoy the imagery and design of the site, so I feel positive when using the site.

### Wireframes

The above user stories have been used to create initial wireframes. To aid in assessment of this project, the wireframes have been included within the assets folder. 

####  [Wireframe-v1](/assets/wireframe/wireframe-v1.pdf): 
This is the initial design which was reworked as not all user stories were met.

#### [Wireframe-v2](/assets/wireframe/wireframe-v2.pdf):
##### Added:
- 'contact us' renamed to 'Stay in Touch' to better reflect contents of page. 
- Image to replace buttons on dog menu.
- additional form for newsletter sign-up
- Accordion style structure added to mobile and tablet design to accommodate additional form and add consistency with menu page.
- submit button for forms. 

##### Removed:
- Buttons from dog menu as they subtracted from simplicity of page.

#### [Wireframe-v3](/assets/wireframe/wireframe-v3.pdf):
##### Added:
- About section on Stay in touch page, including address, email, telephone and map. 
- Additional accordion section to accommodate about section. 

##### Removed:
- N/A

### Structure 

This section will outline the plan for using bootstrap to organise content and make the UI responsive to device screen size. 

3 of Bootstrap's breakpoints will be used to:
- Small, minium width: 576px, mobiles.
- Medium, minium width: 768px, tablets.
- Large, minimum width: 992px, desktops.

This section will break down each container to show how the intended grid implementation will be configured. 

#### Header:

The header will be contained within one row.
##### Small:
![image](/assets/wireframes/wireframe-header-small.png)
'Canine Coffee' = 8 columns
Burger menu = 4 columns

##### Medium:
![image](/assets/wireframes/wireframe-header-mid.png)

'Canine Coffee' = 4 columns offset 4
Burger menu = 4 columns

##### Large:
![image](/assets/wireframes/wireframe-header-lg.png)

'Canine Coffee' = 4 columns.
Burger menu = 4 columns offset 4.

#### Footer:

The footer will be contained within two rows.
**Row 1:** Facebook, Instagram, Twitter.
**Row 2:** Email, Telephone.

##### Small:
![image](/assets/wireframes/wireframe-footer-sm.png)
**Row 1:** 
- Facebook = 4 columns.
- Instagram = 4 columns.
- Twitter = 4 columns.

**Row 2** = display None.

##### Medium:
![image](/assets/wireframes/wireframe-footer-mid.png)
**Row 1:** 
- Facebook = 4 columns.
- Instagram = 4 columns.
- Twitter = 4 columns.

**Row 2:**
- Email = 4 columns.
- Telephone = 4 columns.

##### Large:
![image](/assets/wireframes/wireframe-footer-lg.png)
**Row 1:** 
- Facebook = 4 columns.
- Instagram = 4 columns.
- Twitter = 4 columns.

**Row 2:**
- Email = 4 columns offset 2 columns.
- Telephone = 4 columns.

#### Home Main Content

The main content for the home screen will be placed into its own container and will be spread across 5 rows.
**Row 1:** Hero Image
**Row 2:** Why Canine Coffee? title
**Row 3:** Why 1, Why 2, Why 3 titles and contents
**Row 4:** Meet the Team titles 
**Row 5:** Meet the team content

##### Small:
**Row 1:** 
- Hero Image = 12 columns.

**Row 2:**
- Why Canine Coffee? title = 12 columns.

**Row 3:** 
- Why 1 title and content = 12 columns.
- Why 2 title and content = 12 columns.
- Why 3 title and content = 12 columns.

**Row 4:** 
- Meet the Team titles = 12 columns.

**Row 5:** 
- Meet the team 1 = 12 columns.
- Meet the team 2 = 12 columns.
- Meet the team 3 = 12 columns.
- Meet the team 4 = 12 columns.

#### Menu Main Content

the menu main content container will be spread across 2 rows. 
**Row 1:** Human Menu container, drinks Menu container.
**Row 2:** Dog Menu container, Image, 

##### Large:

**Row 1:**
- Human Menu container = 8 columns
- Drinks Menu container = 4 columns.

**Row 2:**
- Dog Menu container = 8 columns.
- image = 4 columns.

#### Human menu container

The human menu container is broken up into seven rows
**Row 1:** Menu title.
**Row 2:** Item title, item description.
**Row 3:** Item title, item description.
**Row 4:** Item title, item description.
**Row 5:** Item title, item description.
**Row 6:** Item title, item description.
**Row 7:** Item title, item description.

All items above will be set to 12 columns as all should exist on their own line. This could be achieved using the display property in css without using bootstrap. However, Bootstrap will be implemented to ease future development and remain consistent with rest of the programming done for this project.

#### Drinks menu container

The human menu container is broken up into seven rows
**Row 1:** Menu title.
**Row 2:** Item title, item description.
**Row 3:** Item title, item description.
**Row 4:** Item title, item description.
**Row 5:** Item title, item description.
**Row 6:** Item title, item description.
**Row 7:** Item title, item description.

All items above will be set to 12 columns as all should exist on their own line. This could be achieved using the display property in css without using bootstrap. However, Bootstrap will be implemented to ease future development and remain consistent with rest of the programming done for this project. 

#### Dog menu container

The human menu container is broken up into seven rows
**Row 1:** Menu title.
**Row 2:** Item title, item description.
**Row 3:** Item title, item description.
**Row 4:** Item title, item description.
**Row 5:** Item title, item description.
**Row 6:** Item title, item description.
**Row 7:** Item title, item description.

All items above will be set to 12 columns as all should exist on their own line. This could be achieved using the display property in css without using bootstrap. However, Bootstrap will be implemented to ease future development and remain consistent with rest of the programming done for this project. 

#### Stay in touch main content

The stay in touch main content will be spread across 2 rows. 
**Row 1:** Send a Message form, Newsletter sign-up form. 
**Row 2:** About Section

##### Small:
**Row 1:**
- Send a Message form = 12 columns.
- Newsletter sign-up form = 12 columns. 

**Row 2:** 
- About Section = 12 columns.

##### Medium:
**Row 1:**
- Send a Message form = 12 columns.
- Newsletter sign-up form = 12 columns.

**Row 2:** 
- About Section = 12 columns.

##### Large:
**Row 1:**
- Send a Message form = 6 columns.
- Newsletter sign-up form = 6 columns.

**Row 2:** 
- About Section = 12 columns.

## Decision log

| Decision | comment                               | Change required?| 
| -------- | ------------------------------------- | ----------- |
| Example  | This an example comment |      **NO**       |
| Example  | This an example comment |      **YES**       |

## Deployment

## Credits



## Testing
### Bugs
### Smoke Testing 
### HTML Validator Testing
### CSS Validator Testing
### Lighthouse Validator Testing
### Functional Testing



