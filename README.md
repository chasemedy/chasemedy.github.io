<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team Temu</title>
    <style>
        body {
            background-image: url('minecraft.webp');
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-position: center;
            font-family: Helvetica;
        }

        .page-border {
            border: 10px solid black;
            padding: 10px;
            margin: 10px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
        }

        .tabs {
            display: flex;
            justify-content: center;
            cursor: pointer;
            margin-bottom: 20px;
            border-radius: 15px
        }

        .tab {
            padding: 10px 20px;
            border: 1px solid black;
            background-color: ghostwhite;
            margin: 0 5px;
            border-radius: 15px
        }

        .tab.active {
            background-color: burlywood;
        }

        .tab-content {
            display: none;
        }

        .tab-content.active {
            display: block;
        }

        .myDiv {
            border: 15px outset burlywood;
            background-color: ghostwhite;
            text-align: center;
            padding: 10px;
            display: inline-block;
            vertical-align: top;
            margin: 10px;
            width: 240px;

        }

        .container {
            text-align: center;
        }

        .myDiv img {
            width: 200px;
            height: 150px;
            object-fit: cover;
            border: 3px solid black;
            border-radius: 15px
        }

        h1.team-temu {
            border: 5px solid black;
            padding: 10px;
            display: inline-block;
            background-color: ghostwhite;
            border-radius: 15px
        }

        .myDiv iframe {
            width: 200px;
            height: 150px;
            border: 5px solid #333;
            margin-top: 10px;
            border-radius: 15px
        }
    </style>
    <script>
        function showTab(tabId) {
            var tabs = document.getElementsByClassName('tab');
            var contents = document.getElementsByClassName('tab-content');

            for (var i = 0; i < tabs.length; i++) {
                tabs[i].classList.remove('active');
            }
            for (var i = 0; i < contents.length; i++) {
                contents[i].classList.remove('active');
            }

            document.getElementById(tabId).classList.add('active');
            event.currentTarget.classList.add('active');
        }
    </script>
</head>

<body>
    <div class="page-border">
        <div class="container">
            <a href="home.html">
                <h1 class="team-temu">Team Temu</h1>
            </a>
        </div>
        <div class="tabs">
            <div class="tab active" onclick="showTab('games')">Games</div>
            <div class="tab" onclick="showTab('movies')">Movies</div>
        </div>
        <div id="games" class="tab-content active">
            <div class="container">
                <div class="myDiv">
                    <a href="https://www.crazygames.com/game/hobo">
                        <h2>Hobo</h2>
                        <img src="Hobo.jpeg" alt="HomelessMan">
                    </a>
                    <iframe src="https://www.youtube.com/embed/45Mje_OJhvU" title="Hobo Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://www.hoodamath.com/games/run2.html#gsc.tab=0">
                        <h2>Run 2</h2>
                        <img src="run2.jpeg" alt="Run2Game">
                    </a>
                    <iframe src="https://www.youtube.com/embed/RE9R9pdVdfM" title="Run 2 Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://en.gameslol.net/plants-vs-zombies-69.html">
                        <h2>Plants Vs Zombies</h2>
                        <img src="PvZ.jpeg" alt="PVZGame">
                    </a>
                    <iframe src="https://www.youtube.com/embed/XENla8M3910" title="Plants Vs Zombies Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://education.minecraft.net/en-us/quick-start">
                        <h2>Minecraft</h2>
                        <img src="minecraft.jpeg" alt="Minecraft">
                    </a>
                    <iframe src="https://www.youtube.com/embed/bsEuAPP3LIA" title="Minecraft Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://fireboyand-watergirl.com">
                        <h2>Fireboy and Watergirl</h2>
                        <img src="fireboy.jpeg" alt="FBWG">
                    </a>
                    <iframe src="https://www.youtube.com/embed/og0inOdAh8w"
                        title="Fireboy and Watergirl Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://www.disney--games.com/miley_s_malibu_manicure_299.html">
                        <h2>Hannah Montana</h2>
                        <img src="Emilomo 1.jpg" alt="Hannah">
                    </a>
                    <iframe src="https://www.youtube.com/embed/0FIsPgqbBWg" title="Hannah Montana Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://www.numuki.com/game/my-scene-beauty-studio/">
                        <h2>My Scene Beauty Studio</h2>
                        <img src="Emilomo 2.png" alt="Barbie">
                    </a>
                    <iframe src="https://www.youtube.com/embed/6ejmD8LtURY"
                        title="My Scene Beauty Studio Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://amongusplay.online/">
                        <h2>Among Us</h2>
                        <img src="AmongUs.jpeg" alt="Sus">
                    </a>
                    <iframe src="https://www.youtube.com/embed/8a5Z1Idf-Jo" title="Among Us Trailer"></iframe>
                </div>
            </div>
        </div>
        <div id="movies" class="tab-content">
            <div class="container">
                <div class="myDiv">
                    <a href="https://sflix.to/movie/free-cars-hd-19334">
                        <h2>Cars</h2>
                        <img src="newcarspic.jpeg" alt="Best Movie">
                    </a>
                    <iframe src="https://www.youtube.com/embed/W_H7_tDHFE8" title="Cars Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://www.imdb.com/title/tt4154756/">
                        <h2>Rio</h2>
                        <img src="rio2.png" alt="Bird">
                    </a>
                    <iframe src="https://www.youtube.com/embed/P1GRO31ve5Q" title="Rio Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://www.tokyvideo.com/video/walle-2008">
                        <h2>Wall-E</h2>
                        <img src="wallE.png" alt="Wall-E">
                    </a>
                    <iframe src="https://www.youtube.com/embed/alIq_wG9FNk" title="Wall-E Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://sflix.to/watch-movie/free-monsters-inc-hd-19514.5349247">
                        <h2>Monster Inc.</h2>
                        <img src="monsters.jpeg" alt="Monster INC.">
                    </a>
                    <iframe src="https://www.youtube.com/embed/6tCxnHCqqxg" title="Monster INC. Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://www.imdb.com/title/tt0110912/">
                        <h2>The Incredibles</h2>
                        <img src="incredibles.png" alt="The Incredibles">
                    </a>
                    <iframe src="https://www.youtube.com/embed/-UaGUdNJdRQ" title="The Incredibles Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://www.imdb.com/title/tt1375666/">
                        <h2>Kung Fu Panda</h2>
                        <img src="kungfupanda.jpeg" alt="Kung Fu Panda">
                    </a>
                    <iframe src="https://www.youtube.com/embed/siLm9q4WIjI?si=PzBbjKsb7teLja-c"
                        title="Kung Fu Panda Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://www.imdb.com/title/tt7286456/">
                        <h2>Finding Nemo</h2>
                        <img src="findingnemo.webp" alt="Finding Nemo">
                    </a>
                    <iframe src="https://www.youtube.com/embed/9oQ628Seb9w?si=TBsyouIoesMe5eYx"
                        title="Finding Nemo Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://www.imdb.com/title/tt0468569/">
                        <h2>The Dark Knight</h2>
                        <img src="darkknight.jpeg" alt="The Dark Knight">
                    </a>
                    <iframe src="https://www.youtube.com/embed/EXeTwQWrcwY" title="The Dark Knight Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://www.imdb.com/title/tt0110357/">
                        <h2>The Lion King</h2>
                        <img src="lionking.jpeg" alt="The Lion King">
                    </a>
                    <iframe src="https://www.youtube.com/embed/4sj1MT05lAA" title="The Lion King Trailer"></iframe>
                </div>
                <div class="myDiv">
                    <a href="https://www.imdb.com/title/tt0848228/">
                        <h2>High School Musical 2</h2>
                        <img src="hsm2.webp" alt="High School Musical2">
                    </a>
                    <iframe src="https://www.youtube.com/embed/zL4ZEWYsmuw?si=9GbaL8hCIPlL54pL"
                        title="High School Musical Trailer"></iframe>
                </div>
            </div>
        </div>
    </div>
</body>

</html>
