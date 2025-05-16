<div id="top_bar">
    <h1 id="title">원숭이</h1>
    <form action="." method="post">
        <input id="search-txt" type="text" placeholder="알고 싶은 원숭이를 검색해주세요">
        <button id="search-btn" type="submit">검색</button>
    </form>
    <div id="sign">
        <input class="sign_id" placeholder="아이디를 입력해주세요" type="text">
        <input class="sign_password" placeholder="비밀번호를 입력해주세요" type="password">
        <button class="login">login</button>
    </div>
</div>

<style>
    #top_bar{
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    #title {
        width: 90px;
        height: 35px;
        font-size: 25px;
        margin: 0px;
        margin-top: 5px;
    }

    #search-txt {
        width: 220px;
        border: solid;
        border-width: 0.1px;
        border-radius: 8px;
        padding: 8px;
        display: false;
    }

    #sign {
        display: flex;
        flex-direction: column;
    }
</style>