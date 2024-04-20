# MT-exam
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>Resume/ Resume</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css"/>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
    <div class="nav">
    <button id="cmd" onclick="printpdf()" class="navbtn"><i class="fas fa-download"></i></button>
    <form>
    <input type="hidden" id="custinfo" name="custinfo">
    <button class="navbtn"><i class="fas fa-save"></i></button>
    </form>
    <button class="navbtn" href=""><i class="fas fa-home"></i></button>
    </div>

    <div class="resume" id="resume">
        <section id="print">
             <div class="head">
                <div class="main">
                    <span class="name" contenteditable="true">JOHNRAY A. PERALTA</span> 
                    <div class="post" contenteditable="true">WEB DEVELOPER</div>
                </div>
                <div class="contacts">
                <span contenteditable="true" class="content">09275803869</span><span class="symbol"> <i class="fas fa-phone"></i></span><br>
                <span contenteditable="true" class="content">johnrayperalta22@gmail.com</span><span class="symbol"> <i class="fas fa-envelope"></i></span><br>
                <span contenteditable="true" class="content">Turod Narvacan Ilocos Sur</span><span class="symbol"> <i class="fas fa-map-marker-alt"></i></i></span>
                </div>
            </div>

            <div class="line"></div>
            <div class="mainbody">
                <div class="leftside">
                <span class="title">MY SKILLS</span><br><br><div>
                <div class="skill"><span><input type="checkbox" class="input-checkbox"></span><span><i class="fas fa-chevron-circle-right"></i></span>   <span contenteditable="true">write your skill here</span></div>
                <div id="skills"></div>
                <button id="skilladd" type="button" class="btn btn-success" onclick="addskill()"><i class="fas fa-plus-circle"></i> Skill</button>
                
                <button id="langrem" type="button" class="btn btn-danger" onclick="remLang(event)"><i class="fas fa-minus-circle"></i> Language</button></div>
                <br><br><span class="title">ACHIEVEMENTS</span><br><br><div>
                <div class="achieve" ><span><input type="checkbox" class="input-checkbox"></span><span contenteditable="true">Write your achievement</span></div>
                <div id="achievement"></div>
                <button id="achadd" type="button" class="btn btn-success" onclick="addAch()"><i class="fas fa-plus-circle"></i> Achievement</button>

                <button id="achrem" type="button" class="btn btn-danger" onclick="remAch(event)" style="margin-top: 0;"><i class="fas fa-minus-circle"></i> Achievement</button></div>
                <br><br><span class="title">INTERESTS</span><br><br><div>
                <div class="achieve" ><span><input type="checkbox" class="input-checkbox"></span><span contenteditable="true">Write interest</span></div>
                <div id="interest"></div>
                <button id="Intadd" type="button" class="btn btn-success" onclick="addInt()"><i class="fas fa-plus-circle"></i> Interest</button>

                <button id="Intrem" type="button" class="btn btn-danger" onclick="remInt(event)"><i class="fas fa-minus-circle"></i> Interest</button></div>
                </div>

            
                <div id="Trainings">
                    <div class="edublock">
                        <span><input type="checkbox" class="input-checkbox"></span>
                        <span class="education-head" contenteditable="true">Trainings</span>
                        <div ><span contenteditable="true">Write Training or Seminar</span> 
                    </div>
                </div>

                <button id="eduadd" type="button" class="btn btn-success" onclick="addedu()"><i class="fas fa-plus-circle"></i> Education</button>

                <button id="edurem" type="button" class="btn btn-danger" onclick="remedu(event)"><i class="fas fa-minus-circle"></i> Education</button></div>
                <br><br>
            </div>
            </div>
        </section>
     </div>
    </body>

</html>
