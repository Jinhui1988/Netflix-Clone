---
 # 用Html和Css克隆Netflix首页



## 前言：

​       自己试着用html和css搭建netflix的首页，结果如下，这个文章主要是记录下写下来的代码，原教程是youtube上一个印度人的教学，跟着做的，本人不懂前端知识，但是一通代码写下来还是有所收货的，真是好记性不如赖笔头，简单说就是写代码，在浏览器看效果，就这样，编辑器用的是VS Code！我把html和css的文件代码都放这来，看着也方便些！



## HTML代码：



```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div class="nav" id="nav">
        <img src="images/netflix-logo.png" alt="" class="nav_logo">
        <img src="images/netflix-avatar.png" alt="" class="nav_avater">

    </div>

    <!-- header -->
    <div class="banner">
        <div class="banner_contents">
            <h1 Class="banner_title">纸房子</h1>
            <div class="banner_buttons">
                <button class="banner_button">播放</button>
                <button class="banner_button">我的列表</button>
            </div>
            <div class="banner_description">
                　八名窃贼将自己与人质反锁在西班牙皇家造币厂内，他们背后的犯罪首脑则妄图操纵警察实现自己的计划...
            </div>
        </div>
        <div class="banner--fadeBottom"></div>
    </div>

    <!-- Netflix Originals -->
    <div class="row">
        <h2>NETFLIX ORIGINALS</h2>
        <div class="row_posters">
            <img src="images/large-movie1.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie2.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie3.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie4.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie5.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie6.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie7.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie8.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie1.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie2.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie3.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie4.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie5.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie6.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie7.jpg" alt="" class="row_poster row_posterLarge">
            <img src="images/large-movie8.jpg" alt="" class="row_poster row_posterLarge">
        </div>
    </div>


    <!-- Trending Now -->
    <div class="row">
        <h2>Trending Now</h2>
        <div class="row_posters">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
        </div>
    </div>


    <!-- Top Rated -->
    <div class="row">
        <h2>Top Rated</h2>
        <div class="row_posters">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
        </div>
    </div>

    <!-- Action Movies -->
    <div class="row">
        <h2>Action Movies</h2>
        <div class="row_posters">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
        </div>
    </div>

    <!-- Comedy Movies -->
    <div class="row">
        <h2>Comedy Movies</h2>
        <div class="row_posters">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
        </div>
    </div>

     <!-- Horror Movies -->
     <div class="row">
        <h2>Horror Movies</h2>
        <div class="row_posters">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
        </div>
     </div>

     <!-- Romance Movies -->
    <div class="row">
        <h2>Romance Movies</h2>
        <div class="row_posters">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
        </div>
    </div>

    <!-- Documentaries -->
    <div class="row">
        <h2>Documentaries</h2>
        <div class="row_posters">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
        </div>
    </div>

     <!-- Sci-Fiction Movies -->
     <div class="row">
        <h2>Sci-Fiction Movies</h2>
        <div class="row_posters">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
            <img src="images/small-movie1.jpg" alt="" class="row_poster">
            <img src="images/small-movie2.jpg" alt="" class="row_poster">
            <img src="images/small-movie3.jpg" alt="" class="row_poster">
            <img src="images/small-movie4.jpg" alt="" class="row_poster">
            <img src="images/small-movie5.jpg" alt="" class="row_poster">
            <img src="images/small-movie6.jpg" alt="" class="row_poster">
            <img src="images/small-movie7.jpg" alt="" class="row_poster">
            <img src="images/small-movie8.jpg" alt="" class="row_poster">
        </div>
    </div>

    <script>
        const nav = document.getElementById('nav');
        window.addEventListener('scroll',() => {
            if(window.scrollY >=100) {
                nav.classList.add('nav_black')
            } else {
              nav.classList.remove('nav_black'); 
                

            }
             

        })

    </script>

</body>
</html>
```

## CSS代码： 

```css
* {
    margin: 0;
    box-sizing: border-box;
}

body{
    font-family: Arial, Helvetica, sans-serif;
    background-color: #111;
}

.row_poster {
    width: 100%;
    object-fit: contain;
    max-height: 100px;
    margin-right: 10px;
    transition: transform 450ms;
}

.row_posters {
    display: flex;
    overflow-y: hidden;
    overflow-x: scroll;
    padding: 20px;
}

.row_poster:hover {
    transform: scale(1.2);
}

.row_posters::-webkit-scrollbar {
    display: none;
}

.row_posterLarge {
    max-height: 300px;
}

.row_posterLarge:hover {
    transform: scale(1.3);
}

.row {
    color: white;
    margin-left: 20px;
}

.banner {
    background-image: url('images/banner.jpg');
    background-size:cover;
    background-position: center center;
    color: white;
    object-fit: contain;
    height: 448px;
}

.banner_contents {
    margin-left: 30px;
    padding-top: 140px;
    height: 190px;
}

.banner_title {
    font-size: 3rem;
    font-weight: 800;
    padding-bottom: 0.3rem;
}

.banner_description {
    width: 45rem;
    line-height: 1.4;
    padding-top: 1rem;
    font-size: 1.1rem;
    max-width: 400px;
    height: 180px;
}

.banner_button {
    cursor: pointer;
    color: white;
    outline: none;
    border: none;
    font-weight: 700;
    border-radius: 0.2vw;
    padding-left: 2rem;
    padding-right: 1rem;
    margin-right: 1rem;
    padding-top: 0.5rem;
    padding-bottom: 0.5rem;
    background-color: rgba(51, 51, 51, 0.5);
}

.banner_button:hover {
    color: black;
    background-color: white;
    transition: all 0.2s;
}


.banner--fadeBottom {
    margin-top: 145px;
    height: 7.4rem;
    background-image: linear-gradient(180deg, transparent, rgba(37, 37, 37, 0.61), #111);
}


.nav_logo {
    width: 80px;
    object-fit: contain;
}

.nav_avater {
    width: 30px;
    object-fit: contain;
}

.nav {
    position: fixed;
    top: 0;
    width: 100%;
    display: flex;
    justify-content: space-between;
    padding: 20px;
    z-index: 1;
    transition-timing-function: ease-in;
    transition: all 0.5s;
}

.nav_black {
    background-color: #111; 
}




```



## 最终效果：

![最终效果](https://raw.githubusercontent.com/Jinhui1988/PicGo_Photo/ba6490ee721ae544319d3a4d34dbac8a28b14994/img/My%20Draw%E5%A5%88%E9%A3%9E%E9%A6%96%E9%A1%B5%E6%90%AD%E5%BB%BA%E6%95%88%E6%9E%9C.jpg)



![最终效果](https://raw.githubusercontent.com/Jinhui1988/PicGo_Photo/main/img/My%20Draw%E5%A5%88%E9%A3%9E%E9%A6%96%E9%A1%B5%E6%90%AD%E5%BB%BA%E6%95%88%E6%9E%9C02.jpg)







## 结语：

​       以上是搭建这个网页的时候写的代码，就html和css，还算不是太难对我老说，但是js应该就不是这样了！放上来特此记录



**PEACE !** 
