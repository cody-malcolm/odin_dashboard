# Odin Dashboard Clone

## Objective

To create a clone of the ~~Google Search Results page~~ Odin Dashboard using HTML and CSS.

#### Specifications

##### Main

##### Main

1. Don't be a perfectionist
 * The page is just supposed to look like ~~Google's~~ The Odin Project's page, not function like it
 * Spacing just needs to *similar*, not down to the pixel.
 * Dropdown menus, form submissions, and hover-highlighting should be ignored
2. Do as much as you can before viewing the page's source code or relying on Dev Tools
3. When complete, project should be pushed to GitHub. Git should be used for Version Control.

##### Optional

4. Submit a pull request to contribute this solution to The Odin Project.

##### Ambiguous

5. Should the project be mobile responsive?

#### Learning Objectives

This project is designed to facilitate practice towards mastery of HTML and CSS. In addition, it allows for practice creating and modifying a Version Control project with Git and GitHub. This is comparable to the "hard" version of the Google page project.

#### Preliminary Thoughts

The usual project is to create a clone of the Google Search Results page using HTML and CSS. However, [I already did this a couple of years ago](https://github.com/codyMalcolm/google_homepage). Now that I'm a 2nd-year Computer Science student, I decided to pick back up where I left off. However, I don't want to jump right back into the middle of Ruby on Rails without refreshing myself on the fundamentals of HTML, CSS, and JavaScript, so I decided to redo the early projects from scratch. In the case of this project, however, I wasn't eager to do the exact same page again, so after a bit of thinking I decided to do a comparably complex page, and what better page to do then the Odin Project dashboard?

#### Final Thoughts

This project was a lot of fun. I essentially haven't used HTML or CSS in two years, but The Odin page was different enough from the original Google project that I could use my old work as reference material without it being "cheating", and was able to pick it all back up very quickly - while the syntax might be rusty, I still remember how things work, what can be done, and where to find great reference materials. Additionally, due to the differences between the two pages, I was able to implement some additional features that aren't present in the Google page, such as implementing a custom font, the replacement effect of the completion indicator, or the popout icon in the bottom right.

Speaking of the popout icon, unfortuately I wasn't able to get the popouts to work 100% correctly. Due to the limitations of CSS, you can modify sibling elements that occur later in the DOM, but not ones that appear before. As a result, if you hover over the uppermost popout icon (which is the one that appears later in the HTML), the lower icon will retreat. This functionality could be easily implemented using JavaScript, where you can modify anything in the DOM at will, but this project is meant to be done with HTML and CSS only, so I did the best I could with the tools available.

As with my previous Google Search Results page, you can test the mobile responsiveness by resizing the browser window.

## Miscellaneous

Read more about this project at The Odin Project's [Web Development curriculum](http://www.theodinproject.com/courses/web-development-101/lessons/html-css).
