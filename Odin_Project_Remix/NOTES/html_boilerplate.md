# HTML BOILERPLATE
- This will exlpain things in the html boilerplate code.
    ## Doctype
    - The beginning of the HTML code.
    - Tells the browsser what version of HTML should be used to render the document.
    - Older version has a complicated implementaion of it so I am going to skip this.
    ```html
    <!DOCTYPE html>
    ```

    ## THe \<html> element
    - Known as the root element of the document.
    ```html
    <!DOCTYPE html>
    <html lang="en">
        <!-- All other stuffs here -->
    </html>
    ```
    - Here the Language Attribute is used which serves to make the accessibility of hte webpage better for screen readers.
    - The language and their abbreviations follow iso standard as [Language Abbreviations](https://www.w3docs.com/learn-html/html-language-codes.html)

    ## The \<head> element
    - An element where important meta-information about the webpage is kept.
    - It also keeps the required stuffs for the webpage to render correctly.
    - It is a rule to not include any elements in the head which displays content on the webpage.
    - Some Elements within the \<head> element
        ### The Charset Meta Element
        - Always uses the meta tag and is used to inform of the character set encoding used.
        - In almost all cases, we use "utf-8".
        ```html
        <!DOCTYPE html>
        <html lang="en">
            <head>
                <meta charset="utf-8">
            </head>
        </html>
        ```
        ### The \<title> element
        - Gives a human readable title to the tab of the browser.
        - If not given defauls to the name of the file: "index.html"
        ```html
        <!DOCTYPE html>
        <html lang="en">
            <head>
                <meta charset="utf-8">
                <title> Test Webpage </title>
            </head>
        </html>
        ```
    ## The \<body> element
    - This is where all the content to be displayed is kept.
    - These could include: text, images, list, links etc.
    ```html
    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title> Test Webpage <title>
        </head>
        <body>
            Test Website
            <!--Displayable elements-->
        </body>
    </html>
    ```
    ## 

