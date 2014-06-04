## How Page Specific Libraries are Requested

Libraries are composed by a Servlet listening for `cq:Page` resources requested using the `pagelib` selector and an extension of `.js` for JavaScript and `.css` for CSS.

The `cl:pageLibrary` tag is provided for easy inclusion of script and link HTML tags appropriate for the current page. 

```
<cl:pageLibrary type="both" />
```
