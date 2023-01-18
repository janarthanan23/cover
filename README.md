# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the github repository and create a django admin interface.
### Step 2:
write HTML and CSS code for Desiging book cover page and execute them.

## Code:
```
cover.html

<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:hsl(24, 78%, 52%);
            margin-left: auto;
            margin-right: auto;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/back.png);
            background-size: cover;
        }
            

        .insight{
            color: yellow;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: blue;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Garamond', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: rgb(255, 80, 80);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1><b>Fundamentals of Web Application Development</b></h1></div>
            <div class="subtitle">
                HTML and CSS Combined with Django Architecture
            </div>
            <div class="mypic">
                <img src="/static/images/my.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(44, 15, 97);">
            </div>
            <div class="author">
               <p><b>Janarthanan S</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>
```

## Output:
![OUTPUT](./cover.png)

## HTML validator:
![OUTPUT](./valid.png)

## Result:
The Program for designing book cover page using HTML and CSS is Executed Successfully.
