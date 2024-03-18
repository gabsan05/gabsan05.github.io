<div class="container">

    <h1>TODO LIST</h1>
    <h2>Uppgifter <input type="text"><button type="submit">Lägg till</button></h2>

    <div class="layout">

        <div style="display:grid">
        <h1>NEW</h1>

        <ol>
            <li>sak</li>
            <li>sak2</li>
        </ol>

        </div>

        <div style="display:grid">
        <h1>COMPLETED</h1>

        <ol>
            <li>sak</li>
            <li>Ett annat list objekt</li>
        </ol>

        </div>

    </div>

    </div>

<style>
    .container{
        width:80vw;
        height:70vh;
        background-color:gray;
        padding-top:10px;
        padding-left:10px;
        border-width:10px;
        border-color:black;
        border-style: groove;
    }
    .layout{
        display: grid;
        grid-template-columns: 50% 50%;
    }
</style>
