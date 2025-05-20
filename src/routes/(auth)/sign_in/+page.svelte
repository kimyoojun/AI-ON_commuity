<div id="main_box">
    <div id="top_bar">
        <h1 id="title_text">
            <a href="/" id="title_A">AI:ON</a>
        </h1>
    </div>
    <div id="body">
        <div id="login_box">
            <h2 id="login_text">로그인</h2>
            <p id="hi_text">개발자를 꿈꾸는 AI:ON의 커뮤니티에 오신것을 환영합니다.</p>
            <input placeholder="이메일 주소" class="login_input">
            <input placeholder="비밀번호" class="login_input">
            <button id="login_button">로그인</button>
        </div>
    </div>
</div>

<style>
    #main_box {
        width: 100%;
        height: 100%;
    }

    #top_bar {
        width: 100%;
        height: 100px;
    }

    #title_text {
        margin-left: 15px;
    }

    #title_A {
        text-decoration-line: none;
        color: black
    }

    #body {
        width: 100%;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    #login_box {
        width: 460px;
        height: 737px;
        border: 3px solid gray;
        border-radius: 10px;
        display: flex;
        /* 세로기준으로 가운데 정렬 */
        align-items: center;
        /* 가로기준 가운데 정렬 */
        justify-content: center;
        /* column으로 세로로 정렬 */
        flex-direction: column;
    }

    #login_text {
        width: 100%;
        display: flex;
        /* 가로 기준으로 가운데 정렬 */
        justify-content: center;
        color: black;
    }

    #hi_text {
        width: 100%;
        text-align: center;
        color: black;
    }

    .login_input {
        width: 300px;
        height: 20px;
        padding: 16px 12px;
        border: 2px solid gray;
        border-radius: 10px;
        margin: 5px 0;
    }

    #login_button {
        width: 325px;
        height: 40px;
        padding: 16px 12px;
        border: 1.5px solid gray;
        border-radius: 10px;
        margin: 10px 0;
        display: flex;
        align-items: center;
        justify-content: center;
    }
</style>