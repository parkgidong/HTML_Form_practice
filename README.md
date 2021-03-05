# HTML_Form_practice

<!DOCTYPE html>
<html lang="ko">
    <head>
        <meta charset="UTF-8">
        <titile>Form 관련요소 연습</titile>
    </head>
    <body>
        <form action="..." method="POST" >
        <h1>Form 관려요소</h1>
        <fieldset>
            <legend>기본정보</legend>
            <label for="userid">아이디: </label> 
            <input type="text" placeholder="영문으로만 써주세요." id="userid"> <br>
    
            <label for="userpw">비밀번호:</label>
            <input type="password" id="userpw"> <br>
    
            성별: <label for="men">남자:</label>
            <input type="radio" name="sex" checked id="men"> 
            <label for="women">여자: </label>
            <input type="radio" name="sex" id="women"> <br>

        </fieldset>
        <fieldset>
            <legend>부가정보</legend>
            취미: 축구 <input type="chechbox" name="hobby"> 농구 <input type="chechbox" name="hobby">  
            야구 <input type="chechbox" name="hobby"> <br> 
            프로필 사진 업로드 : <input type="file"> <br>
            <input type="button" value="assign"> <br>
            <input type="image" src="" alt="" width="" height=""> 
            사는지역: <select>
                <option>Seoul</option>
                <option>Busan</option>
                <option selected>Bucheon</option>
            </select> <br>
            자기소개: <textarea cols="30" rows="5"></textarea> <br>
            <button type="submit">전송</button> <br>
            <button type="reset">취소</button> <br>
            <input type="submit" value="send"> <br>
            <input type="reset" value="cancel"> <br>
    
        </fieldset>
        </form>
    </body>
</html>
