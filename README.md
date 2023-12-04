# Web Accessibility Feature

<h2> Introduction </h2>

* **Description of Feature:**
  * The Web Accessibility feature is an accessible Random User Generator web page that passes ADA guidelines. The web page uses API data from https://randomuser.me/, and stores the data in various HTML5 components like main, details, unordered list, and table tags.
  
* **Group Members:**
  * Megan Steinmasel
  * Michael Belmear
  
* **Link to Project:**
  * [[Press here](https://mbelmear.github.io/CSCI-331/Final%20Project/)] 
  
* **Link to Presentation:**
  * [[Press here](https://github.com/megansteinmasel/web-accessibility/blob/main/Web%20Accessibility.pptx)] 

<h2> Creative Objective </h2>

* **Project Goal:**
  * The goal of the Web Accessibility feature is to educate the audience about how to make web pages accessible. 
    * Web accessibility is the inclusive practice of ensuring there are no barriers that prevent interaction with, or access to, websites on the World Wide Web by people with physical disabilities, situational disabilities, and socio-economic restrictions on bandwidth and speed(Wikimedia Foundation). Web accessibility encompasses all disabilities that affect access to the web, including auditory, cognitive, neurological, physical, speech, and visual.
  * The Web Accessibility Presentation outlines several instances of how to implement accessibility in a web page through coding and styling techniques. The Web Accessibility Presentation covers the following topics:
    * What is Web Accessibility & Importance
    * Who Enforces Web Accessibility
    * Assistive Technology
    * HTML5 Semantics
    * Text Alternatives
    * Keyboard Accessibility
    * Color Blindness Accessibility
    * Accessibility Checkers
    * Two Web Accessibility Demos
      
* **Problem Statement:**
  * Web Accessibility is important so everyone has equal access to online content. There is a growing amount of people with disabilities, and it is important to ensure they can access the web given these disabilities.
 
<h2> Tech Summary </h2>

* **Random User Generator Web Page:**
  * **Frontend** - Web Page:
    * How to Use:
        * Refresh the page for a new random user.
        * Check the tables and details menu for information about the random user.
        * Observe the styling, it is ADA-accessible.
    * Key Points (ADA Guidelines):
        * Page starts with a h1 heading.
        * Headings are structured in ascending order of h1, h2, h3.
        * Links are bolded/underlined to indicate they are pressable.
        * Line height is 1.5 times the font size.
        * Color contrast between the text and background is greater than or equal to 4.5:1 for small text and 3:1 for large text.
  * **Backend** - Code Outline:
    * HTML File: 
      * Body tag:
        * Header tag: goes inside the body element and acts as the main header for the web page.
          * Main tag: goes into the body element and specifies the main content.
            * Image tag: an inline element that needs to be placed inside a block-level element to validate (can't just be in the body element all by itself).
            * Heading tags: goes inside the body element and is used for headings.
              * Web pages must start with a h1 tag.
        * Footer tag <footer></footer> goes into the body element and contains any author and copyright information.
    * CSS File
      * If we are styling more than one element the same way, we must use a class because ids are unique.
      * Make sure there is color contrast.
      * The font size can not be fixed (px, pt, or cm), use ems/rems for sizing.
      * If we include any links, they must be underlined & bolded.
      * Line height must be 1.5 times larger than the font size.
      
* **Demos:**
  * Tools:
    * We used the Siteimprove Accessibility ADA Checker Chrome Extension, the Montana State University homepage, and our Random User Generator web page.
  * Process:
    * We ran the Siteimprove Accessibility Checker on the Montana State University homepage and noted the results.
    * We ran the Siteimprove Accessibility Checker on our Random User Generator web page and noted the results.
  * Results:
    * The Siteimprove Accessibility Checker produced 12 issues on the Montana State University homepage.
    * The Siteimprove Accessibility Checker produced 0 issues on our Random User Generator.

<h2> Conclusion </h2>

* **What I Learned:**
  * I learned that accessibility is very important to keep in mind while creating technology. It is easy for someone who is not disabled to create technology that works for them but does not work for disabled users. This goes to show why testing is so important with software applications & also having a diverse group of testers and developers.

* **What Worked & What Didn’t:**
  * While styling the CSS in the program, I realized that Web Accessibility and Web Design don’t necessarily go hand in hand. I kept trying to make our web page as aesthetic as possible but I kept getting accessibility errors. I mainly got these errors from color contrast that was not up to ADA standards. I also tried to left-align all the components on the web page since it is easier for disabled people to read left-align text. Although having your web page completely left-aligned might not be the best design choice, I kept some components aligned in the center.





