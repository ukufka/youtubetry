# youtubetry
Project study


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Учим HTML</title>
    <link href="styles.css" type="text/css" rel="stylesheet"/>
</head>
<body>
    <h1 id="top"><strong>Вот это основной заголовок</strong></h1>
    <p><i>Сейчас мы изучим формулу<br /></i> <b>E=mc<sup>2</sup></b></p>
    <hr />
    <p>А это уже <em>2 абзац</em></p>
    <blockquote cite="https://www.google.by"><p>
        Переходим <q>на сайт</q> <abbr title="https://www.google.by">Google</abbr>
    </p>
</blockquote>
<address><p><a href="https://www.google.by">
    <del>Переходм</del> <ins>Не переходим</ins> по адресу сайта Google
</a></p></address>
<ol>Упорядоченый список:
    <li>Используем ol</li>
    <li>Внутри используем li</li>
</ol>>
<ul>Теперь неупорядочный список:
    <li>Используем ul</li>
    <li>Внутри пользуемся li
        <ul>
            <li>ВЛоженный неупорядочный список 2 уровня
                <ol>
                    <li>А это уже упорядочный но 3 уровня</li>
                </ol>
            </li>
        </ul>
    </li>
    <li>Вернулись к нашему списку</li>
</ul>
<dl>Список определений:
    <dt>Обозначаем термин</dt>
    <dt><i>Можно еще один раз записать термин</i></dt>
    <dd>Тут даем определение</dd>
</dl>
<h2>Тут по ссылкам небольшая практика</h2>
<a href="https://learn.javascript.ru/native-prototypes"><abbr title="Тема: Прототипы">Допусим если нажать на это предложение то мы перейдём на learn.javascript</abbr></a>
<p><a href="mailto:ukufka@gmail.com">Напиши мне</a></p>
<p><a href="yandex.by" target="_blank">Нажми сюда</a>(откроется новое окно)</p>
<p><a href="#top">Вернуться </a>к заголовку H1</p>
<h2>Работа с изображениями</h2>
<img src="images/flat.jpg" alt="Фото квартиры на случай если не загрузится фото" title="Фото комнаты в нашей квартире" width="100" height="100"/>
<p>Первый вариант фото</p>
<hr />
<p><img src="images/flat.jpg" alt="Null" width="100" height="100" align="middle"/>Второй вариант</p>
<hr />
<p>Третий вариант фото <img src="images/flat.jpg" alt="" width="100" height="100"/> тоже может быть  </p>

<figure>
    <img src="images/flat.jpg" alt="Null" width="300" height="300"/>
    <br />
    <figurecaption>Вот таким образом добавили подпись к фотографии</figurecaption>
</figure>
<h3>Таблицы</h3>
<table bgcolor="grey">
    <thead>
    <tr>
        <th></th>
        <th scope="col">9am</th>
        <th scope="col">10am</th>
        <th scope="col">11am</th>
        <th scope="col">12am</th>
    </tr>
</thead>
<tbody>
    <tr>
        <th>Понедельник</th>
        <td colspan="2" rowspan="2" bgcolor="yellow">География</td>
        <td> Музыка</td>
        <td>ИЗО</td>
    </tr>
    <tr>
        <th scope="row">Вторник</th>
        <td>физкультура</td>
        <td>Биология</td>
    </tr>
</tbody>
<tfoot>
    <tr>
        <th>Среда</th>
        <td colspan="3" bgcolor="yellow">Музыка</td>
        <td>Математике</td>
    </tr>
</tfoot>
</table>
<h3>Формы</h3>
<form action="primer.ru" method="get">
    <p>Имя пользователя:
        <input type="text" name="username" maxlength="15" />
    </p>
    <p>
        Пароль:
        <input type="password" name="password" maxlength="10"/>
    </p>
    <p>Что вы думаете об этом?</p>
    <textarea name="comments" cols="20" rows="4">
        Введите свой комментарий...
    </textarea>
</form>
<form action="Куда отправляем данные">
<p>Выберите любимый жанр музыки</p>
<br />
<input type="radio" name="genre" value="rock"/>Рок
<input type="radio" name="genre" value="pop"/>Pop
<input type="radio" name="genre" value="techno"/>Электроинка
</form>
<form action="куда отправляем данные">
    <p>Где вы слушаете музыку?
    <input type="checkbox" name="music" value="home"/>Дома
    <input type="checkbox" name="music" value="work"/>На Работе
    <input type="checkbox" name="music" value="car"/>В машине
</p>
</form>
<form action="Куда отправляем данные">
<p>На каком устройстве чаще всего слушаете музыку?</p>
<select name="ustroistva">
    <option value="ipod">Ipod</option>
    <option value="radio">Radio</option>
    <option value="computer">Компьютер</option>
</select>
</form>
<form>
    <p>На каких инструментах Вы играете?<b>Ctrl</b> необходимо зажать,чтобы выбрать несколько</p>
    <select name="instrumentary" size="4" multiple="multiple">
        <option value="guitara">Гитара</option>
        <option value="bas" selected="selected">Бас-гитара</option>
        <option value="piano">Пианино</option>
        <option value="treygolnik">Треугольник</option>
        <option value="accord">Аккордион</option>
    </select>
</form>
<form action="куда отправляем данные" method="post">
    <p>Загрузка файлов на сервер</p>
    <input type="file" name="pesnya"/><br/>
    <input type="submit" value="Загрузитьь"/>
</form>
<form action="">
    <p>ПОдпишитесь на рассылку новостей!</p>
    <input type="text" name="email"/>
    <input type="image" src="images/flat.jpg" width="100" height="20"/><br />
    <button><img src="" alt="Добавить" width="10" height="10"/></button><br />
    <label>Возраст:<input type="text" name="vozrast"/></label>
    <br/>
    Пол:
    <input id="female" type="radio" name="pol" value="f">
    <label for="female">Женский</label>
    <input id="male" type="radio" name="pol" value="m">
    <label for="male">Мужской</label>
</form>
<fieldset>
    <legend>Контактная информация</legend>
    <label>Email:<br/>
        <input type="text" name="email"/>
    </label><br/>
    <label>Telephone<br/>
        <input type="text" name="phone"/>
    </label><br/>
    <label>Faks<br/>
        <input type="text" name="fax"/>
    </label>
    
</fieldset>
<form action="" method="post">
<label for="username">Имя пользователя</label>
<input type="text" name="usname" required="required"/><br/>
<label for="password">Пароль</label>
<input type="text" name="pass" required="required"/><br/>
<input type="submit" value="Отправить"/>
</form>
<form action="" method="post">
    <label for="depart">Дата вылета</label>
    <input type="date" name="depart"/>
    <input type="submit" value="отправить"/>
</form>
<form action="" method="post">
    <p>Введите адрес электронной почты:</p>
    <input type="email" name="email"/>
    <input type="submit" value="отправить"/>
    <p>Введите адрес сайта:</p>
    <input type="url" name="url"/>
    <input type="submit" value="отправить"/>
    <p>Поиск:</p>
    <input type="search" name="poisk" placeholder="Купить компьютер"/>
    <input type="submit" value="Искать"/>
</form>
<video src="https://www.youtube.com/watch?v=DRxX_6S0zsI" width='400' height="300">XAXAX</video>
<iframe width="570" height="300" src="../try/index.html"></iframe>
</body>
</html>
