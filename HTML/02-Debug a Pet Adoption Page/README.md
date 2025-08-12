# 02-Debug a Pet Adoption Page

Sally, a pet adoption store owner, has built her first web page but there are some issues.

Your job is to fix all of the errors so Sally can continue building her page.

Fulfill the user stories below and get all the tests to pass to complete the lab.

## Live Demo
[View Completed Lab](https://jjotteson1.github.io/FreeCodeCamp-labs/HTML/02-Debug%20a%20Pet%20Adoption%20Page/index.html)

## User Stories
1. Sally wants to use an image of some cats but it is not displaying correctly. You will need to fix the following in the `img` element:  
   - Replace the `href` attribute with the correct attribute for the image source.  
   - Replace the `att` attribute with the correct attribute representing short, descriptive text for images.  
   - Remove the `</img>` closing tag because `img` elements are void elements and don't have closing tags.
2. Sally wants to use some links to direct users to the dog and cat pages. But the links are not working correctly. You will need to fix the following in the `a` elements:  
   - Replace both `src` attributes with the correct attributes used to specify URLs.

## Tests
1. Your `img` element should have a `src` attribute instead of the `href` attribute.
2. Your `img` element should have an `alt` attribute instead of the non-existent `att` attribute.
3. Your `img` element should not have a `</img>` closing tag.
4. Your `a` element with the text `Visit cats page` needs to have an `href` attribute instead of a `src` attribute.
5. Your `a` element with the text `Visit dogs page` needs to have an `href` attribute instead of a `src` attribute.
