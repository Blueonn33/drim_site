#<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="siteCSS.css">
    </head>
    <body>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
        <script src="siteJS.js"></script>

        <div class="head">
            <img src="D:\Сайт\лого-сайт.png" id="logo" alt="Logo" width="160" height="120">
            <h1></h1>
            <!-- <img src="D:\Сайт\лого.png" id="logo2" alt="Logo" width="110" height="102"> -->
        </div>
        <h1 id="header">ДРИМ</h1>
        <title>ДРИМ - гердани</title>
        <div class="body">
            <div class="prod">
                
                <img src="D:\Сайт\лого.png" class="products" id="pro1" alt="Product">
                <!-- <button type="button" class="info" id="ibutton1">Информация</button> -->
                
                <button type="button" id="sbutton1" class="sbutton">Увеличи</button>
                <button type="button" id="hbutton1">Намали</button>
                
                <p class="price">25.49 лв.</p>
                <div class="prod1">
                    <img src="D:\Сайт\лого.png" class="products" style="margin-right:-15px" id="pro2" alt="Product">
                    <button type="button" id="sbutton2" class="sbutton">Увеличи</button>
                    <button type="button" id="hbutton2" class="hbutton">Намали</button>
                    <!-- <button type="button" class="info" id="ibutton2" style="margin-left: 8.1%; margin-right: 400px;">Информация</button> -->
                    <p class="price" style="margin-left: 57.1%;">15.99 лв.</p>
                </div>
                <div id="info1">
                    <p> Много добър продукт, ръчна изработка</p>
                    <button type="button" id="hideInfo1">Скрий</button>
                </div>
                <div class="prod2">
                    <img src="D:\Сайт\лого.png" class="products" id="pro3" alt="Product">
                    <button type="button" id="sbutton3" class="sbutton">Увеличи</button>
                    <button type="button" class="hbutton" id="hbutton3">Намали</button>
                    <!-- <button type="button" class="info" id="ibutton3" style="margin-left: 94%;">Информация</button> -->
                    <p class="price" style="margin-left: 94%;">19.29 лв.</p>
                </div>
                <!-- <div id="info1">
                    <p> Много добър продукт, ръчна изработка</p>
                    <button type="button" id="hideInfo1">Скрий</button>
                </div> -->
                <div class="prod3">
                    <img src="D:\Сайт\лого.png" class="products" id="pro4" alt="Product">
                    <button type="button" id="sbutton4" class="sbutton">Увеличи</button>
                    <button type="button" id="hbutton4" class="hbutton">Намали</button>
                    <!-- <button type="button" class="info" id="ibutton4">Информация</button> -->
                    <p class="price">25.49 лв.</p>
                <div>
                    <div class="prod4">
                        <img src="D:\Сайт\лого.png" class="products" id="pro5" alt="Product">
                        <button type="button" id="sbutton5" style="margin-left: -9%" class="sbutton">Увеличи</button>
                        <button type="button" id="hbutton5" class="hbutton">Намали</button>
                        <p class="price" style="margin-left: 57.1%">15.99 лв.</p>
                    </div>
                    <div class="prod5">
                        <img src="D:\Сайт\лого.png" class="products" id="pro6" alt="Product">
                        <button type="button" id="sbutton6" class="sbutton">Увеличи</button>
                        <button type="button" class="hbutton" id="hbutton6">Намали</button>
                        <p class="price" style="margin-left: 94%;">19.29 лв.</p>
                    </div>
                    <!-- <input type="radio" id="fpage" name="page" class="radio">
                    <input type="radio" id="spage" name="page" class="radio"> -->


                    
                        

                    <label class="container">
                        <input type="radio" checked="checked" name="radio" id="fradio" onclick="firstPage()">
                        <span class="checkmark"></span>
                      </label>
                      <label class="container">
                        <input type="radio" name="radio" id="sradio" onclick="secondPage()">
                        <span class="checkmark"></span>
                      </label>
                    <img src="D:\Сайт\вертикални_линии_сиво" class="stripe" alt="Stripe">
                </div>
            </div>
            
    
           
        </div>
        
        <div ></div><br><br>
        <div></div>
        <div class="footer">
            <p id="butik"><b>Дантелени фантазии - бутик за ръчно художествено плетиво и бродерии</b></p>
            <p>Телефон: 0008988989</p>

            <div id="gmail_div">
                <img src="D:\Сайт\gmail-logo-grey" class="logos" id="gmail" alt="Gmail_logo">
                <p class="texts">m.boneva494@gmail.com</p>
            </div>

            <div id="facebook_div">
                <img src="D:\Сайт\facebook_logo" class="logos" id="facebook" alt="Facebook_logo">
                <p class="texts">Margarita Boneva</p>
            </div>
            
            <div id="instagram_div">
                <img src="D:\Сайт\instagram-logo-grey" class="logos" id="instagram" alt="Instagram_logo">
                <p class="texts">margarita.boneva.925</p>
            </div><br>

          </div>
    </body>
</html>
