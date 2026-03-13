<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>login page</title>
    <style>
           * {
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            margin: 0;
            height: 100vh;
            display: grid;
            place-items: center;
            background: url('content://com.android.externalstorage.documents/tree/primary%3Apics/document/primary%3Apics%2Fuuu%2Fpurple-aesthetic-laptop-p54rq9vjttngul66.jpg') no-repeat center center/cover;
            /* Placeholder background color if image is missing */
            background-color: #4b2c91; 
        }

        .box {
            width: 400px;
            padding: 40px;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(4px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 20px;
            color: white;
            text-align: center;
            transition:1s;
        }
        .box:hover{
            box-shadow:0 5px 15px #f880ff;
        }

        h2 {
            margin-bottom: 30px;
            font-size: 2rem;
        }
        

        .input-group {
            position: relative;
            margin-bottom: 20px;
        }

        .my-input-class {
            width: 100%;
            padding: 12px 20px;
            background: transparent;
            border: 1px solid rgba(255, 255, 255, 0.5);
            border-radius: 30px;
            color: white;
            outline: none;
            transition:1s;
        }

        .my-input-class::placeholder {
            color: rgba(255, 255, 255, 0.8);
        }

        .options {
            display: flex;
            justify-content: space-between;
            font-size: 0.8rem;
            margin-bottom: 25px;
        }

        .options a {
            color: white;
            text-decoration: none;
        }

        .login-btn {
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 30px;
            background: white;
            color: black;
            font-weight: bold;
            cursor: pointer;
            margin-bottom: 20px;
            transition:1s;
            }
    .login-btn:hover{
            box-shadow:0 5px 15px #f880ff;
        }

        .register-link {
            font-size: 0.9rem;
        }

        .register-link a {
            color: white;
            font-weight: bold;
            text-decoration: none;
        }
       .my-input-class:hover{
           box-shadow:0 6px 15px #f880ff;
       }
      
    </style>
</head>

<body>
    <section class="box">
        <h2>Login</h2>
        <form>
            <div class="input-group">
                <input type="text" class="my-input-class" placeholder="Username">
            </div>
            <div class="input-group">
                <input type="password" class="my-input-class" placeholder="Password">
            </div>
            
            <div class="options">
                <label><input type="checkbox"> Remember me</label>
                <a href="">Forgot Password?</a>
            </div>
            <a href="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/yuev.html">
            <button class="login-btn">Login</button>
            </a>
            <div class="register-link">
                Don't have an account? <a href="#">Register</a>
            </div>
        </form>
    </section>




</body>
</html>
