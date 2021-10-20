<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="./week05/css/w3.css">
    <title>Welcome to Seoyoung's web</title>
    <style>
        body{
            max-width: 950px;
            margin:auto;
        }
        section{
            display: flex;
        }
        article{
            flex: 3;
        }  
        aside{
            flex:1;
        }
        nav{
            flex:1;
        }
        *{font-family:"맑은 고딕",Arial, Helvetica, sans-serif ;}
        header h1{display:inline;}
        ul {list-style:none;}
        a {text-decoration: none;}
        nav ul {
                text-align: center; border-top: 3px solid black;
                border-bottom: 3px solid black ; padding: 15px 10px;

        }
        nav ul li {
                display:inline;
                padding: 15px 20px;
                letter-spacing: 5px;
        }
        nav ul :hover{
                background-color: rgba(255, 192, 19, 0.836);
        }
        nav li a:hover {
                color:white
        }
    </style>
</head>
<body>
    <header>
        <a href="myself2-2.html"><img src="./images/춘식이(수정).jpg" alt="logo" width="100" height="70"></a>
        <h1 style="font-weight:650;">Seoyoung's site</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#profile">Profile</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section class="w3-left w3-container w3-margin-top w3-margin-bottom" style="max-width:700px" >
        <div class="calli01" >
            <div class="w3-row">
                <article class="media" class="w3-row w3-large w3-margin-top"><h3>🖤In Art gallery</h3></article>
                <video controls autoplay loop src="./media/Art gallery.mp4" width="95%" height=95%"></video>
            </div>
            <br>
            <div class="w3-row">
                <article class="music" class="calli w3-margin-top"><h3>🎵My favorite music</h3></article>
                <audio src="./media/water.mp3" controls></audio>
            </div>
            <br>          
        </div>
    </section>

    <aside class="right" class="w3-container w3-cell">
    <div id="login">
        <h4 class="w3-text-black" style="font-weight:650;">Log In</h4>
        <form action="#" >
                          아이디  :<input class="w3-input1" type="text" name="id"/> <br/>
                          패스워드:<input class="w3-input1" type="password" name="pass"/> <br/>
            <input class="w3-button w3-round-xlarge w3-sand" type="submit" value="로그인"/>
            <input class="w3-button w3-round-xlarge w3-sand" type="reset" value="초기화"/><br/><br>
        </form>
    </div>
    <div class="info">
        <div id="link">
               <h5 class="w3-text-black" style="font-weight:900;">즐겨찾기</h5>
                       <ul>
                           <li><a href="http://www.donga.ac.kr" target="_blank">동아대학교</a><br></li>
                           <li><a href="https://www.google.co.kr/" target="_blank">Google</a><br></li>
                           <li><a href="https://www.w3schools.com/"target="_self">w3schools</a></li>
                           <li><a href="https://github.com/" target="_self">github</a></li>
                       </ul>
           </div>
           <div id="post">
              <h5 class="w3-text-black" style="font-weight:900;">최근 게시물</h5>
                       <ul>
                           <li><a href="#">서울여행 1박2일</a></li>
                           <li><a href="#">해운대 밤바다</a></li>
                           <li><a href="#">맛집 탐방</a></li>
                       </ul>
            </div>
       </div>
    </aside>
    
    <div id="profile">
        <article class="package"> 
            <h3 class="w3-large w3-container">💁Seoyoung profile</h3>
            <table border="1">
                <tr>
                    <th>일자</th>
                    <th>내용</th>
                    <th>세부사항</th>
                </tr>
                <tr>
                    <td>현재</td>
                    <td>동아대학교 경영정보학과 재학</td>
                    <td>2학년</td>
                </tr>
                <tr>
                    <td>21.6.18~21.7.25</td>
                    <td>부산광역시 주최 공모전 출전</td>
                    <td>장려상 수상</td>
                </tr>
                <tr>
                    <td>20.5.25~20.7.3</td>
                    <td>어깨동무 활동참여</td>
                    <td>멘티</td>
                </tr>
            </table>
        </article>
    </div>

    <footer  class="w3-dark-grey w3-margin-top"  style="height:150px;">
        <div class="w3-row">
            <div class="w3-col s6 w3-container">
                <h5 id=contact> Contact me</h5>
                <ul>
                  <li>Phone: 010 7302 ****</li>
                  <li>Email: <a href="#">blackeye1108@naver.com</a></li>
                  <li><a href="https://github.com/LSeoyoung">My Github Page</a></li>
                </ul>
                
            </div>
            <div class="w3-col s6  w3-container">
                <h5> Follow me</h5>
                <a href="https://www.instagram.com/_tjyom/"><i class="fa fa-instagram" aria-hidden="true" style="font-size:30px;color:white"></i></a>
                <br /><br/>
                Copyright (c) 2021 💁Seoyoung <br/>
            </div>
        </div>
      </footer>
</body>
</html>



