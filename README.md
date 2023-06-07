# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

## step 1:
Create a new django project

## Step 2:
Create a new django app

## Step 3:
Create Static and its sub directories(Images,html)

## Step 4:
Write the html code in the html folder and images in the images folder

## Step 5:
Start the django-server
## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title> Wings of Fire</title>
        <style>
        h1{
           color:turquoise;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             background-color: black;
             background-position: center;
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url('/static/images/wingg.png');
             background-size: cover;
             background-repeat: no-repeat;

         }
         .toptext{
             color:yellow;
             padding-left: 10px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;

         }
         .tophr{
             color:#e36f2f;
              width: 180px;
         }
         hr{
             color:#e36f2f;

         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
            align-items: center;
            justify-content: center;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 20px;
         }
         .author{
             color:tomato;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             position:relative;
             line-height: 20px;


         }
         .sub-text {
             color:blue;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }

.footer {
  color:orange;
  padding-top: 180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
  margin-right: 20px;
}
.bottomhr {
    color:#e36f2f;
              width: 400px;

}
img {
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align: bottom;
}
.edition {
    color:#e36f2f;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
 line-height:bottom;

}


        </style>
        </head>
            <body>
                <div class="bookpage">

                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EXPERT INSIGHT</div>
                    <div class="tophr"><hr></div>
               <div class="booktitle"><h1>Wings of Fire</h1></div>
               <h3 class="sub-text">The autobiography of Dr. APJ Abdul Kalam</h3>
                    <h3 class="sub-text">written by Dr. APJ Abdul Kalam</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;First
Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="/static/image/ajp.png" alt="Author"></h2>

                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;Dr. APJ Abdul Kalam &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>

                </div>
                </div>

            </body>


</html>
```

## Output:
## server output
![WhatsApp Image 2023-06-07 at 9 02 34 PM](https://github.com/bharathraj1905/cover-page-design/assets/121490575/ba9fc23e-1897-4eb6-a0be-299ca6224181)


## client output
![WhatsApp Image 2023-06-07 at 9 11 29 PM](https://github.com/bharathraj1905/cover-page-design/assets/121490575/9bb8809a-39aa-4975-a78c-981092b0cf47)


## Result:
Thus the code has been executed successfully.
