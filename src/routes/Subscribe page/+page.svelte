<div class=container>

    <h1 class=title>Gabriel News!</h1>
    
    <div class=layout>

        <h2>Bli prenumerant idag på Gabriel News Plus för endast 59kr/månad!</h2>

        <form action="pageprem" method="GET">
            <label for="email">E-mail</label>
            <input id="email" type="email" name="email" placeholder="Ange din e-postadress" required>
            <label for="password">Lösenord</label>
            <input id="password" type="password" name="password" placeholder="Välj ditt lösenord" required>
            <button type="submit">Bli prenumerant</button>
        </form>


    </div>

    <div class=layout>

        <h3>Med Gabriel News plus får du tillgång till exklusiva och saftiga nyhter som du annars inte skulle kunna ta del av.</h3>

    </div>

    <p><a href="page">Tillbaka till huvudsidan</a></p>
</div>

<style>
    .container{
        width:95vw;
        height:85vh;
        background-color:red;
        padding-top:10px;
        padding-left:10px;
        border-width:10px;
        border-color:yellow;
        border-style: groove;
    }
    .layout{
        text-align:center;
        background-color: white;
        padding-bottom: 20px;
        padding-top: 10px;
    }
    .title{
        text-align:center;
    }
    button {
        width: 150px;
        padding: 10px;
        background-color: #007bff;
        color: white;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        transition: background-color 0.3s ease;
    }

    button:hover {
        background-color: #0056b3;
    }
    input[type="text"],
    input[type="email"],
    input[type="password"] {
        width: 250px;
        padding: 8px;
        margin-bottom: 10px;
        border: 1px solid #ccc;
        border-radius: 4px;
        box-sizing: border-box;
    }
    p {
        text-align: center;
    }

    a {
        color: blue;
        text-decoration: none;
    }
</style>
