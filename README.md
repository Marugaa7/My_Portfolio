create one readme file for these                                                                             
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
       <title>
        My Portfolio
       </title>
       <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header>
            <h1>
                HELLO!
            </h1>
            <p> Hi there! I'm Ian 😀 and this is my Portifolio Website.
                I'm really exited to show you me 😂.
            </p>
        </header>
        <main>
        <section id="About">
            <h2>About Me</h2>
            <p>My name Ian Marugaa, a student at PLP cohort 2025. 

            </p>
        
        </section>
        <section id="education">
            <h2>Education Background</h2>
            <p>I completed my highschool in 2023 from Friends School Kamusinga where I did my KCSE.
                Thereafter, I enrolled at the University of Nairobi tu pursue Bachelor o medicine and surgery.
                Here is my cv
                 
            </p>
             <a href="My cv.pdf" download>Download my cv</a>
          
        </section>
            
        <section id="skills">
                <h2>Programming languages</h2>
                <p>I am proficient in the following languages:</p>
                <ul>
                    <li>HTML</li>
                    <li>Python</li>
                    <li>CSS</li>
                </ul>
        </section>
        <section id="interests">
            <h2>Interests</h2>
           <p>I enjoy coding, exploring AI and learning  new tech tools. 
            Other than those I'm also a lover of self help books and I also
             really enjoy playong chess
            </p> 
        </section>
        
        <section id="projects">
            <h2>Projects</h2>
            <p>I've done several projects some of which are listed below:</p>
            <ul>
                <li><a href="https://github.com/Marugaa7/Basic-Calculator" target="_blank">A basic Python Calculator</a></li>
                <li><a href="https://github.com/Marugaa7/Youtube-Prototype" target="_blank">My Youtube Proto</a></li>
                
            </ul>

        </section>
        
            <h3>contact me</h3>
            <form><input type="text" placeholder="Your Name"> <br>
            <input type="text" placeholder="Email Address"> <br>
            <textarea name="" id="" placeholder="Write your message here"></textarea><br>
            <button type="submit">Send</button>
        </form>
        </section>
    
        
        </main>
        <footer> &copy; 2025 All Rights Reserved. Ian Marugaa
        </footer>
    </body>
</html>                                                                                                                                            css body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: rgb(230, 245, 255);
    color: rgb(51, 51, 51);
    line-height: 1.6;
    
    font-size: 16px;
    
}
p {
    margin: 8px 0;
    padding: 5px;
}
header{
    
    color: rgb(38, 50, 80);
    text-align: center;
    padding: 20px;
    margin-bottom: 2px;
}
/* Headings */
h1, h2 {
    color: rgb(230, 245, 255);
}
/* links */
a { color: rgb(0, 119, 182);}

a:hover {color: navy;}



/* Buttons */
button{
    color: ;
    padding: 7px 15px;

    border-radius: 2px;
    cursor: pointer;
    border-color: rgb(192, 192, 192);
    margin-bottom: 7px;
    
}


button:hover{ background-color: gray;}
form{width: 200px;}

textarea{max-width: 350px;
    max-height: 200px;
    min-width: 200px;
    min-height: 50px;
} 

input, textarea {
    width: 100%;
    padding: 3px;
    margin: 3px;
    border-color: rgb(204, 204, 204);
}
 footer{background-color: rgb(93, 117, 129);
color: white;
text-align: center;}
