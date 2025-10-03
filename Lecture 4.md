# Lecture 4

In this Lecture we built a very basic bookmark manager and learnt about some more tags in HTML.

## HTML

- `<h1>` : This tag is used for H1 sized heading.
- `<h2>` : This tag is used for H2 sized heading.
- `<h3>` : This tag is used for H3 sized heading.
- `<h4>` : This tag is used for H4 sized heading.
- `<h5>` : This tag is used for H5 sized heading.
- `<h6>` : This tag is used for H6 sized heading.
- `<p>` : This tag is used to define a paragraph of text within a web document.
- `<a>` : The anchor tag in HTML is used to create hyperlinks, which are fundamental for navigation and connecting resources on the web. Syntax= `<a target = "" href= "https://link"> Open Link </a>`. Some common attributes of this tag are - 
    - href : Specifies the URL of the page the link goes to.
    - target : Specifies where to open the linked document. For Ex- _blank, _parent, _self, _top.
    - download : Specifies that the target will be downloaded when a user clicks on the hyperlink

# Bookmark Manager

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bookmark Manager - CodeWithHarry</title>
</head>
<body>
    <h1>My Bookmarks - CodeWithHarry</h1>
    <h2>Primary Bookmarks</h2>
    <p><a target="_blank" href="https://www.google.com">Open Google</a></p>
    <p><a target="_blank" href="https://www.facebook.com">Open Facebook</a></p>
    <p><a target="_blank" href="https://www.quora.com">Open Quora</a></p>
    <p><a target="_blank" href="https://www.codewithharry.com">Open CodeWithHarry</a></p>
    <p><a target="_blank" href="https://www.youtube.com">Open YouTube</a></p>
    <h2>Secondary Bookmarks</h2>
    <p><a target="_blank" href="https://www.wikipedia.com">Open Wikipedia</a></p>
    <p><a target="_blank" href="https://www.stackoverflow.com">Open Stackoverflow</a></p>
</body>
</html>
```
In this basic project, We segregated the bookmarks into two groups ie- Primary Bookmarks and Secondary Bookmarks. We then linked then inot our html using `<a>` tag 


and That's all for today's lecture thanks for reading.

---
Copyright @Dhairya Minocha 2025
