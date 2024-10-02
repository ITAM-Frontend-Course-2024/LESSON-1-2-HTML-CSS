<header>Шапка сайта</header>
<main>
    <h1>Большой и единсвтенный загаловок h1 на старнице</h1>

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

    <h2>Текст и его форматирование</h2>
    <p>Lorem ipsum <strong>dolor</strong> sit amet consectetur, <em>adipisicing</em> elit. <del>Cumque</del> a et nobis similique eaque, aliquid ab obcaecati nihil placeat <u>architecto</u> in culpa <q>necessitatibus</q> doloremque quaerat explicabo velit harum voluptatum praesentium!</p>

    <h2>Картинка</h2>
    <figure>
        <img src="https://www.meme-arsenal.com/memes/9b757b8a21972270989167310a59f8d7.jpg" alt="">
        <figcaption>Мем про фронтенд</figcaption>
        <button type="button">Тык</button>
    </figure>

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

        <div>
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