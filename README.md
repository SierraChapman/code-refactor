# A Code Refactor

This project is a refactoring of existing code (originally written by Trilogy Education Services, a 2U, Inc.) to make it meet accessibility standards. The accessibility standards include using semantic HTML tags, including alt attributes for images, and appropriately used headings. Additional changes were made including fixing bugs, consolidating or removing repeated or redundant code, and reorganizing the CSS file.

## Examples of Changes

The original HTML code shown below uses `<div>` tags where semantic HTML elements would be appropriate, includes redundant classes and id's, and is missing an id that is referenced by a link.

![HTML before](/screenshots/HTML-before.png)

The refactored HTML replaces `<div>` tags with the more informative `<content>` and `<section>` tags and does 
not include the `"search-engine-optimization"`, `"online-reputation-management"`, and `"social-media-marketing"` classes that are redundant with the similarly named id's.

![HTML after](/screenshots/HTML-after.png)

The addition of `id="search-engine-optimization"` fixes the link in the navbar that referenced `#search-engine-optimization`.
The working link is shown below.

![Working link](/screenshots/working-link.gif)

The following screenshot shows some of the original CSS associated with the HTML that was shown above. Each section is styled separately, leading to repeated code.

![CSS before](/screenshots/CSS-before.png)

The refactored code shown below produces the same result in much fewer lines.

![CSS after](/screenshots/CSS-after.png)

See the deployed link section for the live site.

## Built with

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Deployed Link

* [See Live Site](https://sierrachapman.github.io/code-refactor/)

## Authors

* **Sierra Chapman** 
    - [Portfolio Site](#)
    - [Github](https://github.com/SierraChapman)
    - [LinkedIn](https://www.linkedin.com/in/sierra-chapman)

## Acknowledgments

* The original web application was created by Trilogy Education Services, a 2U, Inc.
* [W3 Schools](https://www.w3schools.com/) was a useful resource in completed this project.