<template>
    
    <div class="container">
        <nav>
        <ul>
            <p><a href="#">Контакты</a></p>
            <p><a href="#">Помощь</a></p>
            <p><a href="#">Услуги и сервис</a></p>
            <p><a href="#">Стать партнером</a></p>
        </ul>
        <ul>
            <img src="../assets/icons/user.svg" alt="usericon">
            <p><a href="#">Вход</a></p>
            |
            <p><a href="#">Регистация</a></p>
        </ul>
        </nav>
</div>
<hr style="width: 100%;height: 1px;opacity:0.3;margin-top: -10px; background-color: black; margin-bottom: 20px;">
<div class="container">
        <div class="logobar">
            <img src="../assets/Logo.png" alt="">
            <div class="serachcontent">
                <input class="search" placeholder="Поиск по товарам..." type="text">
                <img src="../assets/icons/search.svg" alt="">
            </div>
            <div>
                <button><img src="../assets/icons/location.svg" alt=""> </button>
                <li>Работаем по всему <br> Узбекистану</li>
            </div>
            <div>
                <button><img src="../assets/icons/tel.svg" alt=""> </button>
                <li>+998 90 000 00 00 <br> <a href="#">Заказать звонок</a></li>
            </div>
            <div>
                <button><img src="../assets/icons/savat.svg" alt=""></button>
                    <li>Корзина <span class="counter">1</span></li>
            </div>
        </div>

       
    </div>
    
    <div class="nav_section">
               
        <div class="container nav_bar">
            <div>
                    <ul>
                        <img src="../assets/icons/gamburg.svg" alt="">
                        <li>Все категории</li>
                    </ul>
                    <li><a href="#">О нас</a></li>
                    <li><a href="#">Оплата и доставка</a></li>
                    <li><a href="#">Услуги</a></li>
                    <li><a href="#">Контакты</a></li>
                    <li><a href="#">Отзывы</a></li>
                    <li><a href="#">Новинки</a></li>
                    <li><a href="#">Вакансии</a></li>
            </div>
            <div>
                    <div>
                        <span class="heart_count">1</span>
                        <img src="../assets/icons/heart.svg" alt="">
                    </div>
                    <p><a href="#">Избранное</a></p>
            </div>
        </div>

    </div>


</template>

<script>

export default{
name:'TheNavbar'
}

</script>


<style scoped>
*{
    list-style: none;
    text-decoration: none;
    /* box-sizing: border-box; */
}
.container{
    width: 1250px;
    margin: 0 auto;
}
nav{
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
nav ul:nth-child(1){
    width: 400px;
}
nav ul:nth-child(2){
 gap: 5px;
}
nav ul{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
p a{
color: #90989F;
font-weight: 400;
font-size: 15px;
}
p a:hover{
    color:#FFD600 ;
    text-decoration: underline #FFD600 ;
}
/* logobar start */
.logobar{
    margin: 0 auto;
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.logobar div{
    display: flex;
    align-items: center;
    gap: 8px;
}
.logobar div button{
    width: 46px;
    height: 46px;
    border-radius: 100%;
    background: #FFD6001A;
    border: none;
    cursor: pointer;
}
.logobar div button:hover{
    background-color: #f9f19c;
    box-shadow: 0 0 20px #f7f0a2;
}
.search{
    padding: 15px ;
    padding-right: 200px;
    background:#F9F9F9;
    border: none;
    outline: none;
}
.serachcontent img{
    position: relative;
    right: 35px;
    cursor: pointer;
}
.counter{
   position: relative;
   left: 20px;
  width: 14px;
  height: 14px;
  font-size: 11px;
  border-radius: 100%;
  background-color: #FFD600;
  display: flex;
  justify-content: center;
  align-items: center;
}
/* .logobar end */
/* header start */
 .nav_section{
    width: 100%;
    height: 65px;
    margin-top: 23px;
    margin-bottom: 23px;
    box-shadow: 0px 0px 10px 0px #2979FF1A;
 }
.nav_bar{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 5px;
}
.nav_bar ul{
    display: flex;
    gap: 10px;
}
 
.nav_bar  div{
    gap: 20px;
    display: flex;
    align-items: center;
}
.nav_bar div li a{
    color: black;
    font-weight: 700;
    font-size: 16px;
}
.heart_count{
    position: relative;
    left: 28px;
    top:-9px;
    width: 14px;
  height: 14px;
  font-size: 11px;
  border-radius: 100%;
  background-color: #FFD600;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>