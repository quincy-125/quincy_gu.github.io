---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
 
Qiangqiang(Quincy) Gu is a Ph.D. candidate in [biomathematics](https://en.wikipedia.org/wiki/Mathematical_and_theoretical_biology), [bioinformatics](https://en.wikipedia.org/wiki/Bioinformatics), and [computational biology](https://en.wikipedia.org/wiki/Computational_biology) trained jointly by the [University of Minnesota - Twin Cities](https://twin-cities.umn.edu) and the [Mayo Clinic Graduate School of Biomedical Sciences](https://college.mayo.edu). He also holds a bachelor degree from the [University of Minnesota - Twin Cities in mathematics](https://cse.umn.edu/math). 
With primary interests in medicine and engineering, Quincy served as an undergraduate research assistant at the [University of Minnesota Medical School](https://med.umn.edu), where he did research on [colorectal cancer](https://www.cdc.gov/cancer/colorectal/basic_info/what-is-colorectal-cancer.htm) patients [survival analysis](https://en.wikipedia.org/wiki/Survival_analysis) and [breast cancer](https://www.mayoclinic.org/diseases-conditions/breast-cancer/symptoms-causes/syc-20352470) [MRI](https://www.mayoclinic.org/tests-procedures/mri/about/pac-20384768) image processing. His previous research experience convinced him that he could be a dedicated medical science researcher in the future by pursing a doctoral degree.
After joining Mayo Clinic, he has focused his research on [computer vision](https://en.wikipedia.org/wiki/Computer_vision) and [digital pathology](https://en.wikipedia.org/wiki/Digital_pathology). With special interest in [melanoma](https://www.mayoclinic.org/diseases-conditions/melanoma/symptoms-causes/syc-20374884), Quincy is developing [artificial intelligence (AI)](https://en.wikipedia.org/wiki/Artificial_intelligence) algorithms in [Whole Slide Images (WSIs)](https://digitalpathologyassociation.org/whole-slide-imaging-repository) analysis, which aims to support clinical melanoma diagnostics and treatment by providing automatic melanoma diagnostics and individualized therapeutic options.
Quincy is looking forward to continuing his education in the medical doctoral (MD) training program after graduating from the Ph.D. program. He is particularly interested in being a physician-scientist to provide direct patient care and contribute to the innovations in cancer diagnostics and therapies as his long-term career goal.

Education Backgrounds
=====

  <table>
      <tr>
        <td width="200" height="50" style="text-align:center">Undergradte Study at the <a href="https://twin-cities.umn.edu">University of Minnesota - Twin Cities</a> <a href="https://cla.umn.edu/undergraduate-students/requirements-policies/about-majors-minors/shared-majors-and-minors/ba-mathematics">College of Libral Arts</a> majored in <a href="https://cse.umn.edu/math">Mathematics</a></td>
        <td width="200" height="50" style="text-align:center">Ph.D. Trainig at the <a href="https://college.mayo.edu">Mayo Clinic</a> in Bioinformatics and Computational Biology <a href="https://r.umn.edu/academics-research/graduate/bicb">(BICB)</a></td>
      </tr>
      <tr>
        <td><img style="vertical-align: bottom;" src="images/umn.png" width="100%" height="100%"></td>
        <td><img style="vertical-align: bottom;" src="images/mayo_clinic.png" width="100%" height="100%"></td>
      </tr>
    </table>

Facts about Quincy
=====
* Quincy is a Real Person with No Doubts: 

  <table>
    <tr>
      <td style="text-align:center">Traveler</td>
      <td style="text-align:center">Foody</td>
      <td style="text-align:center">Nerdy</td>
    </tr>
    <tr>
      <td><img style="display:block;" src="images/traveler.gif" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/foody.gif" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/nerd.gif" width="100%" height="100%"></td>
    </tr>
  </table>

* Quincy is a Music Enthusiast:
     
  <table>
  <caption>Songs Quincy Loves</caption>
    <tr>
      <td style="text-align:center">Radetzky March</td>
      <td style="text-align:center">A Place Called You</td>
      <td style="text-align:center">The Blue Danube</td>
      <td style="text-align:center">Wedding Day</td>
    </tr>
    <tr>
      <td><audio id="radetzky_march" display="true"> <source src="musics/radetzky_march.mp3" type="audio/mpeg"></audio>
      <div> 
      <button onclick="getVolume()">Volume</button>
      <button onclick="play_music()">Play</button> 
      <button onclick="pause_music()">Pause</button> 
      <button onclick="up_volumne()">Vol +</button> 
      <button onclick="down_volumne()">Vol -</button> 
      </div>
      <td><audio id="place_called_you" display="true"> <source src="musics/place_called_you.mp3" type="audio/mpeg"></audio>
      <div> 
      <button onclick="getVolume()">Volume</button>
      <button onclick="play_music()">Play</button> 
      <button onclick="pause_music()">Pause</button> 
      <button onclick="up_volumne()">Vol +</button> 
      <button onclick="down_volumne()">Vol -</button> 
      </div>
      <td><audio id="blue_danube" display="true"> <source src="musics/blue_danube.mp3" type="audio/mpeg"></audio>
      <div> 
      <button onclick="getVolume()">Volume</button>
      <button onclick="play_music()">Play</button> 
      <button onclick="pause_music()">Pause</button> 
      <button onclick="up_volumne()">Vol +</button> 
      <button onclick="down_volumne()">Vol -</button> 
      </div>
      <td><audio id="wedding_day" display="true"> <source src="musics/wedding_day.mp3" type="audio/mpeg"></audio>
      <div> 
      <button onclick="getVolume()">Volume</button>
      <button onclick="play_music()">Play</button> 
      <button onclick="pause_music()">Pause</button> 
      <button onclick="up_volumne()">Vol +</button> 
      <button onclick="down_volumne()">Vol -</button> 
      </div>
    </tr>

    <script>
    var radetzky_march = document.getElementById("radetzky_march");
    var place_called_you = document.getElementById("place_called_you");
    var blue_danube = document.getElementById("blue_danube");
    var wedding_day = document.getElementById("wedding_day");

    function getVolume() { 
      alert(radetzky_march.volume);
      alert(place_called_you.volume);
      alert(blue_danube.volume);
      alert(wedding_day.volume);
    } 

    function play_music() { 
      radetzky_march.play();
      radetzky_march.play();
      blue_danube.play();
      wedding_day.play();
    } 
      
    function pause_music() { 
      radetzky_march.pause();
      place_called_you.pause();
      blue_danube.pause();
      wedding_day.pause();
    } 
      
    function up_volumne() { 
      radetzky_march.volume = parseFloat(radetzky_march.volume)+0.1;
      place_called_you.volume = parseFloat(place_called_you.volume)+0.1;
      blue_danube.volume = parseFloat(blue_danube.volume)+0.1;
      wedding_day.volume = parseFloat(wedding_day.volume)+0.1;
    } 

    function down_volumne() { 
      radetzky_march.volume = parseFloat(radetzky_march.volume)-0.1;
      place_called_you.volume = parseFloat(place_called_you.volume)-0.1;
      blue_danube.volume = parseFloat(blue_danube.volume)-0.1;
      wedding_day.volume = parseFloat(wedding_day.volume)-0.1;
    } 
  </script> 
  </table>

<table>
<caption>Musical Instruments Quincy Could Play</caption>
    <tr>
      <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Piano">Piano</a></td>
      <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Violin">Violin</a></td>
      <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Erhu">ErHu</a></td>
    </tr>
    <tr>
      <td><img style="display:block;" src="images/piano.png" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/violin.png" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/erhu.png" width="100%" height="100%"></td>
    </tr>
</table>

* Quincy is also a Ph.D. Candidate:

  <table>
    <tr>
      <td style="text-align:center">Overwork but Underpaid</td>
      <td style="text-align:center">Always in a Stress Mode</td>
      <td style="text-align:center">Anxiety</td>
      <td style="text-align:center">Imposter Syndrome</td>
    </tr>
    <tr>
      <td><img style="display:block;" src="images/overwork_underpaid.gif" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/stress_mode.gif" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/anxiety.gif" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/imposter_syndrome.gif" width="100%" height="100%"></td>
    </tr>
  </table>

  <table>
    <tr>
      <td style="text-align:center">Overthinking</td>
      <td style="text-align:center">A Caffeine Addict</td>
      <td style="text-align:center">Fatigue</td>
      <td style="text-align:center">Nobody Cares About Your Ph.D. But You</td>
    </tr>
    <tr>
      <td><img style="display:block;" src="images/overthink.gif" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/caffeine_addict.gif" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/fatigue.gif" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/who_cares.gif" width="100%" height="100%"></td>
    </tr>
  </table>


Research & Life Partners
======

  <table>
      <tr>
        <td style="text-align:center">Leena, Female, <a href="https://en.wikipedia.org/wiki/Pembroke_Welsh_Corgi">Pembroke Welsh Corgi</a>, born in June 2021</td>
        <td style="text-align:center">Girlfriend, Female, Pending, birth date currently is not available</td>
      </tr>
      <tr>
        <td><img style="display:block;" src="images/leena.png" width="100%" height="100%"></td>
        <td><img style="display:block;" src="images/kiss_love.gif" width="100%" height="100%"></td>
      </tr>
    </table>
