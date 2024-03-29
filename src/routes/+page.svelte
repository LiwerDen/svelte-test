<svelte:head>
    <title>Liwer Sawmill</title>
</svelte:head>

<div class="container">
    <div class="info">
        <div class="animate-background">
            <div class="container info-container">
                <div class="welcome">
                    Добро пожаловать на <br>
                    <span>Нашу Лесопилку</span> <br>
                    <div class="welcome-down-text">
                        Liwer Sawmill
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>


<style>
    .info{
        text-align: center;
        position: relative;
    }
    .info-container{
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: left;
        align-items: start;
    }
    .container{
        max-width: 1400px;
        margin: 190px 0 0 2.5rem;
    }
    .welcome {
    text-align: center;
    margin-top: 250px;
    font-size: 50px;
    color: #fff;
    font-weight: 600;
    }
    .welcome span {
        font-size: 80px;
        font-weight: 700;
        padding-top: 10px;
        padding-bottom: 10px;
        }
    .welcome-down-text {
        font-weight: 600;
        font-size: 55px;
        margin-top: 10px;
        }
</style>