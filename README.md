<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            font-family: sans-serif;
            background-color: pink;
            padding: 1px;
        }

        .feedback{
            max-width: 500px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
        }

        .feedback h3{
            text-align: center;
        }

        .form-group{
            margin-bottom: 15px;
        }

        label{
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        input[type="text"],
        input[type="email"],
        textarea,
        select{
            width: 99%;
            padding: 10px;
            border-radius: 4px;
            border: 1px solid #ccc;
        }

        button{
            background: darkgreen;
            border: none;
            padding: 12px 20px;
            color: white;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
            justify-content: center;
        }

        button:hover{
            background-color: #218838;
        }
    </style>
</head>
<body>
    <div class="feedback">
        <h3>Feedback Form</h3>
        <form>
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text",id="name" name="name" placeholder="Enter Your Name" required>
            </div>

            <div class="form-group">
                <label for="email">E-Mail</label>
                <input type="email" id="email" name="email" placeholder="Enter Your E-Mail" required>
            </div>

            <div class="form-group">
                <label for="rating">Rating</label>
                <select id="rating" name="rating" required>
                    <option value="">Select Option</option>
                    <option value="5">Excellent</option>
                    <option value="4">Good</option>
                    <option value="3">Average</option>
                    <option value="2">Poor</option>
                    <option value="1">Very Poor</option>
                </select>
            </div>

            <div class="form-group">
                <label for="comments">Comments</label>
                <textarea id="comments" name="comments" rows="3" placeholder="Enter Comments" required>
                </textarea>
            </div>

            <button onclick="func()">Submit</button>
        </form>

        <script>
            function func()
            {
                alert("Your Feedback Submitted Successfully");
            }
        </script>
    </div>
</body>
</html>
