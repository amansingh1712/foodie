# foodie
Food Ordering Website
<html>

<head>
    <title>Foodie</title>
    <link rel="icon" href="https://raw.githubusercontent.com/riteshf/files/main/logo.svg" />
    <link href="https://fonts.googleapis.com/css2?family=Material+Icons" rel="stylesheet" />
    <style>
        .body {
            font-family: "proxima-nova", sans-serif;
            margin: 0%;
            font-size: 14px;
        }

        .logo {
            height: 40px;
            width: 40px;
        }

        .location {
            display: flex;
            margin-left: 30px;
            align-items: center;
            cursor: pointer;

        }

        .city {
            color: #3d4152;
            display: flex;
            flex-direction: column;
        }

        .underline_Pune {
            height: 2px;
            left: 0;
            bottom: -5px;
            width: 100%;
            margin-top: 5px;
            background-color: #3d4152;
        }

        .city:hover {
            color: orange;
        }

        .underline_Pune:hover {
            background-color: orange;
        }

        .state {
            margin-left: 7px;
            margin-bottom: 3px;
        }

        .navbar {
            max-height: 80px;
            background-color: white;
            padding: 20px;

        }

        .container {
            position: relative;
            min-width: 1200px;
            max-width: 1200px;
            margin: auto;
            display: flex;
        }

        .navbar-options {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-left: 50px;
            cursor: nw-resize;
        }

        .navbar-option {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-left: 50px;
            cursor: nw-resize;
        }
    </style>
</head>

<body class="body">
    <div class="navbar">
        <div class="container">
            <img src="https://raw.githubusercontent.com/riteshf/files/main/logo.svg" alt="" class="logo">
            <div class="location">
                <div class="city">
                    <b>Pune</b>
                    <div class="underline_Pune"></div>
                </div>
                <div class="state">Maharashtra , India</div>
            </div>
            <div class="navbar-options">
                <div class="navbar-option">
                    <span class="material-icons">shopping_bag</span>
                    Cart
                    <span class="material-icons">person</span>
                    Sign In
                    <div class="material-icons">support</div>
                    Help
                    <div class="material-icons">search</div>
                    Search
                </div>
            </div>
        </div>
    </div>
</body>

</html>
