# Using Relative Links in Markdown Files on GitHub

### Introduction

Markdown is a widely used text formatting language for creating readable and informative content. It's a popular choice for writing documentation, wikis, and even blog posts. One of the key features of Markdown is its **ability to link to other files** and **web pages.**

When you're working on a project hosted on [GitHub](https://github.com/), you can leverage relative links in your Markdown files to link to other files within the **same repository**. This makes it easier for users to navigate your project's documentation, regardless of whether they're viewing it on GitHub or *locally* on their machine.

### What are relative links?
A URL or relative link **only includes the path after your domain**. It transmits the address that is relative to your current location rather than providing the full address of your site.

## Benefits of Using Relative Links

There are several advantages to using relative links in your Markdown files on GitHub:

-   **Improved Readability:** Relative links make your code and documentation easier to follow. Users can quickly jump to related content within your project.
-   **Maintains Organization:** Since relative links point to files within the same repository, they won't break if you move the repository to a different location.
-   **Flexibility:** Relative links work seamlessly when users clone your repository and view the Markdown files locally.

## Using Relative Links in Your Markdown Files

Here's how to create relative links in your Markdown files on GitHub:

1.  **Link Text:** Start by writing the text you want users to click on. This will be the displayed text for your link.
    
2.  **Square Brackets:** Enclose the link text in square brackets `[]`.
    
3.  **Link URL:** Following the link text in square brackets, add the file path to the file you want to link to.


**Syntax for creating a relative link in Markdown:**

```
[Link Text](link path to the file.md)
```
Here are some examples of how to use relative links in your Markdown files:

-   Link to a file in the same directory:
    ```
    [Link Text](filename.md).
    ```
    **Example:**  
    Click here for an [Example](example.md).  

-   Link to a file in a subdirectory:
    ```
    [Link Text](subdir/filename.md)
    ```
    **Example:**  
    This [link](Images/example2.md) is linked to a file in the subdirectory.  

-   Link back to the current file (usually used in the table of contents):
    ```
    [Link Text](filename.md)
    ```
    **Example:**  
    [Using Relative Links in Markdown Files on GitHub](demo.md)  

    **Note:** Linking back to the current file (like in the original TOC example) isn't a common practice. Most users wouldn't expect to click a link to reach the same page they're already on.
    <br>

- Link to an image file in a subdirectory:
    ```
    [Link Text](path/to/image.jpg)
    ```
    **Example:**  
    This [link](Images/Flower1.jpg) is linked to a Image file in the subdirectory.  
  
    **Note:** When linking to a file in a subdirectory, you'll need to use the directory name followed by a forward slash (`/`) before the filename.  

### Conclusion

Relative links are a powerful way to **link between Markdown files** *within* your GitHub repository. They improve the readability and maintainability of your project's documentation. By following the simple steps outlined above, you can create effective relative links in your Markdown files and enhance the overall user experience for anyone exploring your project. 
