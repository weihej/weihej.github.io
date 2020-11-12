<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css">
    <title>Visitenkarte Janina Weihe</title>
</head>

<style>
    .card {
        position: relative;
        height: 440px;
        width: 300px;
        background-color: #124257;
        margin: 60px auto;
    }
    
    .header {
        position: absolute;
        height: 240px;
        left: 0;
        right: 0;
        top: 0;
    }
    
    .header img {
        position: absolute;
        height: 150px;
        width: 120px;
        border-radius: 50%;
        left: 90px;
        top: 15px;
    }
    
    .header h3 {
        position: absolute;
        font-family: sans-serif;
        color: rgb(236, 233, 233);
        font-size: 17px;
        font-weight: 400;
        letter-spacing: 1px;
        top: 155px;
        left: 90px;
    }
    
    .header p {
        position: absolute;
        font-family: sans-serif;
        color: rgb(236, 233, 233);
        font-size: 10px;
        top: 190px;
        left: 50px
    }
    
    .body {
        position: absolute;
        height: 130px;
        left: 5px;
        right: 5px;
        top: 52%;
        background-image: linear-gradient(to right, #e2e1e1, #ecf0f1);
        background-color: rgb(236, 233, 233);
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
    
    .body ul {
        position: absolute;
        left: 0;
        right: 0;
        top: 0;
    }
    
    .body ul li {
        position: absolute;
        list-style: none;
        height: 20px;
        width: 100%;
        left: 0;
        right: 50;
    }
    
    .body ul li p,
    h3,
    i {
        position: absolute;
    }
    
    .body ul h3 {
        top: -16px;
        left: 18px;
        font-size: 12px;
        font-family: sans-serif;
        color: #576574;
    }
    
    .body ul li p {
        top: 6px;
        left: 18px;
        font-size: 10px;
        font-family: sans-serif;
        color: #576574;
    }
    
 
    
    
    .footer {
        position: absolute;
        height: 70px;
        bottom: 0;
        left: 0;
        right: 0;
        background-image: linear-gradient(to right, #e2e1e1, #ecf0f1);
    }
    
    .footer ul {
        position: absolute;
        height: 45px;
        bottom: 0;
        right: 0;
        left: -30px;
    }
    
    .footer ul li {
        display: inline-block;
        margin-left: 60px;
    }
    
    .footer ul li i {
        font-size: 30px;
        color: #7f8c8d;
        transition: all .3s ease-in;
    }
    
    .footer ul li:hover i {
        transform: scale(0.9);
        color: #124257;
        cursor: pointer;
        border-bottom: 2px solid #124257;
    }
</style>

<body>

    <div class="card">
        <div class="header">
            <img src="./Weihe,Janina.jpeg">
            <h3>Janina Weihe</h3>
            <p>M.A. Internationales Informationsmanagement</p>
        </div>

        <div class="body">
            <ul>
               <h3>Aktuelle Kurse:</h3>
                    <li>
                    <p>Aktuelle Standards, Formalisierung, Textbasierte Computational Social Science, Vorlesung 
                    Internationale Mensch-Maschine-Interaktion, Vorlesung Mehrsprachige Informationssysteme, Hauptseminar Automatische Analyse von Texten in Social Media, Projektseminar Internationale Mensch-Maschine-Interaktion, Botanik, Sustainable University Seminar</p>
                    </li>
            </ul>
        </div>

        <div class="footer">
            <ul>
                <li>
                    <i class="fab fa-facebook-f"></i>
                </li>
                <li>
                    <i class="fab fa-instagram"></i>
                </li>
                <li>
                    <i class="fab fa-linkedin-in"></i>
                </li>
                
            </ul>
        </div>

    </div>

</body>

</html>
