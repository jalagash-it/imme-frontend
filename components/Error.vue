<template>
    <section>
        <div class="info">
            <h1>Ошибка 404</h1>
            <ul>
                <li><a href="#">Главная</a></li>
                <li>Ошибка 404</li>
            </ul>
        </div>
        <div class="container">
            <div class="numbers">
                <span>
                    4
                </span>
                <span class="circle">
                    <i class="fas fa-bolt"></i>
                </span>
                <span>
                    4
                </span>
            </div>
            <div class="explain">Извините, страница больше не существует или <br>была перенесена.</div>
            <button class="btn">На главную</button>
        </div>

    </section>
</template>

<style scoped>
    *{box-shadow:border-box}body{padding-top:100px}.info{margin-left:10%}.info h1{font-weight:bold;font-size:42px}.info ul{margin-top:20px;padding:0;display:flex;flex-direction:row}.info li{margin-left:26px;color:rgba(0,0,0,0.4)}.info li:nth-child(1){list-style-type:none;margin-left:0;color:#60617B}.info a:nth-child(1){color:#5e5f7c;text-decoration:none;font-size:13px}.info a{color:rbga(0, 0, 0, 0.1)}.container{display:block;margin:0 auto;text-align:center}.container .numbers{color:#6B8BC9;font-size:250px;display:flex;text-align:center;flex-direction:row;justify-content:center;align-items:center;margin:0 auto}.container span{margin-left:20px;color:#6B8BC9;font-size:250px}.container .circle{color:#fff;font-size:150px;display:flex;justify-content:center;align-items:center;width:160px;height:200px;border-radius:100%;background-color:#6B8BC9}.container .explain{margin-top:80px;font-size:18px;font-weight:600}.container .btn{margin-top:37px;width:234px;height:47px;background:#6B8BC9;border-radius:12px;text-transform:uppercase;color:#fff;border:none;cursor:pointer}.container .btn:focus{outline:none}
</style>