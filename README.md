# Web-development
<!DOCTYPE html>
<html>
    <head>
        
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <style>
        * {
          box-sizing: border-box;
        }
        
        body {
          margin: 20;
          font-family: Arial;
          font-size: 17px;
        }
        
        #myVideo {
          position: fixed;
          max-width: 100%;
          height: auto;
          }
        
        .content {
          position: relative;
          bottom: 0;
          background: rgba(0, 0, 0, 0.5);
          color: #f1f1f1;
          width: 100%;
          padding: 100px;
        }
        
        #myBtn {
          width: 40px;
          height: 20px;
          font-size: 8px;
          padding: 5px;
          border: none;
          background: #000;
          color: #fff;
          cursor: pointer;
        }
        
        #myBtn:hover {
          background: #ddd;
          color: black;
        }
        img{
            width: 200px;
            height: 400px;
            position: relative;
        }
        audio{
          position: fixed;
          right: 0;
          bottom: 0;
          width: 30px; 
          height: 30px;
        }
        div.gallery {
          margin: 5px;
          border: 0.5px solid #ccc;
          float: left;
          width: 180px;
          
          }
          div.gallery:hover {
            border: 1px solid #777;
            }
            div.gallery img {
              width: 100%;
              height: auto;
              }
              div.desc {
                padding: 15px;
                text-align: center;
                }
                a{
                  color: lightseagreen;
                  font-size: 15px;
                }
        </style>
        </head>
        <body>
        
        <video autoplay muted loop id="myVideo">
          <source src="E:\vs code\jack.mp4" type="video/mp4">
            
          Your browser does not support HTML5 video.
        </video>
        <audio controls>
            <source src="sng.mp3" type="audio/mp3">
                <source src="sng.mp3" type="audio/ogg">
                    <p>Your browser doesn't support HTML5 audio. Here is a <a href="songdepp.mp3">link to the audio</a> instead.</p>
            
          </audio>
        
        <div class="content">
          <h1 style="text-align: center;">Jhonny Depp</h1>
          <button id="myBtn" onclick="myFunction()">Pause</button>
          <p style="color: chartreuse;">John Christopher Depp II (born June 9, 1963) is an American actor, producer, and musician. He is regarded as one of the most notable film stars.</p>
          <p>He has been nominated for ten Golden Globe Awards, winning one for Best Actor for his performance of the title role in Sweeney Todd: The Demon Barber of Fleet Street (2007), and has been nominated for three Academy Awards for Best Actor, among other accolades.<br>
             Depp made his film debut in the 1984 film A Nightmare on Elm Street, before rising to prominence as a teen idol on the television series 21 Jump Street (1987–1990).<br>
              He had a supporting role in Oliver Stone's 1986 war film Platoon and played the title character in the 1990 romantic fantasy Edward Scissorhands.</p>
              
              <p>Early life and ancestry
                Depp was born on June 9, 1963,[7] in Owensboro, Kentucky, the youngest of four children of waitress Betty Sue Palmer (née Wells) and civil engineer John Christopher Depp.</p>  
                <p>some</p>
                <div class="gallery">
                  <a target="_blank" href="E:\vs code\johnnyd.jpg">
                    <img src="E:\vs code\johnnyd.jpg" alt="Jhonnyd" width="600" height="400">
                  </a>
                  <div class="desc">Add a description of the image here</div>
                </div>
                <p><h2 style="color: magenta;">Who Is Johnny Depp? </h2>
                    Depp's first film role was in the horror film A Nightmare on Elm Street (1984), in which he played the boyfriend of heroine Nancy Thompson (Heather Langenkamp) and one of Freddy Krueger's victims.<br>
                    After a starring role in the comedy Private Resort (1985), Depp was cast in the lead role of the skating drama Thrashin' (1986) by the film's director, but the decision was later overridden by its producer.</p>
                    <p>1990–2002: Independent films and first collaborations with Tim Burton
                        In 1990, Depp played the title character in Tim Burton's film Edward Scissorhands, in which he starred opposite Dianne Wiest and Winona Ryder. <br>
                        The film was a commercial and critical success with a domestic gross of $53 million. It began his long association with Burton. </p>
                        
                        <div class="gallery">
                          <a target="_blank" href="E:\vs code\jh.jfif">
                            <img src="E:\vs code\jh.jfif" alt="Forest" width="600" height="400">
                          </a>
                          <div class="desc">Add a description of the image here</div>
                        </div>
                        <h3 style="color: magenta;">His Family And About his Ex-Girlfreind</h3>
                        <p>Johnny Depp's ex-partner Winona Ryder has said it is "impossible to believe" allegations from his former wife Amber Heard that he was violent.

                          "I truly and honestly only know him as a really good man," said Ms Ryder.
                          
                          Mr Depp, 57, is suing the publisher of the Sun over an article that referred to him as a "wife beater" - but the newspaper maintains it was accurate.</p>
                          <p>Ms Ryder and Vanessa Paradis, also a former partner of Mr Depp, had been due to give evidence at London's High Court via video link.<br>
                            But on Thursday the actor's barrister David Sherborne told the court Mr Depp's legal team had decided there was no need to hear from them.</p>
                            <p>Ms Ryder, who was in a relationship with Mr Depp for four years, said:<br>
                               "I understand that it is very important that I speak from my own experience, as I obviously was not there during his marriage to Amber</p>
                        
                        <div class="gallery">
                          <a target="_blank" href="E:\vs code\dp.jpg">
                            <img src="E:\vs code\dp.jpg" alt="Northern Lights" width="600" height="400">
                          </a>
                          <div class="desc">Add some details</div>
                        </div>
                        <h4 style="color: magenta;">Johnny depp's achievements</h4>
                        <a href="https://en.wikipedia.org/wiki/List_of_awards_and_nominations_received_by_Johnny_Depp"target="_blank">Depp's achievements</a>
                        <p>One of Burton's frequent collaborators, Johnny Depp, is also Oscar-less. <br>
                          At 56, he has received three Best Actor Academy Award nominations for 2003's "Pirates of the Caribbean:The Curse of the Black Pearl," 2004's "Finding Neverland" and 2007's "Sweeney Todd: The Demon Barber of Fleet Street."</p>
                          <p>In 2004, Depp earned an Academy Award nomination for his starring role as Captain Jack Sparrow in the family adventure Pirates of the Caribbean.<a href="https://www.imdb.com/name/nm0000136/awards"target="_blank">IMDB Rating Of Jhonny Depp</a></p>
                          <div class="gallery">
                            <a target="_blank" href="E:\vs code\dep.jpg">
                              <img src="E:\vs code\dep.jpg" alt="Northern Lights" width="600" height="400">
                            </a>
                            <div class="desc">Add some details</div>
                          </div>
                          <h4 style="color: magenta;"><b>Other ventures</b></h4>
                              <p><b style="color: brown;">Music</b><br>
                                Depp played slide guitar on the Oasis song "Fade In-Out" (from Be Here Now, 1997), as well as on "Fade Away (Warchild Version)" .<br>
                                 He also played acoustic guitar in the film Chocolat and on the soundtrack to Once Upon a Time in Mexico.<br>
                                 <b style="color: brown;">Other projects</b><br>
                                 In 1993, Depp co-founded the nightclub The Viper Room in Los Angeles. He sold his share of the club in 2003.
                                 Together with Vanessa Paradis, Depp grew grapes and had wine making facilities in their vineyard in Plan-de-la-Tour north of Saint-Tropez, France.
                                </p>
                                <p>One of Depp’s other projects is his production company called Infinitum Nihil, where he’s the founder and CEO. It was started in 2004 and has already given a few movies to the big screen.

                                  Besides that, he also started a winery and purchased a few vineyards in Saint-Topez, France.<br>
                                   Plus a superb restaurant on Champs-Elysees.
                                </p>
                                <p><b><a href="https://luxatic.com/johnny-depp-net-worth/#:~:text=Tales%20(2017).-,Other%20Ventures,in%20Saint%2DTopez%2C%20France." target="_blank">More about his other ventures</a></b></p> 
                                <h4 style="color:#dd4124;">Some of My Favourite Images Of Jhonny Depp</h4>
                                <div class="gallery">
                                  <a target="_blank" href="E:\vs code\96.jpg">
                                    <img src="E:\vs code\96.jpg" alt="jhon" width="600" height="400">
                                  </a>
                                  </div>
                                  <div class="gallery">
                                    <a target="_blank" href="E:\vs code\86.jpg">
                                      <img src="E:\vs code\86.jpg" alt="dep" width="600" height="400">
                                    </a>
                                    </div>
                                    <div class="gallery">
                                      <a target="_blank" href="E:\vs code\76.jpeg">
                                        <img src="E:\vs code\76.jpeg" alt="de" width="600" height="400">
                                      </a>
                                      </div>
                                      <div class="gallery">
                                        <a target="_blank" href="E:\vs code\67.jpg">
                                          <img src="E:\vs code\67.jpg" alt="depp" width="600" height="200">
                                        </a>
                                        </div>
                                        <div class="gallery">
                                          <a target="_blank" href="E:\vs code\68.jpg">
                                            <img src="E:\vs code\68.jpg" alt="jhon" width="600" height="400">
                                          </a>
                                          </div>
                                          <div class="gallery">
                                            <a target="_blank" href="E:\vs code\65.jpg">
                                              <img src="E:\vs code\65.jpg" alt="jhon" width="600" height="800">
                                            </a>
                                            </div>
                                            <div class="gallery">
                                              <a target="_blank" href="E:\vs code\66.jpg">
                                                <img src="E:\vs code\66.jpg" alt="jhon" width="600" height="400">
                                              </a>
                                              </div>
                                              
                                  
                                  

                               
                                



        </div>
        
        <script>
        var video = document.getElementById("myVideo");
        var btn = document.getElementById("myBtn");
        
        function myFunction() {
          if (video.paused) {
            video.play();
            btn.innerHTML = "Pause";
          } else {
            video.pause();
            btn.innerHTML = "Play";
          }
        }
        </script>
        
</html>
