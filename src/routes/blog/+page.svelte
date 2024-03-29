<svelte:head>
    <title>Услуги</title>
</svelte:head>

<div class="container">
    <div class="head-uslugi">
        Liwer Sawmill предоставляет услуги:
    </div>
    <div class="uslugi">
        <ul>
            <li>Доставка пиломатериалов и фанеры</li>
            <li>Нарезка пиломатериалов</li>
            <li>Распиловка фанеры</li>
            <li>Импрегнирование</li>
            <li>Антисептирование</li>
            <li>Антипирирование</li>
        </ul>
        <div class="uslugi-imfo">
            Антисептирование, антипирирование и импрегнирование – это обработка древесины специальным составом (септиком или антипиреном), которое обеспечивает огнебиозащиту древесины. В случае импрегнирования пропитка производится под давлением. 
        </div>
    </div>
</div>

<style>
    .container{
        margin: 50px auto;
        max-width: 1500px;
        padding: 0 20px;
    }
    .uslugi-imfo {
    text-align: center;
    margin-left: 18%;
    margin-right: 18%;
    color: white;
    font-size: 1.5rem;
    }
    .head-uslugi{
    text-align: center;
    color: white;
    margin-top: 20px;
    font-weight: 700;
    font-size: 3rem;
    }
    ul{
            display: block; 
            text-align: center;   
            margin-top: 35px;
            margin-bottom: 100px;        
        }
    li{
        list-style-type: none;
        padding-left: 35px;
        font-size: 24px;
        font-weight: 700;
        margin-right: 40px;
        color: white;
        padding: 5px;
    }
</style>