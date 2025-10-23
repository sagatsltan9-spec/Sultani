<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Қуандық Шаяхметов</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
            color: #333;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1 {
            color: #2E8B57;
        }
        img {
            max-width: 300px;
            border-radius: 10px;
            margin: 20px auto;
            display: block;
        }
        button {
            background: #2E8B57;
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 20px;
        }
        button:hover {
            background: #236B47;
        }
        .bio {
            text-align: left;
            line-height: 1.6;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Қуандық Шаяхметов</h1>
    <img src="https://adebiportal.kz/images/portraits/6/6_20201119150012.jpg" alt="Қуандық Шаяхметов">

    <div class="bio">
        <h2>Өмірбаяны</h2>
        <p><strong>Туған жылы:</strong> 1928 жыл, Алматы облысы</p>
        <p><strong>Қайтыс болған жылы:</strong> 1992 жыл</p>
        <p><strong>Ұлты:</strong> Қазақ</p>
        <p><strong>Мамандығы:</strong> Суретші, график</p>

        <h2>Білімі</h2>
        <p>1953 жылы Алматы көркемсурет училищесін бітірген. 1960 жылы Мәскеудегі В.И. Суриков атындағы көркемсурет институтын тәмамдаған.</p>

        <h2>Шығармашылығы</h2>
        <p>Қуандық Шаяхметов - қазақ графика өнерінің негізін салушылардың бірі. Ол кітап графикасы, плакат, станоктық графика саласында еңбек етті.</p>
    </div>

    <button onclick="window.location.href='works.html'">Еңбектерін көру</button>
</div>

</body>
</html><!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Шаяхметов еңбектері</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1 {
            color: #2E8B57;
            text-align: center;
        }
        button {
            background: #2E8B57;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin: 10px 0;
        }
        .work-item {
            background: #f9f9f9;
            padding: 15px;
            margin: 10px 0;
            border-left: 4px solid #2E8B57;
            text-align: left;
        }
        .works-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Қуандық Шаяхметовтың еңбектері</h1>

    <div class="works-container">
        <div class="work-item">
            <h3>"Абай жолы" графикалық сериясы (1970)</h3>
            <p>Абай Құнанбаев шығармалары бойынша жасалған графикалық цикл</p>
        </div>

        <div class="work-item">
            <h3>"Қазақтың тарихи тұлғалары" портреттер сериясы</h3>
            <p>Қазақстан тарихының маңызды тұлғаларына арналған графикалық портреттер</p>
        </div>

        <div class="work-item">
            <h3>Кітап илюстрациялары</h3>
            <p>Қазақ жазушыларының кітаптарына жасалған илюстрациялар</p>
        </div>

        <div class="work-item">
            <h3>"Ел тарихы" графикалық циклі</h3>
            <p>Қазақ халқының тарихи оқиғаларына арналған шығармалар</p>
        </div>

        <div class="work-item">
            <h3>Плакаттар</h3>
            <p>Әлеуметтік және мәдени тақырыптардағы плакаттар</p>
        </div>

        <div class="work-item">
            <h3>Станоктық графика</h3>
            <p>Әр түрлі техникада орындалған станоктық графикалық жұмыстар</p>
        </div>
    </div>

    <button onclick="window.location.href='index.html'">Негізгі бетке оралу</button>
</div>

</body>
</html>
