# digital-portfolio

<!DOCTYPE html>
<html>
    <head>
        <title>PORT FOLIO</title>
        <link rel="stylesheet" href="port folio.css">
    </head>
    <body>
         <header>
            <div class="headercontent">
                <img src="photo kiruthi.jpg" alt="your profile pic" class="my-pic">
                <h1>Kiruthika T</h1>
                <h5>final year Computer science student</h5>
            </div>
         </header>
         <nav>
        <ul>
            <li><a href="#about">About </a> </li>             
            <li><a href="#edu">Education </a> </li>
            <li> <a href="#hskill">Hard Skills</a> </li>
            <li><a href="#sskill">Soft Skills</a> </li>
        </ul>
         </nav>
         <section id="About">
            <div class="section">
                <h2>About myself</h2>
                <p>hello everyone! this is Kiruthika T. i am final year computer science student.</p>
            </div>
         </section>
         <section id="edu">
            <div class="section">
                <h2>B.Sc..,</h2>
                <p>bharathiar university</p>
            </div>
         </section>
         <section id="hskill">
            <div class="section">
                <h2>Hard Skills</h2>
                <ul>
                    <li>MS Office</li>
                    <li>HTML and CSS</li>
                    <li>SQL</li>
                </ul>
            </div>
         </section>
         <section id="sskill">
            <div class="section">
                <h2>Soft Skills</h2>
                <ul>
                    <li>Communicatin skill</li>
                    <li>Team WOrk</li>
                    <li>Leadership</li>
                </ul>
            </div>
         </section>
        <style>
            body{
    margin: 0;
    padding: 0;
    background-image: linear-gradient(blue,purple,red, yellow);
}
header{
    background-color: rgb(43, 39, 39);
    color: white;
    text-align: center;
    padding: 1rem 0;
    position: relative;
    
}
.my-pic{
    width: 90px;
    height: 90px;
    border-radius: 75%;
    object-fit: cover;
    position: absolute;
    /* top: 55px; */
    left: 85px; 
}
nav{
    background-color: rgb(39, 26, 26);
    color: white;
    text-align: center;
}
nav ul{
   list-style-type: none;
   padding: 0;
}
nav ul li{
    display: inline;
    margin: 0 20px;
}
nav ul li a{
    color: white;
}

.section{
    background-color: beige;
    padding: 2rem;
    margin: 2rem;
    border-radius: 20px;
    box-shadow: 5px 5px 5px silver;
}
</style>
         <footer>
            <center>
            <p>&copy; 2023 Kiruthika T</p>
        </center>
         </footer>
    </body>
</html>
