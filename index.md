## Akash Bapat | Computer Vision
Hi, my name is Akash Bapat.
I am a Ph.D student in the computer science department of UNC Chapel Hill 
advised by <a href="http://frahm.web.unc.edu/">Jan-Michael Frahm</a>.
My interests are computer vision and augmented and virtual reality.
My research interests can be traced to my <a href="http://www.iitgn.ac.in/">
IITGN</a> days where I worked with Prof. 
<a href="http://www.iitgn.ac.in/faculty/electrical/shanmuganathan.htm">
Raman</a>.

## Recent News
1. Joining Facebook mid-August.
2. Recently, I defended my Ph.D thesis. YAY!!!

## Papers
<table style="width:100%">
<tr onmouseout="dts_stop()" onmouseover="dts_start()">
  <td style="padding:20px;width:40%;vertical-align:middle">
    <div id='dts_anim' class='hidden'><img src="assets/img/dts/dts_example_result.gif"></div>
    <div id='dts_still'><img src="assets/img/dts/example_marked.png"></div>
    <script type="text/javascript">
      function dts_start() {
        document.getElementById('dts_anim').style.display = 'inline';
        document.getElementById('dts_still').style.display = 'none';
      }

      function dts_stop() {
        document.getElementById('dts_anim').style.display = 'none';
        document.getElementById('dts_still').style.display = 'inline';
      }
      dts_stop()
    </script>
  </td>
  <td width="60%" valign="middle">
    <a href = "https://github.com/akashbapat/domain_transform_solver/blob/master/paper/dts_solver.pdf">
      <strong>The Domain Transform Solver</strong>
    </a>
    <br>
    <strong>Akash Bapat</strong> and
    <a href = "http://frahm.web.unc.edu/">Jan-Michael Frahm</a>
    <br>
    <em>CVPR</em>, 2019
    <br>
    <a href = "https://arxiv.org/abs/1805.04590"> arxiv</a> /
    <a href = "https://github.com/akashbapat/domain_transform_solver">
    code</a> /
    <a href = "assets/bib/bapat2019domain.bib"> bibtex</a>
    <p></p>
    <p> Fast edge-aware optimization can be done by using approximate 1-D filtering techniques.
    </p>
  </td>
</tr>
<!---------------------------------------------------------------------------->
<tr onmouseout="rd_tracking_stop()" onmouseover="rd_tracking_start()">
  <td style="padding:20px;width:40%;vertical-align:middle">
    <div id='rd_tracking_front'><img src="assets/img/rd_tracking/rd_tracking_front.png"></div>
    <div id='rd_tracking_back'><img src="assets/img/rd_tracking/rd_tracking_back.png"></div>
    <script type="text/javascript">
      function rd_tracking_start() {
        document.getElementById('rd_tracking_back').style.display = 'inline';
        document.getElementById('rd_tracking_front').style.display = 'none';
      }

      function rd_tracking_stop() {
        document.getElementById('rd_tracking_back').style.display = 'none';
        document.getElementById('rd_tracking_front').style.display = 'inline';
      }
      rd_tracking_stop()
    </script>
  </td>
  <td width="60%" valign="middle">
    <a href = "assets/pdf/rd_tracking/radial_distortion_tracking_cvpr_18_paper.pdf">
      <strong>Rolling Shutter and Radial Distortion are Features for High Frame Rate
Multi-camera Tracking</strong>
    </a>
    <br>
    <strong>Akash Bapat</strong>,
    <a href = "https://www.cs.unc.edu/~jtprice/">True Price</a> and
    <a href = "http://frahm.web.unc.edu/">Jan-Michael Frahm</a>
    <br>
    <em>CVPR</em>, 2018
    <br>
    <a href = "assets/pdf/rd_tracking/radial_distortion_tracking_cvpr_18_poster.pdf">
    poster</a> /
    <a href = "assets/pdf/rd_tracking/radial_distortion_tracking_cvpr_18_supplementary.pdf">
    supp</a> /
    <a href = "assets/bib/bapat2018rolling.bib"> bibtex</a>
    <p></p>
    <p> Radial distortion induces multiple virtual rolling shutter cameras. Using these virtual cameras, we can better constrain the head-pose motion and still track at a high-frequency.
    </p>
  </td>
</tr>
<!---------------------------------------------------------------------------->
<tr>
  <td style="padding:20px;width:40%;vertical-align:middle">
    <div id='rs_tracking_still'><img src="assets/img/rs_tracking/rs_tracking.png"></div>
  </td>
  <td width="60%" valign="middle">
    <a href = "assets/pdf/rs_tracking/Bapat_Dunn_Frahm_ISMAR2016.pdf">
      <strong>Towards Kilo-Hertz 6-DoF Visual Tracking Using an Egocentric Cluster of Rolling Shutter Cameras</strong>
    </a>
    <br>
    <strong>Akash Bapat</strong>,
    <a href = "https://www.cs.stevens.edu/~edunn/">Enrique Dunn</a> and
    <a href = "http://frahm.web.unc.edu/">Jan-Michael Frahm</a>
    <br>
    <em>ISMAR/TVCG</em>, 2016, <strong style="color:Red;">Best Paper Award</strong> 
    <br>
    <a href = "assets/pdf/rs_tracking/paper135TalkDistribute.pdf">
    talk</a> /
    <a href = "assets/bib/bapat2016towards.bib"> bibtex</a>
    <p></p>
    <p> Rolling shutter exposure provides us with a high fequency of row-image samples. If we can estimate a pose per-row, then we have a high-frequency tracker.
    </p>
  </td>
</tr>
</table>
