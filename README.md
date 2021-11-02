# IAM Design Guidelines
### IAM Design Checklist
---------------------------------
#### 1) Element based Things to be addressed
- Is logo's width & height same as the design
- Is Heading font related informations are verified 
    - Is font family, colour, size, letter spacing & line height are same
- Is Sub heading/description available, then
     - Is font family, colour, size, letter spacing & line height are same
- Form field group
    - Is label's font family, colour, size, letter spacing & line height are same
    - Is input field's width, height, background & border color and border-radius are same
    - Is positive & negative use-cases handled **Eg: Color of specific label & input field should be made as negative impact (It should be purely based on the design specifications)**
    [*Note: Should be handled all respective places*]
    - Is **Pseudo-class** features are handled ? **Eg: focus, hover, disabled should mainly be handled**
    [*Note: Should be handled all respective places*]
    - Is password field has show/hide feature
        - Whether values in password field getting merged with icon of show/hide feature
    - Error messages
        - Is error message shown as toaster message
            - Is the position, background colour, font family, font size & font color for the toaster is as expected
        - Is error message shown as individual text message
            - Is error messages appearing for individual or commonly for all fields
                - Is error text's font family, size, line height, letter spacing and spacing above & below are same
                - Is error text's gets hidden while user types on the input field
    - Button
       - Is font family, colour, size, letter spacing, line height, background colour & border properties are same
    - Checkbox
        - Is the checkbox element in the screen should be selected by default
        [*Note: If yes, styling states should be compared with **Pseudo-class** options*]
    - Helper Text
        - Is font family, colour, size, letter spacing & line height are same 
    - Fixed sections
        - Is there any position fixed section available for Responsive view **(Mobile, Ipad & Desktop)**
            - Whether section is positioned for responsive views individually ?
                - If yes, whether it is handled & verified properly in all screen sizes & orientation

<br/>

---------------------------------
<br/>

#### 2) Browser based checks
- Whether element styling and positioning is same in all browser
- Whether all the **Pseudo-class** properties are handled to support lower version of browsers
    **Note:**
    1) Google Chrome, Mozilla Firefox, Safari, Microsoft Edge & Opera are the browsers to verified and its mandatory.
    2) Also it should be checked Platform specific like Windows, iOS & Android

<br/>

---------------------------------
<br/>

#### 3) Accessibility Checks
- Keyboard based actions
    - Is the user's element selection using **TAB** key is enabled in browser. **Eg: If the user uses tab button elements will be highlighted. So feature should be enabled for sure, until unless client request's to remove this feature**
- Window resize actions
    - Whether all elements are in proper position while the window is resized manually by the user from large to smaller screens and vice versa
    - Elements do have smooth experience on automatic position changes on the resize events

<br/>

---------------------------------
<br/>

#### 4) Usability Checks
- Form submission
    - Whether the information that user types in the input field remains preserved in form field while the submission gets failed
    *Note: These information should be preserved until the user refreshes the page manually*
