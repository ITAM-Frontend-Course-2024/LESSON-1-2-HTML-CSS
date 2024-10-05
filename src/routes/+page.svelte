<script>
    import './../reset.css'
</script>

<header>Шапка сайта</header>
<main>
    <h1>Большой и единсвтенный загаловок h1</h1>

    <h2>Списки</h2>
    <ul>
        <li>Пункт ненумерованного списка</li>
        <li>Пункт ненумерованного списка</li>
        <li>Пункт ненумерованного списка</li>
    </ul>
    <ol>
        <li>Пункт нумерованного списка</li>
        <li>Пункт нумерованного списка</li>
        <li>Пункт нумерованного списка</li>
    </ol>

    <q class="for_list">Но во втором списке мы убрали цифры через css с помощью свойства <span class="code">list-style: none;</span> для элементов li</q>

    <h2>Текст и его форматирование</h2>
    <p>Lorem ipsum <strong>dolor</strong> sit amet consectetur, <em>adipisicing</em> elit. <del>Cumque</del> a et nobis similique eaque, aliquid ab obcaecati nihil placeat <u>architecto</u> in culpa <q>necessitatibus</q> doloremque quaerat explicabo velit harum voluptatum praesentium!</p>

    <h2>Картинка</h2>
    <figure>
        <img class="meme" src="https://www.meme-arsenal.com/memes/9b757b8a21972270989167310a59f8d7.jpg" alt="">
        <figcaption>Мем про фронтенд</figcaption>
    </figure>
    <button type="button">Тык</button>

    <h2>Форма</h2>
    <form action="" method="get">
        <div>
            <label for="name">Name:</label>
            <input placeholder="Your name:" type="text" id="name" value="">
        </div>
        <div>
            <label for="mail">Email:</label>
            <input type="email" id="mail" value="">
        </div>
        <div>
            <label for="phone">Tel:</label>
            <input type="tel" id="phone" value="">
        </div>
        <div>
            <label for="pass">Password:</label>
            <input type="password" id="pass" value="">
        </div>
        <div>
            <label for="date">Birthday:</label>
            <input type="date" id="date" value="">
        </div>

        <h3>Choose items</h3>
        <div>
            <input type="checkbox" id="cat" value="">
            <label for="cat">Cat</label>

            <input type="checkbox" id="dog" value="">
            <label for="dog">Dog</label>

            <input type="checkbox" id="ham" value="">
            <label for="ham">Hamster</label>
        </div>

        <h3>Choose <u>one</u> item</h3>
        <div>
            <input type="radio" id="man" value="" name="gender">
            <label for="man">Man</label>

            <input type="radio" id="woman" value="" name="gender">
            <label for="woman">Woman</label>
        </div>

        <select name="" id="">
            <option disabled selected value="">No choose</option>
            <option value="">Item 1</option>
            <option value="">Item 2</option>
            <option value="">Item 3</option>
        </select>

        <div class="comment">
            <label for="">Поле для комментариев:</label>
            <textarea placeholder="Please, write here sth" name="" id="" cols="30" rows="4"></textarea>
        </div>

        <button type="submit">Submit</button>
    </form>
</main>
<footer>
    <a href="https://www.google.com/">Ссылка на гугл</a>
    <a href="https://ya.ru/">Ссылка на яндекс</a>
</footer>

<style>
    * {
        font-family: 'Roboto', sans-serif;
        font-size: 16px;
        font-weight: 400;
    }

    header, main, footer {
        padding-right: 60px;
        padding-left: 60px;
    }

    header {
        padding-top: 20px;
        padding-bottom: 20px;
        font-size: 24px;
        background-color: #e7f2d7;
        text-align: center;
    }

    h1 {
        font-size: 46px;
        margin: 20px 0;
    }

    h2 {
        font-size: 32px;
        margin: 40px 0 10px;
    }

    ul, ol {
        padding: 8px;
        margin: 10px 0;
        border: 2px solid lightgreen;
    }
    
    ul li {
        padding: 10px 0;
        color: rgb(69, 168, 41);
    }

    ol li {
        padding: 10px 0;
        color: rgb(3, 209, 109);
        list-style: none;
    }

    .for_list {
        font-style: italic;
        color: rgb(162, 141, 7);
    }

    .for_list span {
        color: red;
        font-weight: 600;
    }

    .meme {
        width: 450px;
        border: 4px dashed green;
    }

    button {
        margin: 8px 0 0;
        padding: 12px 18px;
        font-weight: 300;
        background-color: #6b9d2e;
        color: #fff;
        border-radius: 12px;
    }

    button:hover {
        background-color: #537a23;
    }

    form {
        max-width: 600px;
        display: flex;
        flex-direction: column;
        row-gap: 8px;
        padding: 20px;
        border: 2px solid gray;
        border-radius: 8px;
    }

    form button, form select {
        max-width: 100px;
    }

    form label {
        font-weight: 600;
    }

    form input {
        margin-left: 6px;
        padding: 4px;
        border: 1px solid rgb(199, 199, 199);
    }

    form > *:not(button)::before {
        content: '🔥';
    }

    .comment {
        display: flex;
        align-items: center;
    }

    form textarea {
        padding: 4px;
        margin-left: 8px;
        border: 1px solid gray;
    }

    footer {
        margin-top: 10px;
        padding-top: 40px;
        padding-bottom: 40px;
        background-color: rgb(241, 241, 241);
    }

    @media (max-width: 450px){

        header, main, footer {
            padding-right: 30px;
            padding-left: 30px;
        }

        li {
            font-size: 20px;
        }
    }


</style>