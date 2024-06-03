<script>
 
</script>

<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

<div class=container>

    <div class="profile">
        <img src=https://www.shutterstock.com/image-vector/vector-flat-illustration-grayscale-avatar-600nw-2281862025.jpg alt="Profile Picture">
    </div>

    <div class="header-content">
        <h1 class="title">Gabriel News Plus+</h1>
    </div>

    <div class="log-in">
        <p>Vill du logga ut? <a href="/page">Logga ut</a></p>
        <p id="profile-name"></p>
    </div>

    
    <div class=layout>

        <div class=news-item>
            <h2>Gabriel Motor Company tvingas återkalla sin nya bilmodell Gabbe Turbo efter ett fel på ratten, Experten:"Det är lätt hänt"</h2>
            <img src=https://upload.wikimedia.org/wikipedia/commons/thumb/5/54/Folkevogn-2001.jpg/640px-Folkevogn-2001.jpg alt="News Image">
            <p><a href="/nyhet 1">Läs mer</a></p>
        </div>

        <div class=news-item>
            <h2>Gabbe IK vinner Champions League efter straffläggning i finalen, Messi:"Dom var bättre än Barcelona 2009 i år"</h2>
            <img src=https://editorial.uefa.com/resources/025f-0fe0cd7f0734-a5aa8cb0c77f-1000/fbl-eur-c1-draw.jpeg alt="News Image">
            <p><a href="/nyhet 2">Läs mer</a></p>
        </div>

        <div class=news-item>
            <h2>Gabriel Industries ökade med 40% på börsen efter en strålande rapport</h2>
            <img src=https://static.vecteezy.com/ti/gratis-foton/p2/4631055-foretag-ljusstake-diagram-diagram-over-aktiemarknadsinvesteringar-handel-pa-bakgrundsdesign-trend-pa-aktiegraf-marknadsbors-finansiell-ekonomi-koncept-gratis-fotona.JPG alt="News Image">
            <p><a href="/nyhet 3">Läs mer</a></p>
        </div>

        <div class=news-item>
            <h2>Bostadspriserna i Gabrielköping når nya rekordhöjder</h2>
            <img src= https://image.freepik.com/free-photo/soccer-ball-golden-cup-isolated-on-blue-background_1150-39547.jpg alt="News Image">
            <p><a href="/nyhet 4">Läs mer</a></p>
        </div>

        <div class=news-item>
            <h2>Det väntas bli mycket regnigt i Gabrilonien de kommande dagarna, Meterologen:"Risk för översvämmning"</h2>
            <img src=https://static.bonniernews.se/gcs/bilder/dn-mly/40e606f6-22fe-4f06-84bf-1abdbd7f7623.jpeg alt="News Image">
            <p><a href="/nyhet 5">Läs mer</a></p>
        </div>

        <div class=news-item>
            <h2>Byggnationen av Gabriel Tower kommer att vara färdig i år</h2>
            <img src=https://media.architecturaldigest.com/photos/6526cfff484a2bd295861382/16:9/w_1280,c_limit/E02-1-1024x683.jpg alt="News Image">
            <p><a href="/nyhet 6">Läs mer</a></p>
        </div>

    </div>

</div> 

<style>
    .container{
        width:93vw;
        height:182vh;
        background-color:yellow;
        padding-top:10px;
        padding-left:10px;
        padding-right:10px;
        border-width:10px;
        border-color:green;
        border-style: groove;
    }
    .profile {
        position: absolute;
        top: 85px;
        left: 40px;
        display: flex;
        align-items: center;
        font-size: 1rem;
    }

    .profile img {
        width: 70px;
        height: 70px;
        border-radius: 50%;
        margin-right: 10px;
    }
    .header-content {
        display: flex;
        padding-left:310px;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }
    .layout{
        display: grid;
        grid-template-columns: 1fr 1fr; 
        gap: 20px; 
    }
    .news-item {
        background-color:antiquewhite; 
        padding:30px;
        padding-bottom:5px;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        font-size: 1rem;
    }
    .subscribe-button {
        background-color: #007bff;
        color: white;
        border: none;
        border-radius: 5px;
        padding: 8px 16px;
        cursor: pointer;
        text-decoration: none;
    }

    .subscribe-button:hover {
        background-color: #0056b3;
        text-decoration: none;
    }
    .log-in { 
        border-radius: 8px;
        margin-bottom: 20px; 
        padding-left: 655px;
    }

    .log-in p {
        text-align: center; 
        font-size: 1rem; 
    }

    .log-in a {
        color: blue; 
        text-decoration: none; 
    }

    .log-in a:hover {
        text-decoration: underline; 
    }

    h2 {
        margin-bottom: 10px;
        text-align: center;
        font-size: 1.2rem;
        padding-top:0px; 
    }
    .title {
        text-align: center;
        font-size:2.5rem;
        font-family: 'Roboto', sans-serif; 
    }
    p {
        text-align: center;
    }

    a {
        color: blue;
        text-decoration: none;
    }

    a:hover {
        text-decoration: underline;
    }
    img {
        width: 100%;
        max-width: 380px; 
        height: 150px; 
        border-radius: 8px; 
        margin-bottom: 15px; 
    }
</style>
