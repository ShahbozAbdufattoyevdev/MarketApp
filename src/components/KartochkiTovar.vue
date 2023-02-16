<template>
    <div class="container ">
            <li style="margin-top: 40px;">Главная  /  Каталог  /  New Year Candle, Christmas Gift Idea </li>
        <section>
            <div class="property">
                <div class="product_box">
                    <div>
                        <img src="../assets/newyeari_mg.png" alt="">
                        <div class="choosen">
                            <img src="../assets/boximg.png" alt="">
                            <img src="../assets/boximg.png" alt="">
                            <img src="../assets/boximg.png" alt="">
                            <img src="../assets/boximg.png" alt="">
                        </div>
                    </div>
                    <div>
                        <h2>New Year Candle, Christmas Gift <br> Idea</h2>
                        <li>Состояние товара: Новый <span >×</span></li>
                        <div class="btn_box">
                            <button>Новый</button>
                            <button>Уцененный</button>
                        </div>
                        <h4> Коротко о товаре</h4>
                        <li>•  Handmade</li>
                        <li>•  Handmade</li>
                        <li>• Handmade</li>
                        <li style="line-height: 15px;">• Доступно только 4 штуки, и сейчас это 
                             <br> есть у более 20 человек</li>
                    </div>
                </div>
            </div>
            <div class="katalog">
                <div class="deliver">
                    <li>Самая низкая цена</li>
                  <h2>  1 000 000 UZS</h2>
                  <li><span><img src="../assets/icons/caricon.svg" alt=""></span>Бесплатно курьером, 2-3 дня</li>
                  <li><span><img src="../assets/icons/cardicon.svg" alt=""></span>Картой на сайте/курьеру, наличными</li>
                  <button><img src="../assets/icons/savatwhite.svg" alt=""> В корзину</button>
                  <div class="mark">
                    <h3>ЯБЛОЧКО</h3>
                    <li style="display: flex; gap:8px;">
                        <img src="../assets/icons/star.svg" alt="">
                        <img src="../assets/icons/star.svg" alt="">
                        <img src="../assets/icons/star.svg" alt="">
                        <img src="../assets/icons/star.svg" alt="">
                        <img src="../assets/icons/star.svg" alt="">
                    </li>
                    <p>5 отзывов</p>
                </div>
                </div>
                <div class="opisanie">
                    <h2>Описание</h2>
                    <button><img src="../assets/icons/Arrowbuttom.svg" alt=""></button>
                </div>
                <div class="opisanie">
                    <h2>Основные моменты</h2>
                    <button><img src="../assets/icons/Arrowbuttom.svg" alt=""></button>
                </div>
                <div class="opisanie">
                    <h2>Доставки и возврат</h2>
                    <button><img src="../assets/icons/Arrowbuttom.svg" alt=""></button>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name: 'KartochkiTovar'
}
</script>

<style scoped>
.container{
    width: 1250px;
    margin: 0 auto;
}
section{
    width: 100%;
    margin-top: 40px;
    display: flex;
   justify-content: space-between;
}
.property{
width: 62%; 
display: flex;
}
.choosen{
    width: 100%;
    display: flex;
 justify-content: space-between;
}
.choosen img{
width: 70px;
height: 67px;
 
}
.product_box li{
    list-style:square;
    opacity: 0.8;
    display: flex;
    font-size: 14px;
    align-items: center;
}
.product_box li span{
    width: 17px;
    height: 17px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 100%;
    background-color: #90989F;
    margin-left: 10px;
    cursor: pointer;
}
.product_box{
    display: flex;
    gap: 30px;
    line-height: 35px;
}

.katalog{
width: 31%; 
display: flow-root;
align-items: center;
line-height: 30px;
}


.btn_box{
    margin-top: 10px;
    width: 180px;
   
}
.btn_box button{
   margin-right: 10px; 
    padding:11px 10px;
    border-radius: 4px;
   border:#90989F 2px solid ;
   background: transparent;
}
.btn_box button:hover{
    border-color:#FFD600;
    /* color: #FFD600; */
}
.deliver{
    width: 300px;
    height: auto;
    padding: 20px 30px;
    box-shadow: 0px 5px 20px   #CCCCCC40;
}
.deliver:hover{
    box-shadow: 0px 5px 20px 8px  #CCCCCC40;
}
.deliver button{
    width: 310px;
    height: 40px;
    margin-top: 10px;
    border: none;
    border-radius: 4px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    gap: 10px;
    font-size: 18px;
    background-color: #FFD600;
}
.mark{
    display: flex;
    align-items: center;
    justify-content: left;
    gap: 30px;
    margin-top: 15px;
}
.opisanie{
    width: 300px;
    height: 54px;
    border-radius: 4px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0px 5px 20px   #CCCCCC40;
    padding: 10px 30px;
    margin-top: 15px;
}
.opisanie button{
    background: #FFD60045;
    border: none;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    widows: 35px;
    height: 25px;
}
</style>