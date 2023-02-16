<template>
    
<div class="property">
     <div>
        <img src="../assets/propertyimg.png" alt="">
        <ul>
            <li><a href="">В избранное</a></li>
            <li><a href="">Удалить</a></li>
        </ul>
     </div>
     <div>
        <h2>New Year Candle, Christmas <br> Gift Idea</h2>
        <h3>Коротко о товаре</h3>
        <li>Handmade</li>
        <li>Handmade</li>
        <li>Handmade</li>
        <li>Доступно только 4 штуки, и сейчас это <br> есть у более 20 человек</li>
     </div>
     <hr style="width: 2px;opacity: 0.5;height: 100%;">
     <div>
        <h2>1 000 000 UZS <span>1 000 000 UZS</span></h2>
        <button>Sale: <span>10%</span></button>
        <button>
            -
            10
            +
        </button>
        <button>Общая цена:</button>
        <h2>100 000 000 UZS</h2>
     </div>
</div>

</template>


<script>
export default {
    name: 'ProductProperty'
}
</script>


<style scoped>
.property{
    width: 695px;
    height: 211px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    
}
</style>