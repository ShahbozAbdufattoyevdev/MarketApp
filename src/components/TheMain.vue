<template>
    
    <TheNavbar />
    
    <!-- <div class="container">
    </div>
        <div class="swiper_box">

        </div>
        <div class="container">
            <main>
                <div class="heading"><h2 class="diffrent">Популярные <span>товары</span></h2></div>
                <section class="main_first">
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                </section>
                <div class="heading uspeyt"><h2 class="diffrent_second"><span>Успейте</span> купить</h2></div>
                
                <section class="main_second">
                    <UnicCard />

                    <div class="kupit_products">
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    </div>
                </section>
            </main>
        </div>

        <section class="main_third">
            <h3>Наши партнеры</h3>
            <pre>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Placerat eu mauris, varius neque orci neque tortor.</pre>
        </section>

        <div class="container">
            <main>
                <div class="colordifrent"><h2>Новые <span>товары</span></h2></div>
                <section class="main_fourth">
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                    <TheCard />
                </section>
            </main>
        </div>
        <section class="main_fifth">
            <h3>Наши преимущества</h3>
         <div class="container oplata">
          <TheOplata />
          <TheOplata />
          <TheOplata />
          <TheOplata />
         </div>
        </section> -->
      <KartochkiTovar />
    <TheFooter />
</template>


<script>
    import TheNavbar from './TheNavbar.vue'
    // import TheCard from './TheCard.vue';
    // import UnicCard from './UnicCard.vue';
    // import TheOplata from './TheOplata.vue';
    import KartochkiTovar from './KartochkiTovar.vue'
    import TheFooter from './TheFooter.vue';
export default {
    name: 'TheMain',
    components: {
        // TheCard, UnicCard, TheOplata, 
        TheFooter, TheNavbar, KartochkiTovar
    }
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
 
.nav_bar{
    width: 100%;
    display: flex;
    justify-content: space-between;
}
.nav_bar ul{
    display: flex;
    gap: 10px;
}
 
.nav_bar div{
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
/* SWIPPERBOX START */
.swiper_box{
    width: 100%;
    height: 482px;
    border: 2px solid #FFD600;
}
/* main start */
main{
    width: 100%;
}
.heading{
    width: 309px;
    height: 36px;
    background-color: #FFD600;
    display: flex;
    align-items: center;
    margin-top: 90px;
    margin-bottom: 60px;
}
.diffrent{
    position: relative;
    left: 165px;
    color: white;
}
.diffrent span{
    color: black;
}

.main_first{
    width: 100%;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
}
.main_second{
    display: flex;
    justify-content: space-between;
}
.diffrent_second{
    position: relative;
    right:88px;
    color: white;
}
.diffrent_second span{
color: black;
}
.uspeyt{
    margin:70px auto;
}
.kupit_products{
    width: 800px;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
}

/* main third start */

.main_third{
    margin-top: 70px;
    margin-bottom: 70px;
    width: 100%;
    height: 280px;
    background-color:#F5F7FA;
    padding-top:28px ;
}
.main_third h3{
    text-align: center;
    
}
.main_third pre{
    text-align: center;
}

/* main foourth start */

.colordifrent{
    width: 231px;
    height: 36px;
    background-color: #FFD600;
    display: flex;
    align-items: center;
    margin-bottom: 50px;
}
.colordifrent h2 span{
    color: black;
}
.colordifrent h2{
    color: white;
    position: relative;
    left: 150px;
   
}
.main_fourth{
    width: 100%;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
}
.main_fifth{
    width: 100%;
    height: 435px;
    padding-top: 20px;
   background-color: #F5F7FA;
}
.main_fifth h3{
    text-align: center;
}
.oplata{
    margin-top: 50px;
  
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}

</style>