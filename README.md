> NEEDS TO BE EDITED
> MICHELLE WAS HERE!!

# Lesson 3 Project
This project will assess your knowledge and skills using the various concepts taught within the lesson. 
1. You will need to create 2 HTML pages that utilize the appropriate semantic elements to achieve the desired goal of the steps. 
2. You will need to style the pages following the directions. 
3. You will need to validate your code to ensure there are no errors or problems.
4. You will need to apply the accessibility best practices you have learned.

## Project Prep
1. If you haven't done so already, clone the repo to your computer within your course folder.
2. Open the repo within VS Code. You can open this `readme.md` file within VS Code to view the project directions there. 
   > *TIP: Right click on the file and choose the `Open Preview` option.*
3. If there are files and folders present other than this `readme.md` file, take some time to familiarize yourself with the files within the repo so you know where they are located. This will help you when asked to use them within the project directions.

> TIP: Before beginning any work on the project, read through all the steps to understand what you will be doing.

## Reflection Page Directions
Complete the following steps:
1. Create an `index.html` file.
2. Add the DTD and necessary basic elements that define the HTML document.
3. Identify the language of the page as *English*.
4. Within the document head:
   1. Add a page title of: `HTML Examples`
   2. Add a metadata element to identify the character set as `UTF-8`.
   3. Add a metadata element to identify the author as you (i.e., put your name in as the value.)
   4. Create a link to the `main.css` file. 
      > *TIP: Refer to the CSS Styling Directions below to determine the file path.*
5. Save the file and apply a commit to your file.
6. Within the document body:
   1. Create a `div` element with an `id` of `side-menu`. Add the following as children.
      1. Create a navigation element.
      2. Create 2 navigation links. 
         1. One for `Home` that links to the `index.html` file.
         2. And one for `Checkout Form` that links to `checkout.html`.
   2. Create a main element and add the following as children:
      1. A header.
      2. A section.
      3. A footer.
   3. Within the header:
      1. Create a heading with the following text: `HTML Element Reflection`
   4. Within the section:
      1. Create a heading with the text: `My Reflection`
      2. Create a paragraph and answer the following:
         > *TIP: If you need additional paragraphs or would like to use additional elements, like lists, you may do so.*
         1. Reflect upon what you learned in this lesson and identify at least three things (elements, concepts, etc.) that were new to you and how you think you may use them in a project?
      3. Create another heading with the text: `My Next Steps`
      4. Create a paragraph and answer the following: 
         > *TIP: If you need additional paragraphs or would like to use additional elements, like lists, you may do so.* 
         1. Reflecting on what you learned, what element or concept do you feel you need to learn more about? Why do you feel that way? What steps do you feel could help you learn more about it? 
   5. Save the file and apply a commit to your file.
   6. Within the footer:
      1. Create an unordered list with the following list item: `Lesson Activities`.
      2. Create a nested unordered list with 6 list items. Each list item should be a hyperlink to the HTML files you created during the practice activities you for the lesson. Do not link to the index.html practice activity file.
      > TIP: You can get the URLs to use for the `href` by opening the practice activity repo on GitHub within your browser, navigating to the HTML file, and then copying the URL from the address bar in your browser. You can then repeat this process for each file.
   7. Save the file and apply a commit to your file.

## Shopping Cart Form Directions
1. With the `index.html` file open, use the Save As command to create a new file called `checkout.html`.
2. Change the page title to: `Cart Checkout Form Component`
3. Change the heading within the header element to: `Shopping Cart Checkout Component`
4. Remove the headings, paragraphs, and any other elements from the section element (leaving the section element tags).
5. Within the section element:
   1. Create a form using the postback script from the lesson.
   2. Create two fieldsets with legends.
      1. One fieldset set will be for shipping details.
      2. The other will be for payment details.
   3. Within the shipping details fieldset, create the necessary labels and appropriate input field types for the following. **Do not use only text fields**:
      1. Name
      2. Address 1
      3. Address 2
      4. City
      5. State
      6. Zip Code
      7. Phone
      8. Email
   4. Save the file and apply a commit.
   5. Within the payment details fieldset, create the necessary labels and appropriate input field types for the following:
      1. Name on card
      2. Card number
      3. Expiration date
      4. Verification number (i.e., the 3 digit CCV number on cards)
   6. Save the file and apply a commit.
   7. Mark all fields, except address 2, as being required.
   8. Apply the following pattern to the zip code field to ensure a 5 or 9 digit value is entered: `^(?(^00000(|-0000))|(\d{5}(|-\d{4})))$`
   9. Apply the following pattern to the card number field to ensure only numbers and the expected count of numbers is entered: `^[0-9- ]{13,19}$`
   10. Create a submit button that says `Purchase`.
   11. Save the file and apply a commit.

## CSS Styling Directions
You will need to create any and all selectors that are needed to target the specific elements on the page. You may utilize tag selectors, classes, ids, pseudo-classes, multiple selectors, descendant selectors, etc. to select the appropriate element.
1. Create a new folder with the name: `css`
2. Within the new folder, create a new file and call it `main.css`.
3. Add a comment at the top of the document and include the following information:
   1. Authored by: *Put in your first and last name*
   2. Course: CIS233DA
   3. Section: *Put your 5 digit section*
4. Style the html and body elements as follows:
   1. Add a height of `100%`.
   2. Set the margin on all sides to `0`.
   3. Set the padding on all sides to `0`.
   4. Apply a sans-serif font family and fallback families of your choosing.
   5. Apply a background color of your choosing.
   6. Apply a `16px` font size.
   7. Apply a text color of your choosing that will allow text to be legible against the background color.
5. Save the file and apply a commit.
6. Style the `side-menu` as follows:
   1. Float the side menu to the left.
   2. Apply a width of `200px`.
   3. Apply a right solid border with a width of `2px` and a color of your choosing.
   4. Apply a background color.
   5. Set the height to be `100%`.
   6. Set the `overflow` property to `hidden`.
7. Style the links that are descendants of the `side-menu` element. Hint: the selector should be structured like this: `.parent descendant`
   1. Apply padding around the links.
   2. Apply a color of your choosing.
   3. Change the element's display to be `block` level.
   4. Remove the text decoration.
8. Style the hover states for the links that are descendants of the `side-menu` element to adjust the background and text color.
9. Save the file and apply a commit.
10. Style the main element as follows:
   1. Apply a width using the value of: `calc(100% - 202px)` 
      > *TIP: You'll learn more about how to use the calc() notation in later lessons. To get this to work, make sure there is a space before and after the mathematical operator.*
   2. Float the element to the left.
   3. Set the padding to `0` on all sides.
11. Style the header element as follows:
    1. Apply a background color of your choosing that is darker than the body background color.
    2. Align the text to the center.
    3. Change the text color to make it readable against the background color.
    4. Add a padding of `16px` to all sides.
12. Save the file and apply a commit.
13. Style the headings within the section element as follows:
    1. Apply a thin solid bottom border and a thick solid left border with a color of your choosing.
    2. Apply a left padding of `16px`.
    3. Apply a left margin of `8px`.
14. Style the paragraphs within the section element as follows:
    1. Apply a left margin of `20px`.
15. Save the file and apply a commit.
16. Style the footer as follows:
    1. Apply a background color to match the header element.
    2. Adjust the text color.
    3. Add a padding to all sides.
17. Style the unordered lists in the footer as follows:
    1. Remove the list style.
    2. Allow the browser to apply the margins automatically.
    3. Define the width to be `60%`.
18. Save and apply a commit to the file.

The following is an example screenshot of what your page should look like at this point, barring any differences in content, colors, fonts, etc.

![screenshot of index page](images/L1-prj-page-example.png)

### Style the Form
1. Style the form element as follows:
   1. Set the minimum height to be `500px`.
   2. Set the minimum width to be `830px`.
2. Style the fieldset element as follows:
   1. Add a top and bottom margin of `5px` and a left and right margin of `10px`.
   2. Define the width to be `40%`.
   3. Float the element to the left.
3. Apply a bold font weight to the legend element.
4. Style the label elements as follows:
   1. Change the element's display to be `block` level.
   2. Apply a bold font weight.
   3. Apply a top margin of `8px`.
5. Style the input elements as follows:
   1. Change the element's display to be `block` level.
   2. Add a top and bottom margin of `5px`, a left margin of `20px`, and no right margin.
   3. Set the width to be `300px`.
6. Style the submit button as follows:
   1. Add a top and bottom margin of `8px` and a left and right margin of `16px`.
   2. Add a background color of your choosing.
   3. Add a text color to allow the text to be read.
   4. Add a thin solid border with a color of your choosing.
   5. Set the left margin to `50px`.
7. Create a hover state for the submit button and swap the background and text colors.
8. Apply any additional stylings like margins, padding, etc. to help improve the layout, whitespace, and design of the site.
9. Save and apply a commit to the file.

The following is an example screenshot of what your page should look like at this point, barring any differences in content, colors, fonts, etc.

![screenshot of form page](images/L1-prj-form-example.png)

## Submit the Project
Before you submit your project:
1. Make sure that you have validated your HTML and CSS code. If any errors were found within the validators, be sure to fix those errors before you submit your assignment.
   > TIP: The validator extensions that you installed during the course introduction will provide details within the Problems tab as you code, which you can open from the `View` menu and then selecting the `Problems` option.
2. Save your files and apply any final commits to your work.
3. Push (i.e., sync) the repo on your computer with GitHub to ensure all files are uploaded for your instructor to see.
4. Verify that all files appear on GitHub.
> TIP: You can view any of your repos by going to the GitHub organization for the course - [RSC-CIS233DA-in-v8](https://github.com/rsc-cis233da-in-v8). You can bookmark the page for future reference. 
5. Open the Pull Requests tab within GitHub (or using the GitHub Extension within VS Code).
6. In the comment field, 
   1. Type in your instructor's username with an `@` before. See the course announcements for their username to use. 
   2. Put a note to your instructor that the assignment is ready to grade.
7. Click on the `Comment` button to finalize and submit your assignment for grading.

