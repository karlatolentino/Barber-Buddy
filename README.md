##### By Karla Tolentino
# T2A2 - "Barber Buddy" Marketplace Project

## Table of Contents
- [App Deployment](#app-deployment)
- [GitHub Repository](#github-repository)
- [Purpose and Target Audience](#purpose-and-target-audience)
- [Functionality and Features](#functionality-and-features)
- [Sitemap](#sitemap)
- [Screenshots](#screenshots)
- [Target Audience](#target-audience)
- [Tech Stack](#tech-stack)
- [User Stories](#user-stories)
- [Wireframes](#wireframes)
- [ERD](#erd)
- [Abstractions](#abstractions)
- [Third Party Services](#third-party-services)
- [Active Record Associations](#active-record-associations)
- [Database Relations](#database-relations)
- [Database Schema Design](#database-schema-design)
- [Project Management](#project-management)

## App Deployment
https://barber-buddy.herokuapp.com/

## GitHub Repository
https://github.com/karlatolentino/Barber-Buddy

## Purpose and Target Audience
As barbering is a highly transportable skill, many Barbers tend to not stay in the same place for a long time. This can prove to be quite frustrating for clients who have finally found the right barber.

*Barber Buddy* is a networking marketplace application created for Barbers and Barber clients to find each other. to  As the creator of this application is a barber by trade, this concept was curated with the barber and client's direction in mind.

The *purpose* of this app is to help both the Barber and their Buddy establish a mutual connection with each other before they even enter the shop and sit in the chair for their haircut appointment. A common *problem* within the hairdressing industry is the amount of trial and error required for a client to find a hairdresser or barber that not only understands their needs, but also enjoy their conversations.  Having the right vibe and conversations between the Barber and Buddy can make or break a client's experience within the barbershop, and affect clientele retention and relationships for the Barber. If a client or Buddy is satisfied with the quality of the cut, their experience may be dampened with conflicting interests with the Barber that is often discovered during their banter. As barbering is a highly transportable skill, many Barbers tend to not stay in the same place for a long time. This can prove to be quite frustrating for clients who have finally found the right barber and must restart the process of searching for a new barber who can fill their criteria needs.

*Barber Buddy* aims to showcase the needs of both Barber and Buddy/clients in an informal manner. This networking application enables both parties to seek out relationships that are genuine by matching each other by their similar needs and interests. For example, if a Barber is looking to experiment with unconventional hairstyles, they may include that information on their profile when seeking for a Buddy. If a Buddy is looking for a Barber with a specific skill or specialisation, they may also include that information on their profile. A Barber or Buddy may even just describe their topic interests if all they require for a great haircut experience is great banter. Once both parties have created their profile on *Barber Buddy*, they can then begin the search for the perfect connection.

The *target audience* for this application is directed towards users who are either Barbers or clients who seek out each other for a haircut. The majority of clients who visit barbershops usually rely on external resources to find the right barber.  Often times, clients switch between different hairdressers or barbers and can have different expectations of what the client's needs are. By creating this app, bridging the communication gap between barber and client can increase client satisfaction and boost the overall experience at the shop. *Barber Buddy* offers a safe networking space Barbers and Buddies to create positive relationships by addressing their criteria needs for the perfect haircut experience.

## Functionality and Features
* **1. Landing Page**

Upon launching the app, the user will be taken to the *Barber Buddy* landing home page. From there, they are able to access and view the About page to discover the purpose of the app and what they are able to offer to users. In order to view *Barber Buddy* profiles, they must log in or be a registered user.

* **2. User Registration**

If a user accesses the Register page from the navigation bar, or any other page apart from the About page, they are taken to the user registration page. From here, they must input an email address, username, password and password confirmation and specifiy whether they are a Barber or a Buddy. Upon completion of the registration form, they are taken back to the home page where they can have full access to Barber Buddy profiles and create their own.

* **3. User Log in**

If prompted to log in, a user is directed to input their email address and password. Upon successful log in, they will be taken to the *Barber Buddy* home page. If they have forgotten their password, there is an action button below the log in form that enables the user to send a password reset form to their chosen email address. If the user is not registered, there is a sign up action button that will redirect them to the user registration page.

* **4. User Account**

Once a user has registered and logged in, they are able to access the Account page. From there, they are allowed to change their user password and/or delete their account. Once their account is deleted, they must register again for full access of the app.

* **5. Create a Profile**

Once a user has registered an account on *Barber Buddy*, they are able to create their own Barber or Buddy profile on either the Profile page or Barber and Buddies page. From here, they must fill out a form that takes in the users details:
- First Name
- Last Name
- Pronouns
- Location: specified by suburb and state
- About Me: a section for the user to describe their personality and interests. They may also outline their specialisations and desires, if any.
- Services offered/desired: user can check off any services provided by *Barber Buddy* that are relevant to the user
- Profile Picture upload: user is able to upload one image as their profile picture

* **6. Edit/Update Profile**

Once a user is registered, they are able to edit their profile via the Profile or Barbers and Buddies page. The same form from the Create a Profle page is rendered for the user.

* **7. Profile Index and Views / Barbers and Buddies**

Once a user is registered, they are able to access the Barbers and Buddies page where a list of user profiles are shown. From there, they are able to view the selected profiles to display that users profile information. If the profile selected is, it will display  that user's profile image, name, pronouns, location and show whether they are either a Barber or a Buddy. Below their About Me section, it will list the services that are desired/offered by that user. The registered user will only be allowed to edit and delete their profile on either the Barber and Buddies page or their Profile page. If the user finds the perfect profile match, they are able to contact that match via a contact button that opens up their mail app and inputs the chosen user profile's email address and establish a conversation.

* **7. Search Filter**

On the Barbers and Buddies index page, users are able to search for text that matches a user profile's description via a search form. For example, if a user types in 'music' in the search bar and hits th search button, it will list the profiles that match the query in their About Me desription. This will enable Barbers and Buddies to identify specific profiles of their liking.


## Sitemap
<img src="docs/barber-buddy-sitemap.png">

## Screenshots
<img src="docs/screenshots/Screen Shot 2021-08-19 at 11.09.14 am.png">
<img src="docs/screenshots/Screen Shot 2021-08-19 at 11.08.49 am.png">
<img src="docs/screenshots/Screen Shot 2021-08-19 at 11.09.07 am.png">
<img src="docs/screenshots/Screen Shot 2021-08-19 at 11.09.28 am.png">
<img src="docs/screenshots/Screen Shot 2021-08-19 at 11.09.43 am.png">
<img src="docs/screenshots/Screen Shot 2021-08-19 at 11.09.49 am.png">
<img src="docs/screenshots/Screen Shot 2021-08-19 at 11.10.42 am.png">
<img src="docs/screenshots/Screen Shot 2021-08-19 at 11.14.24 am.png">
<img src="docs/screenshots/Screen Shot 2021-08-19 at 11.14.30 am.png">


## Tech Stack
This application as been created using HTML, CSS, SCSS, Javascript and Ruby on Rails. This app is deployed on Heroku and GitHub.

## User Stories
As a Barber, I want to find more clients who are willing to try new and unique hairstyles with me so I can maintain a specific client base to showcase on my haircut portfolio.

As a Barber Client, I want to find a barber who specialises in hair art so I can display my eccentric style and personality.

As a Barber, I want to find more clients who want to talk openly about art and music so we can share mutual topics of conversation in our appointments.

As a Barber Client, I want to find a barber who understands me on a personal level and have a good relationship with while I get my haircut so I feel more comfortable in the shop.

As a Barber, I want to find and contact clients with a specific style to utilise them as my model in my hair exhibition shows and demonstrations.

As a Barber Client, I want a barber who is real and honest with me about my haircut expectations and is willing to suggest something cool to try out.

As an Apprentice Barber, I want to find clients with facial hair to help me practice my shaving and beard trimming skills.

As a Barber Client, I want to find a barber who specialises in how to cut and style curly hair as there are not many barbers in my area who can do this.

As an Apprentice Barber, I seek out clients who are willing to come in for hair colouring services to  improve my hair colouring skills and procecss.

As a Barbershop owner, I want to promote healthy and positive topics of conversations between my barbers and their clients by attracting a specific demographic of people into mny shop.

## Wireframes


## ERD


## Abstractions


## Third Party Services


## Active Record Associations


## Database Relations


## Database Schema Design


## Project Management