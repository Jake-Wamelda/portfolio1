body {
    background-size: 100% 100vh;
    font-family: Inter, sans-serif;
    background-color: whitesmoke;
}

/*
    HEADER
*/

header {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
}

.about-me, .resume, .projects, .contact {
    color: black;
    margin: 20px;
    font-weight: bold;
}

a:link {
    text-decoration: none;
}

/*
    General
*/

.fade-in-content {
    animation: fadeInAnimation ease 2s;
    animation-iteration-count: 1;
    animation-fill-mode: forwards;
}

@keyframes fadeInAnimation {
    0% {
        opacity: 0;
        transform: translate3d(0, 20px, 0);
    }
    100% {
        opacity: 1;
    }
}

/*
    index.html
*/

h1, h2, .description {
    position: relative;
    margin: 10px;
    left: 948px;
    top: 200px;
}

h1 {
    width: 246px;
    height: 117px;
    font-size: 100px;
}

h2 {
    width: 216px;
    height: 25px;
}

.description {
    width: 371px;
    height: 94px;
    top: 220px;
}

.pfp{
    position: absolute;
    display: flex;
    width: 378px;
    height: 366px;
    object-fit: fill;
    left: 536px;
    top: 180px;
    border-radius: 183.5px;
    scale: 100%;
}

.button1, .button2, .button3 {
    position: relative;
    font-size: 16px;
    left: 900px;
    top: 220px;
    width: 113px;
    height: 110px;
    cursor: pointer;
    border-radius: 50%;
    margin: 10px;
    font-weight: bold;
    border: 2px solid black;
}

.button1{
    background-color: #EEA302;
    transition: background-color 0.5s;
}

.button2 {
    background-color: #FF3B25;
    transition: background-color 0.5s;
}

.button3 {
    background-color: #80D8DA;
    transition: background-color 0.5s;
}
.button1:hover, .button2:hover, .button3:hover {
    background-color: whitesmoke;
}

/*
    FOOTER
*/

footer hr {
    position: relative;
    display: flex;
    width: 95%;
    top: 850px;
}

.phone, .email, .socials {
    position: relative;
    width: 393px;
    height: 97px;
    font-size: 12px;
}

.phone {
    left: 200px;
    top: 880px;
}

.email {
    left: 900px;
    top: 767px;
}

.socials {
    width: 75px;
    left: 1600px;
    top: 652px;
}

.ig_logo, .x_logo {
    position: relative;
    margin: 3px;
    width: 18px;
    height: 18px;
    left: 10px;
}

/*
    General
*/

.bold_text {
    font-weight: bold;
}

.page-head {
    position: relative;
    left: 207px;
    top: 80px;
    font-size: 42px;
}

/*
    resume.html
*/

.section1 {
    position: relative;
    left: 207px;
    top: 126px;
    font-size: 26px;
}

.separator1 hr{
    position: relative;
    display: flex;
    width: 95%;
    top: 400px;
}

.separator2 hr{
    position: relative;
    display: flex;
    width: 95%;
    top: 600px;
}

.sy1 {
    position: relative;
    width: 500px;
    left: 853px;
    top: 167px;
}
    

.sy2 {
    position: relative;
    width: 500px;
    left: 1016px;
    top: 130px;
}

.sy3 {
    position: relative;
    width: 500px;
    left: 852px;
    top: 290px;
}

.sy4 {
    position: relative;
    width: 500px;
    left: 1016px;
    top: 255px;
}

.section2 {
    position: relative;
    left: 207px;
    top: 446px;
    font-size: 26px;
}

.section3 {
    position: relative;
    left: 207px;
    top: 640px;
    font-size: 26px;
}

ul {
    width: 800px;
}

ul li{
    margin: 20px;
    width: 800px;
}

.skills {
    position: relative;
    top: 500px;
    left: 852px;
    width: 800px;
}

.awards {
    position: relative;
    top: 750px;
    left: 852px;
    width: 800px;
}

.awards ul li {
    margin: 50px;
}

.attendance p, .dl p {
    position: relative;
    font-weight: bold;
    left: 150px;
}

/*
    contact.html
*/

.lf {
    position: relative;
    left: 220px;
    width: 291px;
}

.contact-phone p{
    position: relative;
    margin: 7px;
    top: 50px;
    left: 215px;
    width: 138px;
}

.contact-email p{
    position: relative;
    margin: 7px;
    top: 79px;
    left: 215px;
    width: 138px;
}

.input-container1 {
    display: flex;
    position: relative;
    left: 1050px;
    top: -120px;
    width: 215px;
}

.input-container2 {
    display: flex;
    position: relative;
    left: 1050px;
    top: -61px;
    width: 215px;
}

.input-container3 {
    display: flex;
    position: relative;
    left: 1050px;
    top: -2px;
    width: 215px;
}

.fname-input p, .lname-input p, .email-input p, .subject-input p, .message-input p{
    margin: 2px 31px;
}

input[type='text'] {
    height: 45px;
    font-family: Inter, sans-serif;
    padding: 3px 3px 3px 7px;
    font-size: 16px;
    margin: 0px 31px;
}

.message-input input[type='text'] {
    width: 300px;
    height: 141px;
}

.submit-button {
    position: relative;
    font-size: 16px;
    width: 155px;
    height: 155px;
    cursor: pointer;
    border-radius: 50%;
    font-weight: bold;
    border: 2px solid black;
    left: 1448px;
    top: -150px;
}

.submit-button {
    background-color: #EEA302;
    transition: background-color 0.5s;
}

.submit-button:hover {
    background-color: whitesmoke;
}

/*
    project.html
*/

.project1 {

}

.project2 {
    
}

.project1 h3, .project2 h3{
    font-size: 26px;
}

.project1 p, .project2 p{
    width: 645px;
    height: 75px;
}
