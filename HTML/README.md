# Basic HTML Page Structure

<!DOCTYPE html>            <!-- HTML Version -->
<html lang="en">            <!-- Root Element -->
<head>                      <!-- Inforamation about the page(Meta, Link, Title) -->
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title> <!-- Page Title -->
</head>
<body>                      <!-- What will be displayed on the page -->   
    <h2> HTML ignores all the whitspaces within tag or outside the tags. HTML is white Space Collapsing.</h2> 
</body>
</html>

# Element in HTML

    Heading:
        Heading are from <h1></h1> to <h6></h6> tags and the size of the text decreases from H1 to H6.
    
    Paragraph:
        It is represented using <p></p> tag.

    Image:
        To show or import the image in HTML Page <img> tag is used. Use "/", "./", "../" in src property to get the path of file from folder structure or directory. you can also add online image as well. This tag come up wit Height and Width of image to adjust it.

    Break Element:
        <br/> tag is used to break the elements into the rows or the spaces in between on html page.

    Navigation Link:
        Extenal Link:
        <a href="" target=""></a> tag is used to open the link when user clicks on link. target="" is used to trigger to open the page in same tab or new tab. This link navigate us to the new website or page. 
    
        Internal Link:
        This type of links are only work within our websites no navigate from one page to another example from Home Page to About us or Contact Us page. This type of links are enclosed in the <nav></nav> bar tags. for Empty links you can put "#" to active the link. You can also use <a></a> anchor tag with images and texts to navigate through.

    Sup and Sub Element:  
        <sup></sup> place the content of the tag onto the top of the text and <sub></sub> place the content of the tag bottom of the text. 

    Strong And Em Element:
        <strong></strong> tag is used to "Bold" the text and <em></em> is used to "Italic" the text. You can also achive this using the css to put all you changes to one place. 

    Special Characters:
        You can provide special characters in your code using & and the type of character you want to add followed by semi-colon(;).

    UnOrdered List and Orderd List Element:
       UnOrdered List: 
        <ul>
            <li></li>
            <li></li>
        </ul> tag is used to represent it. 

       Ordered List: 
        <ol>
            <li></li>
            <li></li>
        </ol>
        tag is used to represent it. 

        We can also place navigation links inside the unordered list. We can place <a></a> tag to navigate throuugh tag.

        Nested List:
            It consist of combination of Ordered and unordered list.
               <ul>
                    <li></li>
                    <li>
                        <ol>
                            <li></li>
                            <li></li>
                            <li></li>
                        </ol>
                    </li> 
                    <li>
                        <ul>
                            <li></li>
                            <li></li>
                            <li></li>
                        </ul>
                    </li>
                </ul>

    Table Element:
        Table Element is used to show the HTML content into the tabular form to make data sustanable.
                <table>
                    <tr>
                        <th></th> 
                        <th></th>
                        <th></th>
                    </tr>
                    <tr>            
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                    <tr>
                        <td></td>
                        <td></td>
                        <td></td>
                    </tr>
                </table>
    
    Form Element:
        Form is used to process the data from the user and make it useful to future reference as entry. 
            <form action="" methods="">

            </form>

        Types of Element in Form:
            <label for="">Name</labele>
            <input type ="text" name="" id="" value="" placeholder="">
            <button type="submit">Submit</button>

        You can get all the inputs using following syntax enter input: and all the elements will open.
# Useful resource links

    Youtube: https://www.youtube.com/watch?v=mU6anWqZJcc
    Emmet: https://emmet.io/

# Extensions for VS Code