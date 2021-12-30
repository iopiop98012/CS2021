
<!DOCTYPE html> `DOC``TYPE`==>文件類型 

<html>
<head>
    <title>Cafe Unlimited - Home</title>

    <script>
        function bigger(){
            document.getElementById('body').style.fontSize='x-large';   放大字體  
        }
        function smaller(){
            document.getElementById('body').style.fontSize='medium';  縮小字體  
        }
    </script>
    <style>
        h1 {
            font-family: fantasy;  字型  
            color: slategray;   顏色  
        }
        p {
            font-family: sans-serif;  字型  
            color: rgb(0, 0, 128);  顏色  
        }

        li {
            font-family: sans-serif;  字型  
            color: #000080;  顏色  
        }
    </style>

</head>
<body id="body" style="background-image:url(images/background.png)">  網頁橫幅  

<!-- Banner -->
<p>
    <img src="images/banner.png" alt="Cafe Unlimited - Banner">  插入背景   
</p>

<!-- Navigation links -->
<p style="background:slategray;font-weight: bolder;">  連結
    <a href="index.html">Home</a>  資料夾中的連結  
    <a href="breakfast.html">Breakfast</a>  資料夾中的連結  
</p>

<!-- Breakfast photos -->
<p>
    <img src="images/pancakes.jpg" alt="Pancakes">  影像圖片  
    <img src="images/muffin.jpg" alt="Muffin" >  影像圖片  
</p>

<!--Javascript -->
<button type="button" onclick="bigger()">Bigger</button>  字體按鈕  
<button type="button" onclick="smaller()">Smaller</button>  字體按鈕  

<h1>Welcome</h1>  標題  
<p>Welcome to Cafe Unlimited. We serve award-winning breakfasts and lunches,   /*  
    with unlimited coffee, tea, and soft drinks.                                 內容  
    Freshly baked muffins, signature omelets, healthy salads, delicious burgers
    and hearty sandwiches are just some of the delicious items on our menu.    */

    We were voted the
    <span style="color:red;font-style:italic">  紅色字體  
        the #1 Breakfast and Lunch restaurant
    </span>
    downtown!  內容  
</p>
<p>We want to make you  內容  
    <span style="color:red;font-style:italic">feel at home</span>  紅色字體  
    from the minute you walk in the door.  內容  

    Be part of the Cafe Unlimited family! Have a great meal, relax, socialize, and come back again soon!</p>  內容  
<p>We offer delivery on <a href="http://ubereats.com" target="_blank">UberEats</a>. Download the app and place your order today. Please contact us about catering services.</p>  內容 

<p>We are located at 20 Channel Center Street in Boston, MA.</p>  內容  
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2948.8366673124624!2d-71.05369318489703!3d42.346005543982265!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89e37a7de82a1251%3A0xb79b53cf96e26c94!2s20+Channel+Center+St%2C+Boston%2C+MA+02210!5e0!3m2!1sen!2sus!4v1543445329233" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
<p>   地圖連結 
  We are open:</p>   內容  
<ul>
    <li>Saturday and Sunday, 7 am to 2 pm</li>  內容
    <li>Monday through Friday, 6 am to 2 pm</li>  內容  
</ul>
<p>Visit our contact page for directions and contact information.</p>
<h1>Find Us, Follow Us</h1>  標題  
<p>Follow us on <a href="http://facebook.com" target="_blank">Facebook</a> and  連結  
    <a href="http://twitter.com" target="_blank">Twitter</a>.  連結  
    Check out our reviews on <a href="http://yelp.com" target="_blank">Yelp.</a>  內容  
</p>
<p>Find us in Channel Center.</p>  內容
<p>Cafe Unlimited<br>  內容
617-555-1234<br>  內容
    cafeunlimited@example.com</p>  內容
</body>
</html>
```
