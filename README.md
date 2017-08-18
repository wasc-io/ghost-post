[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wasc-io/ghost-post)

# \<ghost-post\>
A simple Element which renders the content of a GhostBlog Post to its shadowDOM.

## A Simple Element to render a Ghost Blog's Post
To use this element on an other domain, then the blogs Domain a CORS Header need to be set on each response of the server. Otherwise the clients browser will refuse to download the content from the remote origin


Sample usage with content from https://www.troyhunt.com:
```html
<ghost-post ghost-url="https://www.troyhunt.com" post-id="59968d3ad718ff0023975261"></ghost-post>
```
(c) 2017 wasc GbR BSD-3-Clause License