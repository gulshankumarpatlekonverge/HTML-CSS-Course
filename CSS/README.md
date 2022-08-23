
# CSS- Cascading style sheets

    Responsible for styling the web
    HTML- Structure, CSS- Layout, Look
    selector{
        property: value; 
        property:valur
    }

    Types:
        Inline CSS: 
            Inline CSS declarartion happens on the tag which we are using. It is places inside the tag using the style="" keyword.
                <h1 style="color: olive; font-size:3rem">Hello World</h1>

        Internal CSS:
            Internal CSS is written inside the HEAD tag using the <style></style> tag. Internal CSS can be used directly by the selectors within that page.
            
            <style>
                selector{
                    property:value
                }
            </style>

        External CSS:
            With an External CSS you can change the look of an entire website by changing just one file.

            <link rel="stylesheet" href="index.css">

        Each type of CSS overwrite each CSS type property.

        External CSS is overwriten by Internal and Internal is overwriteen by Inline CSS.




# Extension to use with VS code

    Bracket Pair Colorizer
    Indent Rainbow
    High Light Matching Tag