What CSS TYPES I used and where?

1. Inline CSS:
   - This is done by Writting directly inside the HTML element using the style attribute in the opening tag of the element used.
     It has the most priority among all CSS TYPES . 
     I used Inline CSS in the profile card div by giving it background color 

2. Internal CSS:
   - This is written within a <style> tag inside the <head> section at the start of the HTML file.
     It has second most priority after Inline CSS. 
     I used Internal CSS in the h1 and h2 tags used across the HTML file for giving them color, size and a specific font style.

3. External CSS:
   - This is done by creating a separate file and Writting all the required CSS there.
     It is then linked with the actual HTML by using the <link> tag in the HTML file and specifying the file name in href attribute.
     I used External CSS for styling of links, bio, profile picture, body of the whole webpage and icons of the image I've used.


What CSS Selectors and I used and I where?

1. Element Selectors:
   i. It targets HTML tags directly by specifying the tag directly to select.
   ii. Eg: body, h1, h2, ul, li, a

2. Class Selectors:
   i. It targets the elements using a class which is defined in the HTML tag.
   ii. Eg: .profile-card, .bio
   iii. We use (.)followed by its class name to style an element. Classes are reusable.

3. ID Selectors:
   i. It targets a unique element by ID.
   ii. Eg: #my-img
   iii. We use (.)followed by its class name to style an element. It is used to apply style to a single, specific element.

4. Group Selectors:
   i. Used to target multiple elements at once by separating them with commas.
   ii. Eg: h1, h2
   iii. It is used to apply same style to multiple selectors.

5. Attribute Selectors:
   i. Used to target elements with specific attributes.
   ii. Eg: a[href], a[href]:hover
   
6. Pseudo-class Selectors:
   i. Used to Style elements in a particular state.
   ii. Eg:  a:hover, a[href]:hover

7. Descendant Selectors:
   i. Used to select elements nested within other elements.
   ii. Eg: .icons img

For the shadow effect on the profile card I used the box-shadow property.
For the Hover effects on links I used the pseudo class.
For bringing the links below the image I centered them using the center tag and then create a table and put the images and text inside it 
