## Akash Bapat | Computer Vision
Hi, my name is Akash Bapat.
I am a Research Scientist and I work in the field of Augmented and Virtual Reality at Meta Inc.
Previously, I completed my Ph.D from the computer science department of UNC Chapel Hill and was
advised by <a href="http://frahm.web.unc.edu/">Jan-Michael Frahm</a>.
My research interests can be traced to my <a href="http://www.iitgn.ac.in/">
IITGN</a> days where I worked with Prof.
<a href="http://www.iitgn.ac.in/faculty/electrical/shanmuganathan.htm">
Raman</a>.

## Recent News
* Our paper on stereo system for smart glasses was accepted at CVPR 20223, see <a href="https://arxiv.org/abs/2211.10551">arxiv</a>

## Papers
<table style="width:100%">
<!---------------------------------------------------------------------------->
<tr>
  <td style="padding:20px;width:40%;vertical-align:middle">
    <div id='argos_still'><img src="assets/img/argos/overview.jpg"></div>
  </td>
  <td width="60%" valign="middle">
    <a href = "https://arxiv.org/abs/2211.10551">
      <strong>A Practical Stereo Depth System for Smart Glasses</strong>
    </a>
    <br>
    <a>Jialiang Wang</a>,
    <a>Daniel Scharstein</a>,
    <strong>Akash Bapat</strong>, and
    <a>many other people</a>
    <br>
    To appear in <em>CVPR</em>, 2023
    <br>
    <a href = "assets/bib/wang2023practical.bib">bibtex</a>
    <p></p>
    <p> End to end stereo ML system for smart glasses.
    </p>
  </td>
</tr>
<!---------------------------------------------------------------------------->
<tr>
  <td style="padding:20px;width:40%;vertical-align:middle">
    <div id='thesis_still'></div>
  </td>
  <td width="60%" valign="middle">
    <a href = "https://github.com/akashbapat/akashbapat.github.io/blob/master/assets/pdf/thesis/thesis_small.pdf">
      <strong>Thesis: Towards High-Frequency Tracking and Fast Edge-Aware Optimization</strong>
    </a>
    <br>
    <strong>Akash Bapat</strong>
    <br>
    UNC Chapel Hill Doctoral Thesis.
    <br>
    <a href = "assets/bib/bapat2019towards.bib">bibtex</a>
    <p></p>
    <p> My thesis covering my work on rolling shutter tracking and edge aware optimization.
    </p>
  </td>
</tr>
<!---------------------------------------------------------------------------->
<tr onmouseout="building_sat_recon_stop()" onmouseover="building_sat_recon_start()">
  <td style="padding:20px;width:40%;vertical-align:middle">
    <div id='building_sat_recon_front'><img src="assets/img/building_sat_recon/sat_image.jpg"></div>
    <div id='building_sat_recon_back'><img src="assets/img/building_sat_recon/reconstruction.jpg"></div>
    <script type="text/javascript">
      function building_sat_recon_start() {
        document.getElementById('building_sat_recon_back').style.display = 'inline';
        document.getElementById('building_sat_recon_front').style.display = 'none';
      }

      function building_sat_recon_stop() {
        document.getElementById('building_sat_recon_back').style.display = 'none';
        document.getElementById('building_sat_recon_front').style.display = 'inline';
      }
      building_sat_recon_stop()
    </script>
  </td>
  <td width="60%" valign="middle">
    <a href = "">
      <strong>Boundary-aware 3D Building Reconstruction from a Single Overhead Image</strong>
    </a>
    <br>
    <a href = "https://www.linkedin.com/in/crysoberil">Jisan Mahmud</a>,
    <a href = "https://www.cs.unc.edu/~jtprice/">True Price</a>,
    <strong>Akash Bapat</strong>, and
    <a href = "http://frahm.web.unc.edu/">Jan-Michael Frahm</a>
    <br>
    Appeared in <em>CVPR</em>, 2020
    <br>
    <a href = "assets/bib/mahmud2020boundary.bib">bibtex</a>
    <p></p>
    <p> Predicts building boundaries, semantics, signed distance function (BPSH) and normalized DSMs using a single overhead or satellite image using a multi-task deep learning framework.
    </p>
  </td>
</tr>
<!---------------------------------------------------------------------------->
<tr onmouseout="mapped_conv_stop()" onmouseover="mapped_conv_start()">
  <td style="padding:20px;width:40%;vertical-align:middle">
    <div id='mapped_conv_front'><img src="assets/img/mapped_conv/std_conv.png"></div>
    <div id='mapped_conv_back'><img src="assets/img/mapped_conv/sphere_map.png"></div>
    <script type="text/javascript">
      function mapped_conv_start() {
        document.getElementById('mapped_conv_back').style.display = 'inline';
        document.getElementById('mapped_conv_front').style.display = 'none';
      }

      function mapped_conv_stop() {
        document.getElementById('mapped_conv_back').style.display = 'none';
        document.getElementById('mapped_conv_front').style.display = 'inline';
      }
      mapped_conv_stop()
    </script>
  </td>
  <td width="60%" valign="middle">
    <a href = "https://arxiv.org/pdf/1906.11096.pdf">
      <strong>Mapped Convolutions</strong>
    </a>
    <br>
    <a href = "https://www.marceder.com">Marc Eder</a>,
    <a href = "https://www.cs.unc.edu/~jtprice/">True Price</a>,
    <a href = "http://thanhmvu.com/">Thanh Vu</a>,
    <strong>Akash Bapat</strong>, and
    <a href = "http://frahm.web.unc.edu/">Jan-Michael Frahm</a>
    <br>
    <a href = "assets/bib/eder2019mapped.bib">bibtex</a>
    <p></p>
    <p> Decouples weighted sum and sampling in a convolution operation to enable processing 360 imagery which show high levels of distortion.
    </p>
  </td>
</tr>
<!---------------------------------------------------------------------------->
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
