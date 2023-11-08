


## About Us

Spending the majority of your time on campus, whether living, working, or attending classes, results in the accumulation of various campus-specific items. This scenario has given rise to a growing demand for a platform that can facilitate the buying and selling of these goods. Introducing "uh-marketplace," a user-friendly application designed to cater to the needs of students right here at UH Manoa. For further details, please continue reading.

## Objectives/Goals

Our objective for this app is to facilitate the process of buying, selling, and even trading items at UH Manoa, making it easier than ever before. By doing so, we aim to help people save money, prevent items from going to waste, and enable them to earn back some of their expenses. Given the ever-changing population of students at UH Manoa, this app has the potential to benefit a wide range of people.

## What we offer

We offer a way for students to buy/sell items. The marketplace is open for everyone to explore, allowing easy navigation through a search bar and a selection of pre-made filters. However, enhanced functionality becomes accessible when users log in as a "User" (specifically UHM students). As registered Users, individuals gain the ability to not only browse the marketplace but also delve into seller profiles, which display the user's listed items and their respective ratings. Moreover, Users can take actions such as ordering, making offers, and purchasing goods directly from the marketplace. They can also create listings for items they wish to sell. Additionally, Users have the option to report other users or specific items on the marketplace that may violate guidelines. Administrators possess the authority to remove items from the marketplace if they are deemed unsafe, inappropriate, or illegal, ensuring a safe and reliable environment for all users.

## Instllation
First, [install Meteor](https://www.meteor.com/install).

Second, go to [https://github.com/ics-software-engineering/meteor-application-template-react](https://github.com/ics-software-engineering/meteor-application-template-react), and click the "Use this template" button. Complete the dialog box to create a new repository that you own that is initialized with this template's files.

Third, go to your newly created repository, and click the "Clone or download" button to download your new GitHub repo to your local file system.  Using [GitHub Desktop](https://desktop.github.com/) is a great choice if you use MacOS or Windows.

Fourth, cd into the app/ directory of your local copy of the repo, and install third party libraries with:

```
$ meteor npm install
```

## Running the system

Once the libraries are installed, you can run the application by invoking the "start" script in the [package.json file](https://github.com/ics-software-engineering/meteor-application-template-react/blob/master/app/package.json):

```
$ meteor npm run start
```

The first time you run the app, it will create some default users and data. Here is the output:

```
 meteor npm run start 

> meteor-application-template-react@ start /Users/carletonmoore/GitHub/ICS314/meteor-application-template-react/app
> meteor --no-release-check --exclude-archs web.browser.legacy,web.cordova --settings ../config/settings.development.json

[[[[[ ~/GitHub/ICS314/meteor-application-template-react/app ]]]]]

=> Started proxy.                             
=> Started HMR server.                        
=> Started MongoDB.                           
I20220529-12:09:18.384(-10)? Creating the default user(s)
I20220529-12:09:18.389(-10)?   Creating user admin@foo.com.
I20220529-12:09:18.453(-10)?   Creating user john@foo.com.
I20220529-12:09:18.515(-10)? Creating default data.
I20220529-12:09:18.515(-10)?   Adding: Basket (john@foo.com)
I20220529-12:09:18.599(-10)?   Adding: Bicycle (john@foo.com)
I20220529-12:09:18.600(-10)?   Adding: Banana (admin@foo.com)
I20220529-12:09:18.601(-10)?   Adding: Boogie Board (admin@foo.com)
I20220529-12:09:18.773(-10)? Monti APM: completed instrumenting the app
=> Started your app.

=> App running at: http://localhost:3000/
```

Periodically, you might see `Error starting Mongo (2 tries left): Cannot run replSetReconfig because the node is currently updating its configuration` after the `=> Started HMR server.`. It doesn't seem to be a problem since the MongoDB does start.

### Viewing the running app

If all goes well, the template application will appear at [http://localhost:3000](http://localhost:3000).  You can login using the credentials in [settings.development.json](https://github.com/ics-software-engineering/meteor-application-template-react/blob/main/config/settings.development.json), or else register a new account.

### ESLint

You can verify that the code obeys our coding standards by running ESLint over the code in the imports/ directory with:

```
meteor npm run lint
```

## Landing Page
This is the first page anyone can view as they are viewing our website. It shows all the items that users list.

(INSERT IMAGE)

#### Not Logged In

If the user is not logged in, then you will have limited access to the website. You can only view the landing page.

(INSERT IMAGE)

#### Logged In

If the user is logged in then you will have more access to the website. A nav bar will appear with "Sell" and "My Listings" option.

(INSERT IMAGE)

## Sign Up Page

If users dont have an account they can sign up through this page.

(INSERT IMAGE)

## Login Page

Users can login through their account through this page.

(Insert IMAGE)


## Sell Page

This page is where you can list your own items to be sold.

(INSERT IMAGE)

## My Listings Page

This is where you can view and edit the information of all your items that you have added to the sell page.

(INSERT IMAGE)


## Admins

This is only for authorized access and these individuals can do edit and remove any item/User as they seem fit

(INSERT IMAGE)

## Members
Ryne Stagen, 
Zachary Stoddard,
Elijah Inofinada,
Brandon Underwood,
Mark Posey,
