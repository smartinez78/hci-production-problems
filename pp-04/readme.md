## ITMD 362, Production Problem 04: Implementing HCI guidelines for Touchscreens

## The Problem

Using the HCI guidelines from either iOS or Android, sketch a new small-screen touch-friendly design
for the membership/join page for Chicago’s Museum of Contemporary Art at
https://experience.mcachicago.org/donate/contribute1?ct=6 (Hint: visit the URL on your phone).

**You only need to sketch your redesign**, and in the text below, reference at least three different
points of guidance from chosen HCI guidelines that went into your redesign sketches (you might
want to do multiple sketches, each highlighting a different feature of the same overall design).

## Resources

* Apple iOS HCI Guidelines:
  https://developer.apple.com/design/human-interface-guidelines/
* Android Guidelines:
  https://developer.android.com/design

## Deliverables

Small commits to your Production Problems repository that include:

1. photographs of sketches of your new design, from your sketchbook
2. an explanation of three different points of guidance from your chosen guidelines (point to the
   specific URL where the guidance can be found) that you implemented in your sketch, written below:

* HCI Guideline One (URL):https://developer.apple.com/design/human-interface-guidelines/ios/user-interaction/data-entry/
* Describe how you implemented that guideline in your sketch: I implemented a few data entry guidelines in my sketch.
One of the points states that a site should only require fields for information that is truly necessary.
Based on what the MCA form should do, only the membership type is truly important. Adding a second cardholder is optional, so
although the ability to select adding an additional person is there, it is not required. Basic membership is the default
value in the list, which I think is reasonable according to the guidelines, and the list is sorted alphabetically to make locating the membership option easier.

* HCI Guideline Two (URL): https://developer.apple.com/design/human-interface-guidelines/ios/app-architecture/navigation/
* Describe how you implemented that guideline in your sketch:
Describe how you implemented that guideline in your sketch: I kept some of the navigation guidelines in mind.
The current MCA mobile website has really messy tabs, the words are jumbled together and they don't look like buttons
you can click on at first glance. One of the guidelines states that it should be fast and easy to get content. In the sketch, the
different tabs are combined into a collapsible menu. The user will click the menu button and the choices for other pages will appear.
This will make it easier to read because each different tab will appear bigger on the screen, and they will all be stacked neatly on top of each other.
Although different than what an app would do, this also provides a clear path.
The user will know what button to refer to if they want to move to another page, but the site is kept clutter free.

* HCI Guideline Three (URL): https://developer.apple.com/design/human-interface-guidelines/ios/visual-design/adaptivity-and-layout/
* Describe how you implemented that guideline in your sketch: One of the visual design guidelines says that visual elements
should fill the screen, backgrounds should extend to the edges of the display. The current MCA site has a background that is not
only distracting, but also fails to fill the entire screen. I decided to get rid of it altogether in my sketch, opting for a solid color instead.
I also implemented alignment for ease of scanning. One of the issues of the MCA website is that, at the bottom, there is a section full of contact information and museum hours. The information is useful but it's very difficult to follow because the text is not aligned in regards to each other.
Improving the spacing and making sure that the contact information section is aligned with the location and hours section will make it easier to
read. I noticed that a lot of museums only show if the building is open on the day the user visits the site. For example, if a user visits Shedd's website
on a Monday, and the museum is open, the website will state that it is currently open and list the Monday visiting hours. The full schedule is still available on the site elsewhere. I think this would work for MCA and would make the bottom of the page look friendlier.
