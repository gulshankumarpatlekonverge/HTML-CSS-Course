
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

# Color and BackGround Color
    1. RGB(RED, GREEM, BLUE): rgb(100, 200, 56)

    2. RGBA(0, 0, 0, 1) : rgba(red, green, blue, alpha) 0-1  optacity/transparacy

    3. HSL HEX Values: #RRGGBB
        Number Codes:
            1 2 3 4 5 6 7 8 9 A(10) B(11) C(12) D(13) E(14) F(14)

# Units in CSS
    absolute:
        1. pixels 
            pixels is a absolute unit of mesurement and one pixel represent one dot on a screen.

    relative:
        1. percent(%)
        2. em, rem
        3. vw,vh

    calc function:
        calc() perform math operation +, -, *, / mix and match value
            min-height: calc(100vh - 100px);

# Typography
    1. font stack, generic family 
        Provided by VS code
    2. google fonts
        You can find this on the internet by googleing it.

# Box Modeling

    1. padding: 
        Padding is used to create space around an element's content, inside of any defined borders.
            padding-top: 30px; 
                - from top
            padding-bottom: 60px; 
                - from bottom
            padding-left: 25px; 
                - from left
            padding-right: 50px; 
                - from right
            padding: 50px; 
                - from all around
            padding: 30px 60px; 
                - from 60px -  left & right 30px top & bottom 
            padding: 20px 30px 40px 50px; 
                -from 20px- top, 30px right 40px- bottom, 50px- left

    2. border:
        The CSS border properties allow you to specify the style, width, and color of an element's border.
            border-top: 30px; 
                - from top
            border-bottom: 60px; 
                - from bottom
            border-left: 25px; 
                - from left
            border-right: 50px; 
                - from right
            border: 50px; 
                - from all around
            border: 30px 60px; 
                - from 60px -  left & right 30px top & bottom 
            border: 20px 30px 40px 50px; 
                -from 20px- top, 30px right 40px- bottom, 50px- left
            border: solid 20px red;
                - soli style width 20px color red 
            border-style: dashed;
            border-width: 20px;
            border-color: red;
        Border Radius:
            border-radius: 4px;
            and many more

    3. margin:
        The CSS margin properties are used to create space around elements, outside of any defined borders. 
            margin-top: 30px; 
                - from top
            margin-bottom: 60px; 
                - from bottom
            margin-left: 25px; 
                - from left
            margin-right: 50px; 
                - from right
            margin: 50px; 
                - from all around
            margin: 30px 60px; 
                - from 60px -  left & right 30px top & bottom 
            margin: 20px 30px 40px 50px; 
                -from 20px- top, 30px right 40px- bottom, 50px- left
        Negative Margin:
            margin-top: -30px;

    4. Outline:
        An outline is a line that is drawn around elements, OUTSIDE the borders, to make the element "stand out"
            outline-width: 0.2rem;
            outline-style: solid;
            outline-color: #222;

            outline: 0.2rem solid #222;
                0.2rem width solid style #222 color
            outline-offset: 10px;  
                away from the padding of the content
            outline-offset: - 10px; 
                inside the padding of the content


# Display Properties

    Block: Alwys starts a new line and take full width.
         display: block;

    Inline: Does not start and only take up as much as cotent space.
         display: inline;

# Background Properties
    All the properties with the background keyword applied to the background of the page or content.
        background-color: red;
        background:url(image.jpg)
        background-repeat: 
        background-size:
        background-position:
        background-attachment:

# CSS Gradient
    background: linear-gradient();
# Links

    MDN Specificity in CSS: 
        https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity
        https://www.w3schools.com/css/css_specificity.asp

    Color Pallet(COOLERS): https://coolors.co/

    Google Fonts: https://fonts.google.com/

    CSS Gradient: https://www.colorzilla.com/gradient-editor/
# Extension to use with VS code

    Bracket Pair Colorizer
    Indent Rainbow
    High Light Matching Tag