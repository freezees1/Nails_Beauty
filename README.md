<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nails Beauty</title>
    <link rel="stylesheet" href="css/main1.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" />
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cuprum:ital,wght@0,400..700;1,400..700&family=Limelight&display=swap');

        * {
            margin: 0;
            padding: 0;
        }

        .limelight-regular {
        font-family: "Limelight", sans-serif;
        font-weight: 400;
        font-style: normal;
        }

        .cuprum {
        font-family: "Cuprum", sans-serif;
        font-optical-sizing: auto;
        font-weight: 400;
        font-style: normal;
        }

        a {
            text-decoration: none;
        }

        img {
            max-width: 100%;
        }




        .container {
            width: 1400px;
            margin: 0 auto;
        }

        header {
            padding: 20px 0;
        }

        header .logo {
            font-size: 32px;
            color: #CA014E;
        }

        header nav {
            float: right;
            width: 50%;
        }

        header nav ul {
            list-style: none;
            display: flex;
            flex-direction: row-reverse;
        }

        header nav ul li {
            display: inline-block;
        }

        header nav ul li a {
            color: black;
        }

        .num {
            font-size: 24px;
        }

        .wrapper {
            background-color: black;
            border-radius: 30px;
            border: 15px solid white;
        }

        .hero {
            padding-bottom: 100px;
            color: white;
            position: relative;
        }

        .hero--info {
            width: 930px;
            padding-top: 70px;
            text-align: center;
        }

        .hero--info h1 {
            font-size: 96px;
        }

        .hero--info p {
            font-size: 24px;
            margin: 30px;
        }

        .btn {
            background-color: #CA014E;
            color: #fff;
            border-radius: 30px;
            padding: 15px;
            border: 20px;
            font-size: 18px;
            width: 200px;
            position: relative;
        }

        .hero_img {
            position: absolute;
            top: 100px;
            right: 100px;
            width: 462px;
        }

        .stolb {
            display: flex;
            justify-content: space-between;
            width: 600px; 
            padding-left: 150px;
        }

        .btn--in {
            padding-bottom: 30px;
        }

        .wrapper--price {
            background-color: #FFCCDF;
            border-radius: 30px;
            border: 15px solid white;
        }

        .line {
            height: 2px;
            background: #FFCCDF;
            box-sizing: content-box;
            margin-bottom: 16px;

        }

        .container--price {
            width: 60%;
            margin: 0 auto;
        }

        .item--price {
            background-color: #fff;
            border-radius: 30px;
        }

        .centr {
            text-align: center;
            padding: 70px;
        }

        .manik {
            color: #CA014E;
            font-size: 48px;
        }

        .nad {
            color: #4E4E4E;
            padding-bottom: 15px;
            font-size: 18px;
        }

        .item--lr {
            display: flex;
            justify-content: space-between;
            padding-left: 100px;
            padding-right: 100px;
            padding: 20px;
        }

        .text {
            font-size: 24px;
            color: #CA014E;
        }

        .btn--it {
            padding: 20px;
        }

        .padd {
            padding: 50px;
            width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .manik1 {
            color: #CA014E;
            font-size: 48px;
            display: flex;
            justify-content: center;
            padding-bottom: 30px;
        }

        .p1 {
            font-size: 24px;
            padding-bottom: 20px;
        }

        .wrapper--clear {
            background-image: url("https://avatars.mds.yandex.net/get-altay/13818104/2a00000192b4b9d18dec5fa975a05596e3bb/XXXL");
            border-radius: 30px;
            border: 15px solid white;
            height: 500px;
            width: auto;
            background-size: contain;
        }

        .padd1 {
            padding-top: 150px;
            padding-bottom: 100px;
            width: 1000px;
            margin-left: auto;
            margin-right: auto;
            
        }

        .obgect {
            display: flex;
            flex-flow: column-reverse;
            height: 100%;
            width: 800px;
        }

        .a {
            display: flex;
            flex-flow: row nowrap;
        }

        .b {
            height: 150px;
            padding-bottom: 100px;
        }

        .image--1 {
            height: 48px;
            width: 48px;
        }

        .h2--1 {
            font-size: 32px;
            color: #CA014E;
        }

        .p--2 {
        font-size: 24px; 
        }

        .pol {
            display: flex;
            align-items: flex-start;
            flex-wrap: nowrap;
            width: 1400px;
        }

        .wrapper_wi {
            background-color: #fff;
            border-radius: 30px;
        }

        .container_wi {
            width: 30%;
            margin: 0 auto;
        }

        .nails {
            padding: 30px;
            width: 80%;
            border-radius: 60px;
        }

        .h2--3 {
            color: #CA014E;
            font-size: 32px; 
            padding-bottom: 10px;
        }

        .p--3 {
            padding-bottom: 30px;
            width: 90%;
            margin-left: auto;
            margin-right: auto;
            font-size: 24px; 
        }

        .pad--1 {
            padding-top: 50px;
            padding-bottom: 100px;
        }

        .pad--2 {
            padding-bottom: 50px;
        }

        .nowrap {
            display: flex;
            flex-flow: row nowrap;
            padding-bottom: 50px;
        }

        .wrapper_ros {
            background-color: #FFCCDF;
            border-radius: 30px;
            width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .nails--2 {
            border-radius: 60px;
        }

        .text--al {
            width: 80%;
            margin-left: auto;
            margin-right: auto;
            padding: 400;
            margin-top: 50px;
        }

        .p--4 {
            font-size: 24px; 
            padding-bottom: 20px;
        }

        .h2--4 {
            color: #CA014E;
            font-size: 32px;
        }






        .button {
            cursor: pointer;
        }
        .modal {
            display: none; 
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%; 
            height: 100%;
            overflow: auto;
            background-color: rgba(0,0,0,0.4);
        }
        .modal-content {
            background-color: #fcdde8;
            margin: 20% auto;
            padding: 20px;
            border: 5px solid #CA014E;
            border-radius: 30px;
            width: 400px;
            padding-left: 100px;
        }
        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
        }
        .close:hover,
        .close:focus {
            color: black;
            text-decoration: none;
            cursor: pointer;
        }


        #scrollButton {
            cursor: pointer;
        }

        body {
            height: 2000px;
        }

        .text--but {
            font-size: 18px; 
        }

        .input--1 {
            border: 1px solid #ccc;
            width: 300px;
            height: 30px;
            margin-top: 10px;
        }

        .input--12 {
            width: 300px;
            height: 150px;
            margin-top: 10px;
            border: 1px solid #ccc;
        }

        .btn--1 {
            display: flex;
            justify-content: center;
        }








        .container--3 {
            background-color: #fff;
            padding: 20px;
            border-radius: 30px;
            width: 500px;
            border: 5px solid #CA014E;
        }

        .h1--5 {
            text-align: center;
            color: #000000;
        }

        .label--1 {
            display: block;
            margin-bottom: 10px;
            margin-top: 10px;
        }

        .input--3 {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }

        .select {
            height: 32px;
        }

        .textarea {
            resize: vertical;
        }

        .button1 {
            background-color: #CA014E;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 30px;
            cursor: pointer;
            font-size: 18px;
        }

        button:hover {
        background-color: #3b0017;
        }

        .cent--4 {
            display: flex;
            justify-content: center;
        }



        @media (max-width: 1200px){ 
            .container {
                width: 1000px;
                margin: 0 auto;
            }
            .hero--info {
                width: 400px;
                padding-top: 70px;
                text-align: center;
            }

            .hero--info h1 {
                font-size: 68px;
            }

            .hero--info p {
                font-size: 20px;
                margin: 30px;
            }
            .stolb {
                display: flex;
                justify-content: space-between;
                width: 500px; 
                padding-left: 0;
            }
            .hero_img {
                position: absolute;
                top: 100px;
                right: 50px;
                width: 462px;
            }
            .pol {
                display: flex;
                align-items: flex-start;
                flex-wrap: nowrap;
                width: 1000px;
            }
        }

        @media (max-width: 992px){ 
            .container {
                width: 800px;
                margin: 0 auto;
            }
            .hero--info {
                width: 300px;
                padding-top: 48px;
                text-align: center;
            }

            .hero--info h1 {
                font-size: 68px;
            }

            .hero--info p {
                font-size: 20px;
                margin: 30px;
            }
            .stolb {
                display: flex;
                justify-content: space-between;
                width: 300px; 
                padding-left: 0;
            }
            .hero_img {
                position: absolute;
                top: 100px;
                right: 50px;
                width: 350px;
            }
            .pol {
                display: flex;
                align-items: flex-start;
                flex-wrap: nowrap;
                width: 800px;
            }
            .padd1 {
                padding-top: 150px;
                padding-bottom: 100px;
                width: 800px;
                margin-left: auto;
                margin-right: auto;
            }
        }

        @media (max-width: 768px){ 
            .container {
                width: 600px;
                margin: 0 auto;
            }
            .hero--info {
                width: 600px;
                padding-top: 48px;
                text-align: center;
            }

            .hero--info h1 {
                font-size: 68px;
            }

            .hero--info p {
                font-size: 20px;
                margin: 30px;
            }
            .stolb {
                display: flex;
                justify-content: space-between;
                width: 600px; 
                padding-left: 0;
            }
            .hero_img {
                position: absolute;
                top: 100px;
                right: 50px;
                width: 0px;
            }
            .pol {
                display: flex;
                align-items: flex-start;
                flex-wrap: nowrap;
                width: 600px;
            }
            .padd1 {
                padding-top: 150px;
                padding-bottom: 100px;
                width: 500px;
                margin-left: auto;
                margin-right: auto;
            }
            .b {
                height: 150px;
                padding-bottom: 200px;
            }
            .padd {
                padding: 50px;
                width: 500px;
                margin-left: auto;
                margin-right: auto;
            }
            .container--price {
                width: 95%;
                margin: 0 auto;
            }
        }
    </style>
</head>
    
<body>

    <header class="container limelight-regular animate__animated animate__slideInDown">
        <span class="logo">Nails Beauty</span>
        <nav>
            <ul>
                <li><a href="https://whatsaps.ru/" class="whatsaps"><img width="32" height="32" src="https://img.icons8.com/?size=100&id=16712&format=png&color=000000" alt="whatsaps"></a></li>
                <li><a href="https://telegram.org/" class="telegram"><img width="32" height="32" src="https://img.icons8.com/?size=100&id=9R1sV3QvY18K&format=png&color=000000" alt="telegram"></a></li>
                <li><a href="tel:+70000000000" class="num">+7 (912) 345 67 89</a></li>
            </ul>
        </nav>
    </header>

    <div class="wrapper">
        <div class="hero container animate__animated animate__slideInDown">
            <div class="hero--info cuprum">
                <h1>Красивые ногти - </br>ваше идеальное </br>дополнение</h1>
                <p>Доверьтесь профессионалу и наслаждайтесь атмосферой спокойствия,</br> которое я создаю для вас</p>
                
                <div class="btn--in">
                    <button class="btn" id="scrollButton">Записаться онлайн</button>
                </div>

                <div class="stolb">
                    <div>
                        <img src="img\icons8-часы-48.png" alt="часы">
                        <p>Время работы</br>Без выходных</br>10:00-22:00</p>
                    </div>
                    <div>
                        <img src="img\icons8-карта-48.png" alt="карта">
                        <p>Адрес</br>г. Москва, ул. Ленинская,</br>дом 0, корп 0, офис 0</p>
                    </div>
                    
                </div>
            </div>
            
            <img src="img\Визуал.jfif" alt="Описание картинки" class="hero_img">
        </div>
    </div>
    
    <div class="wrapper--price cuprum">
        <div class="container centr">
            <h1 class="manik">Маникюр</h1>
            <h2 class="nad">Сделайте маникюр для отличного настроения</h2>
            

            <div class="container--price">
                <div class="item--price">


                    <div class="item--lr text">
                        <p>Маникюр (без покрытия)</p>
                        <p>1200 ₽</p>
                    </div>
                    <div class="line"></div>
                    <div class="item--lr text">
                        <p>Маникюр с покрытием гель лак</p>
                        <p>3000 ₽</p>                        
                    </div>
                    <div class="line"></div>
                    <div class="item--lr text">
                        <p>Маникюр со снятием и покрытием гель-лак</p>
                        <p>3700 ₽</p> 
                    </div>
                    <div class="line"></div>
                    <div class="item--lr text">
                        <p>Маникюр французский или лунный</p>
                        <p>4200 ₽</p> 
                    </div>
                    <div class="line"></div>
                    <div class="item--lr text">
                        <p>Маникюр + наращивание + покрытие в один тон</p>
                        <p>4000 ₽</p> 
                    </div>
                    <div class="line"></div>
                    <div class="item--lr text">
                        <p>Маникюр + наращивание + покрытие френч</p>
                        <p>3000 ₽</p> 
                    </div>
                    <div class="line"></div>
                </div>   
            </div>
        </div>
    </div>

    <div class="wrapper--price cuprum">
        <div class="container centr">
            <h1 class="manik">Педикюр</h1>
            <h2 class="nad">Простые удовольствия могут сделать вашу неделю, а не только день</h2>
            

            <div class="container--price">
                <div class="item--price">


                    <div class="item--lr text">
                        <p>Педикюр</p>
                        <p>3000 ₽</p>
                    </div>
                    <div class="line"></div>
                    <div class="item--lr text">
                        <p>Педикюр Лайт</p>
                        <p>1000 ₽</p>                        
                    </div>
                    <div class="line"></div>
                    <div class="item--lr text">
                        <p>Педикюр+гель-лак</p>
                        <p>3700 ₽</p> 
                    </div>
                    <div class="line"></div>
                    <div class="item--lr text">
                        <p>Медицинский педикюр</p>
                        <p>1000 ₽</p> 
                    </div>
                    <div class="line"></div>
                    <div class="item--lr text">
                        <p>Установка титановой нити</p>
                        <p>4000 ₽</p> 
                    </div>
                    <div class="line"></div>
                    <div class="item--lr text">
                        <p>Удаление стержневой мозоли</p>
                        <p>3000 ₽</p> 
                    </div>
                    <div class="line"></div>
                </div>            
            </div>
        </div>
    </div>

    <div class="container cuprum">
        <div class="padd">
            <h1 class="manik1">O моей студии</h1>
            <p class="p1">В моем салоне маникюра и педикюра я стремлюсь не просто предоставить услуги, а создать особенную атмосферу уюта для каждого клиента. Моя главная цель - помогать раскрыть вашу красоту и обеспечивать комфортное пребывание в наших студиях.</p>
            <p class="p1">Я ценю каждого посетителя и делаю все возможное, чтобы ваши визиты оставляли только положительные впечатления. Возвращайтесь к мне снова и снова, чтобы наслаждаться заботой и вниманием, которые мы уделяем каждому клиенту.</p>
        </div>
    </div>

    <div class="wrapper--clear"></div>

    <div class="container cuprum">
        <div class="padd1">
            <h1 class="manik1">Почему выбирают меня</h1>
            <div class="a">
                <div class="obgect">
                    <div class="b">
                        <img src="img\icons8-чистый-48.png" alt="clean" class="image--1">
                        <h2 class="h2--1">Стерильно</h2>
                        <p class="p--2">Настоящий маникюр - это безопасный маникюр: 3 этапа стерилизации инструментов по СанПиН</p>
                    </div>
                    <div class="b">
                        <img src="img\icons8-доверие-48.png" alt="Доверие" class="image--1">
                        <h2 class="h2--1">Доверие</h2>
                        <p class="p--2">4 000 клиентов в год - это много-много людей, которые выбирают именно меня</p>
                    </div>
                </div>
                <div class="obgect">
                    <div class="b">
                        <img src="img\icons8-палец-вверх-50.png" alt="палец" class="image--1">
                        <h2 class="h2--1">Контроль качества</h2>
                        <p class="p--2">Разработаны и внедрены стандарты и процедуры выполнения маникюрных услуг, что гарантирует единое качество моей работы</p>
                    </div>
                    <div class="b">
                        <img src="img\icons8-рукопожатие-50.png" alt="рукопожатие" class="image--1">
                        <h2 class="h2--1">7 дней гарантии на услуги</h2>
                        <p class="p--2">На основании ФЗ "О защите прав потр-ей" от 07.02.1992 г., №2300-1 (ст. 5) гарантия на услуги маникюра предоставляется на 3 дня, но я гарантирую больше</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="wrapper--price cuprum pad--1">
        <div class="container centr">
            <h1 class="manik pad--2">Выгодные предложения для вас</h1>

            <div class="pol">
                <div class="wrapper_wi container_wi">
                    <img src="img\фото1.png" alt="ногти" class="nails">
                    <h2 class="h2--3">Скидка 10%</h2>
                    <p class="p--3">По промокоду HOCHU10 на услуги новых мастеров студии до 29 июля</p>
                </div>
                <div class="wrapper_wi container_wi">
                    <img src="img\фото2.png" alt="ногти" class="nails">
                    <h2 class="h2--3">Кэшбек 3%</h2>
                    <p class="p--3">Для наших постоянных гостей КЭШБЕК 3% с каждой оплаты от 2000 рублей</p>
                </div>
                <div class="wrapper_wi container_wi">
                    <img src="img\фото3.png" alt="ногти" class="nails">
                    <h2 class="h2--3">Скидка 12%</h2>
                    <p class="p--3">Получите скидку 12% в честь вашего дня Рождения!</p>
                </div>
            </div>
        </div>
    </div>

    <div class="container cuprum">
        <div class="padd1">
            <h1 class="manik1">Отзывы о моей работе</h1>
            <div>
                <div class="nowrap">
                    <img src="img\фото12.png" alt="маникюр" class="nails--2">
                    <div class="wrapper_ros">
                        <div class="text--al">
                            <p class="p--4">Была в салоне, делала спа-маникюр и педикюр. Мастер сделала все довольно быстро, но при этом очень качественно. Видно, что мастер любит свою работу. Салон очень чистый, приятный, персонал вежливый. В общем, я очень довольна.</p>
                            <h2 class="h2--4">Светлана</h2>
                        </div>
                    </div>
                </div>
                <div class="nowrap">
                    <div class="wrapper_ros">
                        <div class="text--al">
                            <p class="p--4">Очень уютное местечко в центре города. Приятный и веждивый персонал. Соотношение цена/качество идеальное. Большое спасибо!</p>
                            <h2 class="h2--4">Елена</h2>
                        </div>

                    </div>
                    <img src="img\фото22.png" alt="маникюр" class="nails--2">
                </div>
            </div>
            <div class="btn--1">
            
                <button class="button btn" id="openModal">Оставить отзыв</button>

                <div id="myModal" class="modal">

                    <div class="modal-content">
                        <span class="close" id="closeModal">&times;</span>
                        <h2>Оставьте свой отзыв</h2>
                        <form id="reviewForm">
                            <label for="name" class="text--but">Имя:</label><br>
                            <input type="text" id="name" name="name" required class="input--1"><br><br>
                            <label for="phone" class="text--but">Телефон:</label><br>
                            <input type="tel" id="phone" name="phone" required class="input--1"><br><br>
                            <label for="comment" class="text--but">Комментарий:</label><br>
                            <textarea id="comment" name="comment" required class="input--12"></textarea><br><br>
                            <label for="photo" class="text--but">Загрузить фото:</label><br>
                            <input type="file" id="photo" name="photo" accept="image/*"><br><br>
                            <button type="submit" class="btn">Отправить</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="wrapper--price cuprum pad--1">
        <div class="container centr cent--4">
            <div class="container--3">
                <h1 class="h2--1">Запись на услугу</h1>
                <form>
                <label class="label--1" for="name">Имя:</label>
                <input type="text" id="name" name="name" required class="input--3">

                <label for="phone" class="label--1">Номер телефона:</label>
                <input type="tel" id="phone" name="phone" required class="input--3">

                <label for="date" class="label--1">Желаемая дата:</label>
                <input type="date" id="date" name="date" required class="input--3">

                <label for="design" class="label--1">Желаемый дизайн (фото):</label>
                <input type="file" id="design" name="design">

                <label for="service" class="label--1">Выберите услугу:</label>
                <select id="service" name="service" required class="input--3 select">
                    <option value="">-- Выберите услугу --</option>
                    <option value="service1">Маникюр (без покрытия)</option>
                    <option value="service2">Маникюр с покрытием гель лак</option>
                    <option value="service3">Маникюр со снятием и покрытием гель-лак</option>
                    <option value="service4">Маникюр французский или лунный</option>
                    <option value="service5">Маникюр + наращивание + покрытие в один тон</option>
                    <option value="service6">Маникюр + наращивание + покрытие френч</option>
                    <option value="service7">Педикюр</option>
                    <option value="service8">Педикюр Лайт</option>
                    <option value="service9">Педикюр+гель-лак</option>
                    <option value="service10">Медицинский педикюр</option>
                    <option value="service11">Установка титановой нити</option>
                    <option value="service12">Удаление стержневой мозоли</option>
                    <option value="service13">другое</option>
                </select>

                <label for="other_service" class="label--1">Если "Другое", укажите:</label>
                <textarea id="other_service" name="other_service" rows="4" class="input--3 textarea"></textarea>

                <button type="submit" class="button1">Отправить</button>
                </form>
            </div>
        </div>
    </div>




















<script>
    // Получаем модальное окно
    var modal = document.getElementById("myModal");

    // Получаем кнопку, которая открывает модальное окно
    var btn = document.getElementById("openModal");

    // Получаем элемент <span>, который закрывает модальное окно
    var span = document.getElementById("closeModal");

    // Когда пользователь нажимает на кнопку, открываем модальное окно
    btn.onclick = function() {
        modal.style.display = "block";
    }

    // Когда пользователь нажимает на <span> (x), закрываем модальное окно
    span.onclick = function() {
        modal.style.display = "none";
    }

    // Когда пользователь нажимает в любом месте вне модального окна, закрываем его
    window.onclick = function(event) {
        if (event.target == modal) {
            modal.style.display = "none";
        }
    }

    // Обработка отправки формы (например, для запрета отправки по умолчанию)
    document.getElementById("reviewForm").onsubmit = function(event) {
        event.preventDefault();
        alert("Ваш отзыв отправлен!");
        modal.style.display = "none";
        // Здесь можно добавить код для отправки данных на сервер
    }
</script>
<script>
    const button = document.getElementById('scrollButton');
    button.addEventListener('click', () => {
        window.scrollTo({
            top: document.body.scrollHeight,
            behavior: 'smooth' // Плавная прокрутка
        });
    });
</script>
</body>
</html>
