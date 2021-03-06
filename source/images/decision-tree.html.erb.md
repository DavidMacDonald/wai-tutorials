---
title: A simple alt decision tree
nav_title: <code>alt</code> Decision Tree
status: draft
order: 9
type: tips
---

-   Is this image the only content of a link or form control?
    -   **Yes**: Use the `alt` attribute to communicate the destination of the link or action taken. See [Functional Images](functional.html).
    -   **No**: Continue.
-   Does this image contain text?
    -   **Yes**:
        -   If the text in the image is also present as *real* text nearby, use an empty `alt` attribute.
        -   Otherwise, use the `alt` attribute to include the communicative text of the image (not text included for visual effect). See [Images of Text](textual.html#image-of-styled-text-with-decorative-effect).
    -   **No**: Continue.
-   Does the image contribute meaning to the current page or context?
    -   **Yes**, and it’s a simple graphic or photograph. The `alt` attribute should briefly describe the image in a way that conveys that meaning. See [Informative Images](informative.html).
    -   **Yes**, and it’s a graph or complex piece of information. Include the information contained in the image elsewhere on the page. See [Complex Images](complex.html).
    -   **No**: Continue.
-   Is the image purely decorative or not intended for the user?
    -   Use an empty `alt` attribute. See [Decorative Images](decorative.html)
-   Is the image’s use not listed above or it’s unclear what `alt` text to provide?
    -   This decision tree **does not** cover all cases. For detailed information on the provision of text alternatives refer to the [Image Concepts Page](index.html).
