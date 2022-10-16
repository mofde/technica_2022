# technica_2022
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewpoint" content="width=device-width, initial-scale=1.0">
    <title>Comment Section</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="http://fonts.googleapis.com/css2?family=JArimo&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">
    
    <style>
        html,body {
            height:100%;
            width:100%;
            padding: 0;
            margin: 0;
            font-family: 'Arimo', sans-serif;
        }

        .header {
            padding: 3%;
            font-size: 2cm;
            text-align: center;
            background-color: rbg(250, 250, 250);
            border-bottom: 1px solid #ddd;
        
        }
        .title {
            font-size: 0.8cm;
        }
        .fa-angle-left {
            float: left;
        }
        .fa-paper-plane {
            float: right;
        }
        .body {
            width: 50%;
        }
        .img {
            width: 20%;
        }
        img{
            width: 100%;
        }
        .section > div:nth-child(1){
            padding: 3%;
            display: flex;
        }
        .comment-body {
            padding: 1%;
            font-size: 1.1cm;
        }
        .name {
            font-weight: bold;
        }
        .heart {
            padding-top: 3%;
            width: 20%;
            text-align: center;
        
        }
        .muted {
            padding-top:3%;
            font-size: 0.8cm;
            color: gray;
            
        }
    </style>
</head>
<body>
    <div class="header">
        <i class="fa fa-angle-left"></i>
        <span class="title">Comments</span>
        <i class="fa fa-paper-plane"></i>
    </div>
    <div class ="body">
        <div class="section">
            <div>
                <div class="img">
                    <img src="img1.jpg" alt="">
                </div>

                <div class = "comment-body">
                    <span class="name">joshuji</span>
                    <span>  Love you hun! </span>
                    <br>
                    <div class="muted">
                        <span>3d</span>
                        <b>Reply</b>
                        <b>Like</b>
                    </div>
                </div>

                <div class="heart">
                    <i class="fa fa-heart-o"></i>
                </div>
            </div>
        </div>
        
</body>
</html>
