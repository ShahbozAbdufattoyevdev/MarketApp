<template>
    
    <footer>
        <div class="container footer">
            <ul>
                <img src="../assets/Logo.png" alt="">
                <p><a href="#">Интернет-магазин <br> Крафтовые ручные <br> поделки</a></p>
            </ul>
            <ul>
                <li><a href="#">О нас</a></li>
                <li><a href="#">Оплата и доставка</a></li>
                <li><a href="#">Услуги</a></li>
                <li><a href="#">Гарантия и возврат</a></li>
                <li><a href="#">Гарантия и возврат</a></li>
            </ul>
            <ul>
                <li><a href="#">Отзывы</a></li>
                <li><a href="#">Новинки</a></li>
                <li><a href="#">Новости</a></li>
                <li><a href="#">Контакты</a></li>
                <li><a href="#">Контакты</a></li>
            </ul>
            <ul>
                <li><a href="#">Отзывы</a></li>
                <li><a href="#">Новинки</a></li>
                <li><a href="#">Новости</a></li>
                <li><a href="#">Контакты</a></li>
                <li><a href="#">Контакты</a></li>
            </ul>
            <div class="logo_box">
                <li><a href="#">Cпособы оплаты</a></li>
               <div >
                <img src="../assets/paymelogo.svg" alt="">
                <img src="../assets/clicklogo.svg" alt="">
                <img src="../assets/visalogo.svg" alt="">
                <img src="../assets/mastercardlogo.svg" alt="">
                <img src="../assets/uzcardlogo.svg" alt="">
                <img src="../assets/apelsinlogo.svg" alt="">
                 
               </div>
            </div>
            <div>
                <li><a href="#">Социальные сети</a></li>
                <div class="social">
                   <img src="../assets/icons/facebook.svg" alt="">
                   <img src="../assets/icons/instagram.svg" alt="">
                   <img src="../assets/icons/Telegram.svg" alt="">
                </div>
            </div>
        </div>
    </footer>
<p style="background-color: #454346; text-align: center">Copyright 2020 © Logo.UZ — Все права защищены.</p>
</template>

<script>

export default  {
name: 'TheFooter'    
}

</script>

<style  scoped>
*{
    list-style: none;
    text-decoration: none;
}
.container{
    width: 1250px;
    margin:0 auto;
}
footer{
    margin-top: 80px;
}
.footer{
    display: flex;
    justify-content: space-evenly;
    
}
.footer ul li{
    margin-bottom: 10px;
    font-weight: 700;
}
 li a{
    color: black;
    font-size: 16px;
}
li a:hover{
    color: #FFD600;
}
.footer div{
    margin-top: 20px;
}
.footer img{
    cursor: pointer;
}
 .logo_box div{
    margin-top: 30px;
    width: 280px;
    display: flex;
    align-items: center;
    gap: 15px;
    flex-wrap: wrap;
 }
 .social{
    display: flex;
    gap: 15px;
 }

</style>