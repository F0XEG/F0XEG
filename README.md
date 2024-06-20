<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	  <meta charset="utf-8">
	  <title>Красивый список</title>
	  <link href='http://fonts.googleapis.com/css?family=Exo+2:400,100&subset=latin,cyrillic' rel='stylesheet' type='text/css'>
	</head>
	<body>

<style type="text/css">

      body{
        font-family: 'Exo 2', sans-serif;
      }

      ol {
        counter-reset:myCounter;
        margin-left:0;
        padding-left:5px;
        color: rgb(100,100,100);
      }

      li {
        position: relative;
        padding-left: 3em;
        margin: 0.45em 0;
        list-style: none;
        line-height: 1.8em;
        cursor: pointer;
        -webkit-transition: all 0.2s ease-in-out;
        transition: all 0.2s ease-in-out;
      }

      li:hover {
        color: rgb(0,0,0);
      }

      li:before {
        content:counter(myCounter);
        counter-increment:myCounter;
        position:absolute;
        top:0;
        left:0;
        width: 1.8em;
        height: 1.8em;
        line-height: 1.8em;
        padding:0px;
        color:#fff;
        background:#2980b9;
        font-weight:bold;
        text-align:center;
        border-radius: .9em;
        box-shadow: 0px 1px 4px 0px rgba(0,0,0,0.3);
        z-index: 1;
        -webkit-transition: all 0.3s ease-in-out;
        transition: all 0.3s ease-in-out;
      }

      li:hover:before {
        background-color: #2ecc71;
      }

      li li:before{
        background-color: #3498db;
      }

      li:after {
        position: absolute;
        top: 2.1em;
        left: 0.9em;
        width: 2px;
        height: calc(100% - 2em);
        content: '';
        background-color: rgb(203, 203, 203);
        z-index: 0;
      }

      li:hover:after {
        background-color: #2ecc71;
      }

      li li {
        font-size: 0.8em;
      }

</style>

<h1>Рецепт</h1>
		<ol>
			<li>
			  В большой сковороде разогрейте растительное масло.
			</li>
			<li>
			  В большой миске смешайте ингридиенты:
			  <ol>
					<li>5 тертых картофелин</li>
					<li>2 яйца (взбить)</li>
					<li>1 луковица</li>
					<li>3 ст.л. муки</li>
					<li>соль и перец по вкусу</li>
				</ol>
			</li>

<li>
			  Выкладывайте картофельное тесто большой ложкой на сковороду и 
			  слегка прижмите оладьи лопаточкой. Жарьте примерно 4 минуты 
			  с каждой стороны, пока не подрумянятся.
			</li>
			<li>
        Сразу подавайте на стол
			</li>
		</ol>
</body>
</html>
