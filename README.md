![Screenshot of the website logo](/documentation/logo-header-1-with-subtitle.png)
---
# *Rafal Zygula's Literary Universe - Author Website*

Rafal Zygula's Literary Universe is a website where people can learn about literary works of Rafal Zygula including novels, audiobooks and poetry, and find information where the works are available. The visitors will be able to subscribe to a newsletter with exclusive content and easily find social links to the author's pages.

Website can be accessed here [Rafal Zygula's Literary Universe](https://cptvalleyberg84.github.io/zyg-author/)

![Responsive Mockup](/documentation/responsive-mockup2.png)

## Intro

**Project Descritpion**

A personal website for Rafal Zygula, a visionary writer and author of "THE AGE OF NEW ERA". Website will serve as a platform to showcase Rafal's literary works, share updates, and connect with readers and fans. The site includes a short about section, works section with selected works and links to works, and social medias, and a sign-up form to a newsletter.

**Purpose**

The maini purpose of this website is to create an engaging online presence for Rafal Zygula, allowing readers to learn more about his work, stay updated with his latest projects, and easily connect with him through various channels.

**User demographic**

The target audience:
+ readers and fans of Rafal Zygula's work.
+ literature enthusiasts interested in science-fiction and poetry, personal development, overcoming obstacles and future of human civilisation.
+ individuals looking for inspirational and thought-provoking content.

## Features

+ **Navbar**
    
    + positioned at the top of the page

    + contains branding of the author

    + includes links to:
        - Home 
        - Works
        - and Sign Up page

    + links have feedback hover effect.

    + selected and active page is highlighted by a bold font to make it easy to understand currently viewed page

    + a responsive navigation bar that adapts to different screen sizes.

        * Desktop and Tablets wiht logo in the center and menu options below

        ![Desktop Navbar](/documentation/navbar-desktop.png)

        * Mobile devices with logo in the center and menu options hidden under hamburger menu on the right side of navigation bar

        ![Mobile Navbar](/documentation/navbar-mobile.png)

        * Dropdown menu bar is appearing after clicking the hamburger menu

        ![Mobile Navbar](/documentation/navbar-mobile-open2.png)

    + feedback effect when hovering with mouse appear only over the titles that take you to other sections:

        * Hover over the logo shows dark red stylish underline. Clicking the logo takes you to the index - "Home" page

        ![Logo Hover](/documentation/logo-hover-feedback.png)

        * Hover over menu options changes the color to the dark red stylish with underline.

        ![Menu Hover](/documentation/menu-hover-feedback.png)

        * Hover over mobile menu also changes color to dark red with the underline

        ![Mobile Menu Hover](/documentation/mobile-menu-hover-feedback.png)

        * Menu Titles are Red, when not visited, but turn Green after they were visited once, and while active they be blue for the click

+ **Content Sections**

    + **Landing Page** - consists of 2 sections:

        - **Author Section**: Features an image and a brief introduction.

        ![Author Section](/documentation/home-page.png)

        - **Bio and Quotes**: Provides Insights into Rafal's writing journey and philosophical reflections.

        ![Bio and Quotes Section](/documentation/home-page2.png)
        
    + **Works**: Provides the list of works and links to webshops where the work can be purchased.
        - Work Images are also clickable links.
        - all links open in new tabs.
        
        ![Works Section](/documentation/works-section.png)

    + **Sign-Up**: page with a sign-up form for the Rafal's newsletter and short description of benefits that come with signing up.

        - Sing-up Form has all the fields required in order to submit. 
             - Sign-up Form Submit button:
                - on hover the font transforms to uppercase letters and becomes bold
                - on active the button border-radius gets bigger

        ![Sing-up Form](/documentation/sign-up-form.png)

    - **Thanks for Subscribing**: page with feedback after signing to the newsletter - A thank you note.

        ![Thank you note](/documentation/sign-up-form2.png)

+ **Footer** 
    
    + footer with links to social media profiles, allowing users to connect with Rafal on Facebook, YouTube and Instagram.
    
    + links open in new tabs

    ![Footer Social Media Links](/documentation/footer-icons.png)

    + link icons highlight on hover

    ![Footer Social Media Highlight](/documentation/footer-icons-highlight.png)

+ **Miscelenous**

    + Additionally, all anchor links are Accessible Rich Internet Applications (ARIA) with aria-labels to enhance accessibility, especially important as my novel is also available in audiobook format.

### Features left to implement

- The website will undergo several extensions:

    - Menu options

        * more menu options including: Blog, Forum, Q&A, Sandbox and possibly more. 
    
    - Home page

        * adding more content focusing on news with added date of entry. Similar to blog - but shorter news with links to the Blog section.
        * the News will wrap with flexbox to remain responsive.
    
    - Works section
        * adding more works
        * rebuilding works section into a page with additional menu on the left where the work can be easily selected

    - Adding more sections as mentioned in Menu options.

    - Adding more social media links in the footer. 

## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) used as the foundation of the site.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/css) used to add the styles and layout of the site.
- [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) used to arrange items simmetrically on the pages.
- [Balsamiq](https://balsamiq.com/) used to make wireframe prototypes for the website.
- [GitHub](https://github.com/) used to host the code of the website and deploy the website.
- [GitPod](https://www.gitpod.io/) used to write the code.

## Design

**Color Palette**

![Color Palette of the Author Website](/documentation/color-palette2.png)

   * Beige and its various gradients were used for the background and styling of the text boxes due to its cream and paper-like appearance, creating a strong connection to the reading and writing experience of newspapers, magazines and books.
   * Black color was used for the font, to enhance readability of the written word and the paper-look feeling
   * Matching Red and Green colors were chosen as a hover effect accents to highlight link properties of the text

**Typography**

+ Libre Caslon Text, Serif
    - Used as the main font for the website text - this same font is also used for the text in printed and ebook version of my debut novel. I'd like the audience to feel comfortable and familiar whether visiting my website or reading my works.

    ![Typography Caslon for Paragraph](/documentation/typhography-caslon-paragraph.png)

    - Libre Caslon Text with Uppercase property is also used as the font of the main page logo with added bold font weight, which is also a sentimental choice related to the printed works.

    ![Typography Caslon for Logo](/documentation/typhography-caslon.png)

+ Playfair Display, Serif

    - Carefully selected Playfair Display with its more decorative typeface brings a doze of freshness in all headers around the website.

    ![Typography Playfair Display for Headers](/documentation/typhography-playfair.png) 

**Design Inspiration**

As I am personally very connected to the paper and writing, I wanted the website to have a layout inspired by and reminniscent of traditional printed newspapers. I will continue to make the landing page look like a front page of magazine with stylized as such headers and paragraphs. 

## Manual Testing

+ **QA**
    + Manual testing has been conducted to ensure the website functions as intended across different browsers and devices. Key aspects tested included:
        - navigation links
        - form submissions
        - responsiveness 
        - and layout integrity

    - website was sent to members of family and friends and tested in different browsers, phones and computers.

+ **Compatibility**
    + To confirm funcitonality in different environments, the website was tested on:
        - Desktop
            - Firefox 
            - Ms Edge Browser
            - Opera Developer
        - Mobile Android
            - Chrome
            - Edge
            - Firefox
        - Iphone iOS
            - Safari
    + No issues reported with the deployed website during the testing.

+ Sample compatibility pictures:
    - [Edge](/documentation/compatibility-edge.png)
    - [Opera](/documentation/compatibility-opera.png)
    - [Firefox](/documentation/compatibility-firefox.png)

+ The website responsiveness was also checked with [Am I Responsive?](https://ui.dev/amiresponsive).

    Below, a sample gif showcasing responsiveness of 4 different screens and website features.
    ![Am I Responsive?](/documentation/am-i-responsive-gifcap.gif)

+ **Validator Testing**

    - No errors were returned when passing through the official [W3C HTML Validator](https://validator.w3.org/) 

    ![HTML Validation screenshot](/documentation/w3c-html-validator.png)

    - No errors were returned when passing through the official [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) 

    ![CSS Validation screenshot](/documentation/w3c-css-validator.png)

+ **Bugs**
    + No significant bugs have been identified. Minor adjsutments were made to improve performance and user experience. 

    + However, several obstacles have been noted and solving them improved the experience and overal design and functionality of the website:

        - building responsive design, especially with the menu met with few difficulties, but all where solved after finding the "all: unset;" property and building it again from scratch.

        - floating text box on the image at the Home page was misbehaving while working in media query min-720px, solved as above, by setting "all: unset;" and building from scratch. 

+ **Google Pagespeed Insights report**

    - according to Google Pagespeed Insights report the index page could performing better and is perfectly accessible and readable with great SEO.
    - performance of Index and Works pages are affected by using High Quality Images.

        - Index/Home Page Insights:

            - [Pagespeed Insights Home Page Mobile](/documentation/pagespeed-insights-report-index-mobile.png)

            - [Pagespeed Insights Home Page Desktop](/documentation/pagespeed-insights-report-index-desktop.png)

        - Sign-up Page Insights:

            - [Pagespeed Insights Sign-up Page Mobile](/documentation/pagespeed-insights-report-sign-up-mobile.png)

            - [Pagespeed Insights Sign-Up Page Desktop](/documentation/pagespeed-insights-report-sign-up-desktop.png)


+ **There are no unfixed bugs to report.**

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - [Rafal Zygula's Literary Universe](https://cptvalleyberg84.github.io/zyg-author/index.html)

## Credits

**Content**

- Text written by my hand and keyboard.
- The photo and images of book covers used on the website are coming from my personal files.
- The favicon was generated with [Real Favicon Generator](https://realfavicongenerator.net/) based on a graphic made from a photography of my painting called "Struck by Lightning Ying-Yang" - story of the painting creation is mentioned in my debut novel.
- The icons for the footer and hamburger menu icon were taken from Font Awesome [Free Icons @ Font Awesome](https://fontawesome.com/).

**Media**

1. [CSS Styling Links](https://www.w3schools.com/css/css_link.asp)

2. [Free Icons @ Font Awesome](https://fontawesome.com/)

3. [Code Institute Love Running Project Github Page](https://github.com/cptvalleyberg84/Love-Running/blob/3c4dabc87ed68d9f9ab2b2345180f57b7f3814ff/index.html)
4. [Code Institute Love Running Project Deployed Website](https://cptvalleyberg84.github.io/Love-Running/index.html)
5. [Code Institute Love Running Project Course Lessons](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LRFX101+4/courseware/e805068059af42af87681032aa64053f/7525117e5cd144daa2a7b0c57843bbee/)
6. [Code Institute Love Running Project Course Videos](https://www.youtube.com/watch?v=KvUJZfwiOyQ)

7. [How to reset/remove CSS styles for a specific element or selector only](https://stackoverflow.com/questions/15901030/how-to-reset-remove-css-styles-for-a-specific-element-or-selector-only)

8. [Captain Anonymous](https://codepen.io/pen/)

9. [RGBA Color Picker](https://rgbacolorpicker.com/)

10. [Kevin Powell YouTube Channel](https://www.youtube.com/watch?v=hwbqquXww-U&list=PL4-IK0AVhVjMSb9c06AjRlTpvxL3otpUd)

11. [Slaying the Dragon YouTube Channel](https://www.youtube.com/watch?v=phWxA89Dy94)

12. [HTML Entity for the Middle Doc](https://stackoverflow.com/questions/7250381/html-entity-for-the-middle-dot)

13. [Website Design Inspiration](https://www.lesleymmblume.com/)

14. [Wireframe with Balsamiq](https://balsamiq.com/)

15. [Real Favicon Generator](https://realfavicongenerator.net/)

16. [Am I Responsive?](https://ui.dev/amiresponsive)

17. [gifcap](https://gifcap.dev/)

18. [PageSpeed Insights](https://pagespeed.web.dev/)

## Special Thanks

Thank you to the Code Institute HTML and CSS Essentials courses.

Would love to say thank you to the CI Tutor team for the help with placing the nav-toggle-label.

Big **THANK YOU** to my amazing Mentor Juliia_Konn for guidence and additional tips and tricks!

###### End of Project
