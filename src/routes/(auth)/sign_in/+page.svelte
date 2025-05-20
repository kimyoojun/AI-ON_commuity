<div id = king>
    <div id= top_bar>
        <h1> 
            <a href="/" id = title_a> AION </a>
        </h1>
    </div>

    <div id =body>
        <div id = login_box >
            <h2 id = login_text> 로그인 </h2>
            <p id = welcome_text>AI:ON 멤버의 커뮤니티에 오신걸 환영합니다.</p>
            <input placeholder="이메일을 입력하시오."class = login_input>
            <input placeholder="비밀번호"class = login_input>
            <button id = button_ep>로그인</button> 
        </div>
    </div>
</div>

<style>
     #login_box {
    width: 417px;   
    height: 487px;
    align-items:center;
    justify-content:center;
    display: flex;
    border: 3px solid beige;
    flex-direction: column;
    border-radius: 40px;
    background-color: bisque;
    }

    #body{
        width:100%;
        height:100%;
        display:flex;
        justify-content: center;
    }

    #king{
        width:100%;
        height:100%;
    }

    #top_bar{
        width:100%;
        height:100px;
    }
    #iogin_text{
        width:100;
        display:flex;
        align-items:center;
        justify-content:center
    }
    #welcome_text{
        display:flex;
        align-items:center;
        justify-content:center;
    }
    .login_input{
        padding: right 16px;
        padding: left 16px;
        padding: top 12px;
        padding:bottom 12px;
        border-radius: 12px;
        width:200px;
        height:40px;
        margin-bottom: 12px;
    }
    #button_ep{
        width:10;
        height: 40px;
        border-radius: 10px;
        border: 3px solid cornsilk;
    }
    #title_a{
        text-decoration-line: none;
        color: limegreen;
        margin: 30px;
    }
</style>
