# RPS Bootstrap

## Setup

Follow the usual setup steps:

 1. Ensure that you've forked this repository to your own GitHub organization. So, you should have a copy at `https://github.com/[YOUR ORG NAME]/rps-frontend`.
 1. Follow the [Starting on a project with Cloud9](https://guides.firstdraft.com/getting-started-with-cloud9.html) guide to set up your workspace.
 1. I always recommend closing as many browsers tabs as possible from the last project you were working on — it's very easy to get confused with too many tabs going.
 1. At a Terminal prompt, set up the project (install a bunch of powerful libraries on the workspace, whatever the project depends upon, etc):

    ```
    bin/setup
    ```

 1. Once the previous step completes successfully and you're back at the `$` prompt, launch your Rails application server by clicking the "Run Project" button at the top of the IDE. You'll know it launched when it says "Press Ctrl-C to stop".
 1. Visit the live application preview URL that it gives you to see the app running.
 1. If you want to peek at the instructor's workspace from time to time (e.g. to catch up if you fall behind), it is located at (depending on which section you're in):
    - Tuesday section: https://ide.c9.io/demostudent7/rps-frontend-tuesday
    - Thursday section: https://ide.c9.io/demostudent7/rps-frontend-thursday
    - Saturday section: https://ide.c9.io/demostudent7/rps-frontend-saturday

    Ignore the "request access" banner at the top; that is only if you need to edit my code (which you don't). You can click into any folder and file to view anything already.

### Intermediate target

[http://rps-bs4-intermediate.herokuapp.com/](http://rps-bs4-intermediate.herokuapp.com/)

### Final target

[http://rps-bs4-final.herokuapp.com/](http://rps-bs4-final.herokuapp.com/)

## Some handy links

### Documentation

 - [Official Bootstrap Docs](http://getbootstrap.com/)
    - [Outline buttons](http://getbootstrap.com/docs/4.2/components/buttons/#outline-buttons)
    - [Cards with contextual colored borders](http://getbootstrap.com/docs/4.2/components/card/#border)
    - [Alerts](http://getbootstrap.com/docs/4.2/components/alerts/)
    - [Table contextual classes](http://getbootstrap.com/docs/4.2/content/tables/#contextual-classes)
    - [The Grid](http://getbootstrap.com/docs/4.2/layout/grid/#all-breakpoints)
 - [Bootstrap 4 Cheatsheet](https://hackerthemes.com/bootstrap-cheatsheet)

### Assets

 - These folks helpfully host bootstrap.css on their own server: [BootstrapCDN](https://www.bootstrapcdn.com/)
 - Bootstrap's Javascript components (like modals, hamburger menu, carousel, etc) depend on another open-source library called jQuery; you can grab it from this CDN: [jQuery CDN](https://code.jquery.com/).
 - Ultimately, a quick and easy way to get all of Bootstrap and Font Awesome is to include the following in the `<head>` of your document:

    ```html
    <!-- Expand the number of characters we can use in the document beyond basic ASCII 🎉 -->
    <meta charset="utf-8">
    <!-- Connect Font Awesome CSS -->
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.6.3/css/all.css">
    <!-- Connect Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css">
    <!-- Connect Bootstrap JavaScript and its dependencies -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/js/bootstrap.bundle.min.js"></script>
    <!-- Make it responsive to small screens -->
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    ```

### Bonus

 - [Shoelace.io](http://shoelace.io/) (you can practice by creating a layout for [this target](http://appdevspring16.github.io/friendbook/raghu-b.html))
 - [Bootswatch](https://bootswatch.com/)
 - [Premium themes](https://themes.getbootstrap.com/)
 - [Bootstrap.build](https://bootstrap.build/app) (you can practice by making a UChicago branded theme; see pages 38-41 of our [Identity Guidelines](https://news.uchicago.edu/sites/default/files/attachments/_uchicago.identity.guidelines.pdf))
 - [Butterick's Typography in ten minutes](https://practicaltypography.com/typography-in-ten-minutes.html)
 - [Google Web Fonts](https://fonts.google.com/) and a few resources to [help](http://typ.io/libraries/google) [choose](http://femmebot.github.io/google-type/) [pairings](https://fontpair.co/)
