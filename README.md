<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Page title</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    <style>
        body{
            margin:5px;
        }
        .main{
            background-color:aliceblue;
        }
        .section{
            
            
        }
        table ,th, td {
            border: 1px solid;
            text-align:center;
        }
        th{
            background-color: #04AA6D;
            color:white;
            padding-bottom:10px;
            padding-top:10px;
        }
        table{
            width:100%;
            margin:7px 1px;
            border-collapse: collapse;
        }
        td{
            padding-top:10px;
            padding-bottom:10px;
        }
        table tr:nth-child(even){
        background-color: #f2f2f2;
        }
        .table-img{
            padding-top:10px;
            
           
        }
        .img{
            float:left;
            height:180px;
        }
        h1,h2{
            text-align:center;
        }
        h1{
            padding-top:15px;
        }
        .marq{
            background-color:#04AA6D;
            padding:2px;
            color:white;
            font-size:22px;
            border-radius:5px;
            padding-top:10px;
        }
        ul{
            list-style-type:none;
            width:100%;
            margin:0;
            padding:0;
            overflow:hidden;
            background-color:navy;
            border-radius:5px;
        }
        li{
            float:left;
            padding-right:20px;
        }
        .home{
            padding-left:9px;
        }
        li a{
            display:block;
            text-decoration:none;
            text-align:center;
            padding:15px 22.9px;
            color:white;
            font-size:19x;
        }
        li a:hover{
            background-color:red;
            color:white;
            border-radius:5px;
            text-decoration:none;
        }
        .nbkr{
            padding-top:20px;
        }
        .about{
            background-color:aliceblue;
        }
        .nbkr{
            height:500px;
        }
        .contact{
            background-color:aliceblue; 
            width:100%;
            border-radius:5px;
            align-items: center;  
        }
        @media only screen and (max-width: 768px){
            p{
                witdth:100%;
            }
            h1,h2{
                width:100%;
            }
        }
        @media only screen and (max-width: 434px){
            li a{
                padding:15px 22.7px
            }
            h1{
                text-align:center;
                padding-left:10px;
            }
        }
        @media only screen and (min-width: 375px) and (max-width:435){
            h1{
                text-align:center;
            }
            li a{
                padding:10px 5px;
                }
              }
        @media only screen and (max-width: 1440px) and (min-width:119px){
            li a{
                padding:10px 5px;
            }
            .im{
                text-align:center;
            }
        }
        
    </style>
</head>
<body>
    <div id="home">
    <div class="main">
        <p>
  <img src="https://upload.wikimedia.org/wikipedia/en/thumb/3/3d/NBKRIST_logo.png/220px-NBKRIST_logo.png" alt="" class="img" ><h1>N.B.K.R INSTITUTE OF SCIENCE AND TECHNOLOGY </h1>
  <h2>Vidyanagar<br>
  AUTONOMOUS<br>
  Affiliated to JNTUA, Ananthapuram</h2>
  </p>
  </div>
  <div class="marq">
      <marquee direction="left"><img src="https://media.tenor.com/x8buEnCiZ4MAAAAC/new-blinking.gif" alt="" height="30px" style="border-radius:50%; padding-right:5px"><b>NBKRIST MID PAPERS (New)   1-2 Mid papers available for R20   <span style="color:red">Others Papers will be updated soon.</span></b></marquee>
  </div>
  <p style=""></p>
  <div class="nav">
      <ul>
          <li class="home">
              <a href="#home"><i class="fa fa-home" style="font-size:18px;padding-right: 5px;"></i><b>Home</b></a>
          </li>
          <li>
              <a href="#about"><i style="padding-right: 5px;"class="glyphicon glyphicon-user"></i><b>About Us</b></a>
          </li>
          <li>
              <a href="#contact"><i class="fa fa-phone" style="font-size:18px;padding-right: 5px;"></i><b>Contact Us</b></a>
          </li>
    </div>
  </li>
      </ul>
      </div>
      <div>
      <img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/7b/NBKRmaingate.jpg/1280px-NBKRmaingate.jpg" style="width:100%; "class="nbkr"alt=""></img></div>
      <div class="table-img">
          <h3 style="text-align:center">DOWNLOAD PDF'S HERE</h3>
        <div class="container">
  <h2>Filterable Table</h2>
  <p>Type something in the input field to search the table for first names, last names or emails:</p>  
  <input class="form-control" id="myInput" type="text" placeholder="Search wih subject...." onkeyup="tableSearch()" autocomplete="off">
  <br>
  <table class="table table-bordered table-striped">
    <thead>
        <tr>
            <th>Branch</th>
            <th>Subject</th>
            <th>Paper</th>
            <th>Download</th>
            </tr>
    </thead>
    <tbody id="myTable">
        <tr>
            <td>Cse</td>
            <td> Python Program</td>
            <td>1-2 Mid1</td>
            <td><a href="https://drive.google.com/file/d/1H_jIldHscyusvYaLsEG39xhqQiviLcxh/view?usp=sharing">Click Here</a></td>
        </tr>
        <tr>
            <td>Cse</td>
            <td>Mathematics</td>
            <td>1-2 Mid1</td>
            <td><a href="https://drive.google.com/file/d/13B8Fapa61rMZpUzM4goZ8AcPfzwHuSFf/view?usp=sharing">Click Here</a></td>
        </tr>
        <tr>
            <td>Cse</td>
            <td>DataStructures</td>
            <td>1-2 Mid1</td>
            <td><a href="https://drive.google.com/file/d/1yYzDg56OO_FJcwrlXJ7YdX-hMXQA_jPh/view?usp=sharing">Click Here</a></td>
        </tr>
        <tr>
            <td>Cse</td>
            <td>Applied Chemistry</td>
            <td>1-2 Mid1</td>
            <td><a href="https://drive.google.com/file/d/1BrrHb2ORCTSz40KRfXpi2uuvq2jg1Lyc/view?usp=sharing">Click Here</a></td>
        </tr>
        </tbody>
    </table>
        <p>Note that we start the search in tbody, to prevent filtering the table headers.</p>
</div>
      </div>
      <div class="about" id="about">
          <h2 style="margin:10px;padding: 10px;">About Us</h2>
          <center>
          <p>Hello everyone ! we the unrevealed students of NBKRIST are here with the positive intent to help the juniors and co-students.
            Everyone of us will start  searching for previous mid papers for reference and starts communicating our seniors and it takes some time to collect the papers.
            It will become a timewaste for us during exam preparation.
            No more time waste during the exam time mates!!!
            We collected previous mid papers and we are placing them in this website .
            You no need to waste your time spending time asking each and everyone of your friends for mid papers.
            You can download through this website.
            One sincere and humble request from our side the papers we place in our websites are previous year papers clearly check the date on paper and dont try to misuse them.
            If anyone has midpapers and want to help others please do come forward  and share the papers so you can contact us using Contactus option.</p></center>
          </div>
          <h2 style="paddin-top:20px;">Contact Us</h2>
          
          <div id="contact" style="" class="contact">
            <center>
              <a href="mailto:nbkristmidpapers@gmail.com"> <img src="https://img.freepik.com/free-icon/email_318-304876.jpg?w=360" alt="" style="height:40px;width:40px; padding-left: px;"></img></a>
              <a href="https://www.instagram.com/nbkristmidpapers/"><img src="https://upload.wikimedia.org/wikipedia/commons/9/95/Instagram_logo_2022.svg" alt="" style="height:35px;width:35px;">
              </a>
              <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/2044px-WhatsApp.svg.png" alt="" style="height:45px;width:40px;border-radius:5px;">
              <img src="data:image/png;base64,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" style="height:35px;width:30px;border-radius:5px;">
            </center>
          </div>
      </div>
      </div>
<script>
    function tableSearch()
    {
        let input = document.getElementById("myInput");
        let clean = input.value.toUpperCase();
        let table = document.getElementById("myTable");
        let tr = table.getElementsByTagName("tr");

        for(let i=0;i<tr.length;i++)
        {
            td= tr[i].getElementsByTagName("td")[1]

            if(td)
            {
                let text= td.textContent || td.innerText;
                if(text.toUpperCase().indexOf(clean)>-1)
                {
                    tr[i].style.display="";

                }
                else{
                    tr[i].style.display="none";
                }
            }
        }
    }






    </script>
</body>
</html>
