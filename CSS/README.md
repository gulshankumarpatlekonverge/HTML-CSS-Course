
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

            <link rel="stylesheet" href="">

            CSS File:
                selector{
                        property:value
                    }

        Each type of CSS overwrite each CSS type property.

        External CSS is overwriten by Internal and Internal is overwriteen by Inline CSS.

    Selectors:
        1. Type selector: h1{}, h2{}, p{} etc. are type selector.

        2. Grouping Selector: h3,h4{} is the grouping selector which apply proprty at both the tags.

        3. id Selector: id="" We can implement the css using the id of that perticular tag. id's of the element should be unique. In the CSS file, we us "#(sharp)" to note the id selector followed by name of selector and property.

            In HTML:
                <h3 id="selector">Hello World</h3>
            In CSS File:
                #selector{
                    property:value
                }

        4. class selector: class="" We can also implement CSS using class selector using the ".(dot)" with the selector name followed by property. Classes we can reuse them however we want but we dont use id selectors they must be unique.

            In HTML: 
                <h3 class="selector">Hello World</h3>
            In CSS File:
                .selector{
                    property:value
                }
                
        5. Universal Selector: *
           Universal Selector *{} is used to apply the property over all the elements. It will use the term specificity.


    div tag: <div></div> 
        with div tag we basically start a new line style. div is a block level element.

    span tag: <span></span>
        with span tag we can use it for inline style. span is a inline element.

        "For grouping something in HTML we use div and span tag. we can use class selector with this tags."


# Links

    MDN Specificity in CSS: 
        https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity
        https://www.w3schools.com/css/css_specificity.asp
# Extension to use with VS code

    Bracket Pair Colorizer
    Indent Rainbow
    High Light Matching Tag