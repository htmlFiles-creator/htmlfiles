<html>
    <head>
        <title>Feedback form</title>
        <style>
            body{
                background-color: rgb(211, 166, 166);
                display: flex;
                flex-wrap: wrap;
                justify-content: center;
                margin: 0;
                align-items: center;
                height: 100vh;
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;            
            }
            .feedback{
                background-color: white;
                color: black;
                margin: 8px 0;
                padding: 20px;
                width: 300px;
                border: 1px solid black;
                border-radius: 2px solid black;
            }
            h2{
                color: black;
                text-align: center;
            }
            input,textarea{
                margin: 8px 0;
                padding: 8px;
                width: 100%;
                box-shadow: 1px;
                box-shadow: 1px black;
            }
            button{
                background-color:green;
                color: white;
                cursor: pointer;
                margin:  0;
                padding: 8px;
                width: 100%;
                border: none;
            }
        </style>
    </head>
    <body>
        <div class="feedback">
            <h2>Feedback</h2>
            <input type="Name" placeholder=" Your Name">
            <input type="Email" placeholder="Your Email">
            <input type="Experience" placeholder="Your Experience">
            <textarea rows="4" placeholder="Your Feedback"></textarea>
            <button onclick="myfun()">Submit</button>
            <script>
                function myfun(){
                    alert("Feedback submitted successfully");
                }
            </script>
        </div>
    </body>
</html>    
