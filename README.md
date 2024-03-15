<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Ли Альбина Тевоновна</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №3. «HTML»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>Веб-разработка</b> — процесс создания веб-сайта или веб-приложения. Основными этапами процесса являются: </p>

<ul>
<li>Проектирование сайта или веб-приложения (сбор и анализ требований, разработка технического задания, проектирование интерфейсов);</li>
<li>Создание дизайн-концепции сайта;</li>
<li>Создание страниц;</li>
<li>Программирование;</li>
<li>Оптимизация и размещение материалов сайта;</li>
<li>Тестирование и внесение корректировок;</li>
<li>Публикация проекта на хостинге;</li>
<li>Обслуживание работающего сайта.</li>
</ul>

<br>

<h1 align = "center">Цели и задачи</h1>


<p>Цель: ознакомиться с принципами работы со стилями, классами.</p>

<p>Задачи:</p>

<ul>
<li>Создать несколько веб страниц</li>
<li>Научиться форматированию элементов при помощи стилей</li>
<li>Поэкспериментировать с классами, формами, кнопками, меню и т.д.</li>
</ul>

<p></p>

<h1 align = "center">Решение</h1>

<p>Для выполнения этой лабораторной работы, я пользовалась лекционным материалом и интернет-ресурсами для поиска решений задач оформления и для поиска медиаресурсов:</p>

<ul>
<li><a href="https://youtube.com/">YouTube</a></li>
<li><a href="https://stackoverflow.com/">Stack Overflow</a></li>
</ul>

<p>Создание меню:</p>
<code>header {
	position: fixed;
	width: 100%;
	z-index: 1;
	border-bottom: 8px solid #3b2270;
}
header ul {
	list-style: none;
	background: #47228c;
}
header ul li {
	display: inline-block;
	position: relative;
}
header ul li a {
	display: block;
	padding: 20px 25px;
	text-decoration: none;
	text-align: center;
	color: white;
	font-size: 24px;
}
header ul li ul.dropdown li {
	display: block;
}
header ul li ul.dropdown {
	width: 100%;
	background: #4c228c;
	position: absolute;
	z-index: 1;
	display: none;
}
header ul li a:hover {
	background: #2f1166;
}
header ul li:hover ul.dropdown {
	display: block;
}</code>
</br></br>
<p>Стилизация таблицы:</p>
<code>table {	
	border-collapse: collapse;
	background-size: cover;
	text-shadow: 2px 2px gray;
	background-image: url("https://github.com/albinalee/lab3/blob/main/dog.jpg?raw=true");
}
tr:nth-child(even) {
	background-color: rgba(255, 255, 255, 0.4);
}
tr:nth-child(odd) {
	background-color: rgba(202, 196, 196, 0.7);
}
th {	
	color: white;
	background-color: #573661;
}
th, td {
	font-size: 24px;
	text-align: center;
	padding: 15px 80px;
	border: 1px solid black;
}</code>
</br></br>
<p>Создание анимации:</p>
<code>.Flash {
	margin: 30px 0;
	color: red;
	font-size: 40pt;
	font-weight: bold;
	text-align: center;
	animation: flash linear 1.2s infinite;
	text-shadow: 2px 2px gray;
}
@keyframes flash {
	0%{opacity: 1;}
	50%{opacity: 0.1;}
	100%{opacity: 1;}</code>
<h1 align = "center">Вывод</h1>
<p>В результате проделанной лабораторной работы, я познакомилась с новыми элементами языка html, потренировалась в написании стилей и более сложных структур разметки.</p>
