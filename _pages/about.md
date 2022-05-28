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
      <td><audio id="m1"> <source src="musics/radetzky_march.mp3" type="audio/mpeg"></audio>
      <div> 
      <img src="images/radetzky_march.png">
      <button onclick="m1_get_volume()">Volume</button> 
      <button onclick="m1_play_music()">Play</button> 
      <button onclick="m1_pause_music()">Pause</button> 
      <button onclick="m1_up_volumne()">Vol +</button> 
      <button onclick="m1_down_volumne()">Vol -</button> 
      </div></td>
      <td><audio id="m2"> <source src="musics/place_called_you.mp3" type="audio/mpeg"></audio>
      <div> 
      <img src="images/place_called_you.png">
      <button onclick="m2_get_volume()">Volume</button> 
      <button onclick="m2_play_music()">Play</button> 
      <button onclick="m2_pause_music()">Pause</button> 
      <button onclick="m2_up_volumne()">Vol +</button> 
      <button onclick="m2_down_volumne()">Vol -</button> 
      </div></td>
      <td><audio id="m3"> <source src="musics/blue_danube.mp3" type="audio/mpeg"></audio>
      <div> 
      <img src="images/blue_danube.png">
      <button onclick="m3_get_volume()">Volume</button> 
      <button onclick="m3_play_music()">Play</button> 
      <button onclick="m3_pause_music()">Pause</button> 
      <button onclick="m3_up_volumne()">Vol +</button> 
      <button onclick="m3_down_volumne()">Vol -</button> 
      </div></td>
      <td><audio id="m4"> <source src="musics/wedding_day.mp3" type="audio/mpeg"></audio>
      <div> 
      <img src="images/wedding_day.png">
      <button onclick="m4_get_volume()">Volume</button> 
      <button onclick="m4_play_music()">Play</button> 
      <button onclick="m4_pause_music()">Pause</button> 
      <button onclick="m4_up_volumne()">Vol +</button> 
      <button onclick="m4_down_volumne()">Vol -</button> 
      </div></td>
    </tr> 
<script>
    var m1 = document.getElementById("m1");
    function m1_get_volume() {
      alert(m1.volume)
    }
    function m1_play_music() { 
      m1.play();
    } 
    function m1_pause_music() { 
      m1.pause();
    } 
    function m1_up_volumne() { 
      m1.volume = parseFloat(m1.volume)+0.1;
    } 
    function m1_down_volumne() { 
      m1.volume = parseFloat(m1.volume)-0.1;
    } 
    var m2 = document.getElementById("m2");
    function m2_get_volume() {
      alert(m2.volume)
    }
    function m2_play_music() { 
      m2.play();
    } 
    function m2_pause_music() { 
      m2.pause();
    } 
    function m2_up_volumne() { 
      m2.volume = parseFloat(m2.volume)+0.1;
    } 
    function m2_down_volumne() { 
      m2.volume = parseFloat(m2.volume)-0.1;
    } 
    var m3 = document.getElementById("m3");
    function m3_get_volume() {
      alert(m3.volume)
    }
    function m3_play_music() { 
      m3.play();
    } 
    function m3_pause_music() { 
      m3.pause();
    } 
    function m3_up_volumne() { 
      m3.volume = parseFloat(m3.volume)+0.1;
    } 
    function m3_down_volumne() { 
      m3.volume = parseFloat(m3.volume)-0.1;
    }  
    var m4 = document.getElementById("m4");
    function m4_get_volume() {
      alert(m4.volume)
    }
    function m4_play_music() { 
      m4.play();
    } 
    function m4_pause_music() { 
      m4.pause();
    } 
    function m4_up_volumne() { 
      m4.volume = parseFloat(m4.volume)+0.1;
    } 
    function m4_down_volumne() { 
      m4.volume = parseFloat(m4.volume)-0.1;
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

* Quincy is a Traveler
  <table>
  <caption>Traveling in <a href="https://en.wikipedia.org/wiki/China">China</a></caption>
      <tr>
        <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Beijing">Beijing</a>, <a href="https://en.wikipedia.org/wiki/Direct-administered_municipalities_of_China">Direct-administered municipalities of China</a></td>
        <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Tianjin">Tianjin</a>, <a href="https://en.wikipedia.org/wiki/Direct-administered_municipalities_of_China">Direct-administered municipalities of China</a></td>
        <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Shanghai">Shanghai</a>, <a href="https://en.wikipedia.org/wiki/Direct-administered_municipalities_of_China">Direct-administered municipalities of China</a></td>
        <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Nanjing">Nanjing</a>, <a href="https://en.wikipedia.org/wiki/Jiangsu">Jiangsu</a></td>
      </tr>
      <tr>
        <td><img style="display:block;" src="images/beijing.png" width="100%" height="100%"></td>
        <td><img style="display:block;" src="images/tianjin.png" width="100%" height="100%"></td>
        <td><img style="display:block;" src="images/shanghai.png" width="100%" height="100%"></td>
        <td><img style="display:block;" src="images/nanjing.png" width="100%" height="100%"></td>
      </tr>
  </table>

  <table>
    <tr>
      <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Xi%27an">Xi'an</a>, <a href="https://en.wikipedia.org/wiki/Fujian">Shaanxi</a></td>
      <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Xiamen">Xiamen</a>, <a href="https://en.wikipedia.org/wiki/Fujian">Fujian</a></td>
      <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Changchun">Changchun</a>, <a href="https://en.wikipedia.org/wiki/Jilin">Jilin</a></td>
      <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Harbin">Harbin</a>, <a href="https://en.wikipedia.org/wiki/Heilongjiang">Heilongjiang</a></td>
    </tr>
    <tr>
      <td><img style="display:block;" src="images/xian.png" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/xiamen.png" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/changchun.png" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/harbin.png" width="100%" height="100%"></td>
    </tr>
  </table>

  <table>
  <caption>Traveling in the <a href="https://en.wikipedia.org/wiki/United_States">United States</a></caption>
      <tr>
        <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Minneapolis">Minneapolis</a>, <a href="https://en.wikipedia.org/wiki/Minnesota">MN</a></td>
        <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Rochester,_Minnesota">Rochester</a>, <a href="https://en.wikipedia.org/wiki/Minnesota">MN</a></td>
        <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Duluth,_Minnesota">Duluth</a>, <a href="https://en.wikipedia.org/wiki/Minnesota">MN</a></td>
        <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Chicago">Chicago</a>, <a href="https://en.wikipedia.org/wiki/Illinois">IL</a></td>
      </tr>
      <tr>
        <td><img style="display:block;" src="images/mpls.png" width="100%" height="100%"></td>
        <td><img style="display:block;" src="images/rochester.png" width="100%" height="100%"></td>
        <td><img style="display:block;" src="images/duluth.png" width="100%" height="100%"></td>
        <td><img style="display:block;" src="images/chicago.png" width="100%" height="100%"></td>
      </tr>
  </table>

  <table>
    <tr>
      <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Boston">Boston</a>, <a href="https://en.wikipedia.org/wiki/Massachusetts">MA</a></td>
      <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/San_Francisco">San Francisco</a>, <a href="https://en.wikipedia.org/wiki/California">CA</a></td>
      <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Las_Vegas">Las Vegas</a>, <a href="https://en.wikipedia.org/wiki/Nevada">NV</a></td>
      <td style="text-align:center"><a href="https://en.wikipedia.org/wiki/Seattle">Seattle</a>, <a href="https://en.wikipedia.org/wiki/Washington_(state)">WA</a></td>
    </tr>
    <tr>
      <td><img style="display:block;" src="images/boston.png" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/sanfran.png" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/vegas.png" width="100%" height="100%"></td>
      <td><img style="display:block;" src="images/seattle.png" width="100%" height="100%"></td>
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
        <td style="text-align:center">Qiuqi, Gao. Life Partner.<br> Birth date October 14th, 1997.<br></td>
        <td style="text-align:center">Cisco, Male, <a href="ragdoll show">Ragdoll</a>.<br> Born in July 2019.<br></td>
        <td style="text-align:center">Leena, Female, <a href="https://en.wikipedia.org/wiki/Pembroke_Welsh_Corgi">Pembroke Welsh Corgi</a>.<br> Born in June 2021.<br></td>
      </tr>
      <tr> 
        <td><img style="display:block;" src="images/qiuqi_gao.jpg" width="100%" height="100%"></td>
        <td><img style="display:block;" src="images/cisco.png" width="100%" height="100%"></td>
        <td><img style="display:block;" src="images/leena.JPG" width="100%" height="100%"></td>
      </tr>
    </table>
