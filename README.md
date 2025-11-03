<!doctype html>
<html lang='en'>
  <head>
    <meta charset='UTF-8'>
    <meta name='viewpoint' content='width=device-width, scale-initial=1.0'>
    <meta property='og:title' content='KHÓA GIẢI ĐỀ ĐGNL EMPIRE'>
    <link rel='canonical' href='#'>
    <title>KHÓA GIẢI ĐỀ ĐGNL EMPIRE</title>
    <link rel='stylesheet' href='styles.css'>
    <script href='script.css' defer></script>
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    </head>
  
  <body>
    <style>
      * {
        margin:0;
        padding:0;
        box-sizing:border-box;
        font-family:'Poppins',Sans-Serif;
      }
      body {
        display:flex;
        cursor : pointer;
        justify-content:center;
        align-items:center;
        min-height:100vh;
        background: url('https://kenh14cdn.com/thumb_w/600/2018/2/11/photo1518350471722-15183504717221775202913.gif') no-repeat;
        background-size:cover;
        background-position:center;
      }
      .div1 {
        border-radius:15px;
        width:420px;
        background:transparent;
        color:#fff;
        padding:10px;
        padding:30px 40px;
        opacity : 1.0;
        border:2px solid rgba(255,255,255,.2);
      }
      .div1 h1 {
        text-align:Center;
        font-size:36px;
      }
      .div1 .input-box {
        position:relative;
        width:100%;
        height:50px;
        margin :30px 0;
      }
      .input-box input{
        width:100%;
        height:100%;
        background:transparent;
        border:none;
        outline:none;
        border : 2px solid rgba(255,255,255,.2);
        border-radius:40px;
        color:white;
        font-size:18px;
        padding:20px 45px 20px 20px;
      }
      .input-box input::placeholder{
        color:#fff;
      }
      .input-box i {
        position:absolute;
        right:10px;
        top:50%;
        transform:translateY(-50%);
        font-size:20px;
      }
      .div1 .remember-forgot {
        display : flex;
        justify-content: space-between;
        font-size:14px;
        margin:-15px 0 15px ;
      }
      .remember-forgot label input {
        accent-color: white;
        margin-right:3px;
      }
      .remember-forgot a {
        color :#fff;
        text-decoration: none;
      }
      .remember-forgot a:hover{
        text-decoration:underline;
      }
      .div1 .btn{
        
        width:100%;
        height:40px;
        background:#fff;
        border : none;
        border-radius:40px;
        outline : none;
        box-shadow:0 0 10px rgba(0,0,0,.9);
        cursor:pointer;
        font-size:16px;
        color :#333;
      }
      .div1 .register {
        font-size:14.5px;
        text-align:center;
        margin-top:10px;
      }
      .div1 .register p a {
        color:#fff;
        font-weight:600;
        text-decoration:none;
      }
      .div1 .register p a {
        text-decoration:underline;
      }
      
      
      
    </style>
    <div class='div1'>
      <form action=''>
        <h1>ĐĂNG NHẬP</h1>
        <div class='input-box'>
          <input type='text' placeholder='Tài khoản' required>
          <i class='bx bxs-user'></i>
        </div>
        <div class='input-box'>
          <input type='password' placeholder='Mật khẩu' required>
          <i class='bx bxs-lock-alt'></i>
        </div>
        <div class='remember-forgot'>
             <label><input type='checkbox'>Quên mật khẩu</label>
             <a href='#'>Quên mật khẩu</a>
        </div>
        <button type='submit' class='btn'>ĐĂNG NHẬP</button>
        <div class='register'>
          <p>CHƯA CÓ TÀI KHOẢN-<a href='#'>Register</a></p>
        </div>
      </form>
    </div>
    
  </body>
</html>
