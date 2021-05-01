# Refactoring Horiseon SEO

Horiseon has asked to refactor the current web page done by a previous developer. One of the main objectives is to make the page accessible following the standards and to achieve a good SEO presence.

## What pages have been changed?

Both the index.html and css files have been manipulated to be  easily updated by anyone in the team.

Web Accessibility Guidelines followed from (Web Content Accessibility Guidelines (WCAG)[https://www.w3.org/WAI/standards-guidelines/wcag/]

The sample below shows concatenation of elements within the page for easier update since they all share the same code.

```
.search-engine-optimization, 
.online-reputation-management, 
.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    background-color: #0072bb;
    color: #ffffff;
}

.search-engine-optimization img,
.online-reputation-management img,
.social-media-marketing img {
    max-height: 200px;
}

.search-engine-optimization h2,
.online-reputation-management h2,
.social-media-marketing h2
 {
    margin-bottom: 20px;
    font-size: 36px;
}
```
## Contact info

For any question or concersn, please contact Javier Vilchis.
