<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name ="viewport" context ="width=device-width,initial-scale=1.0">
        <title>document</title>
        <style>
            body,html{
                margin: 0;
                padding: 0;
                heigth: 100%;

            }
            .container{
                background-color: blueviolet;
                display: flex;
                align-items: center;
                justify-content: center;
                height: 100%;
                flex-direction: column;
            }
            .input {
                background-color:white;
                padding: 50px 100px;
                text-align: center;
                border-radius: 20px;

            }






        
            
            p{
                fontsize: 200%;
            }
            input{
                height: 50px;
                width: 250px;
                border-radius: 200px;
            }
            button{
                background-color: blue;
                height: 50px;
            }
                
            
        </style>
    </head>
    <body>
        <div class = " container">
            <div class = " input">
            <p>Qr code generate </p>
            <input type="text" id = "inputtext " placeholder = "en">
                <button oneclick = "generate ()">Generate qr</button>
        </div>
        <div class="qr">
            <ing src="" id = " imgpr "></ing><br><br>
                </div>
                </div>
        </div>
        <script>
            //string concentation 
            let inputtext=document.getelementry.id("inputtext"); 
            let inputtext=document.getelementry.id("imgqr");
            function generate (){
                imgqr .src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=" + indextext.value;
            }

            
        </script>
    </body>
</html>
