---
id: 5
title: externals
author: admin
layout: page
guid: https://www.bigearth.eu/externals
---
<div class="bg-faded p-4 my-4">
	<div class="bg-faded p-4 my-4">
		<p>
			This page is devoted to list the BigEarthNet related datasets and tools that are developed by researchers outside from <a href="https://tu.berlin" target="_blank">TU Berlin</a> and are publicly available.
		</p>
		<h4></h4>
		<p>
			<b>About BigEarthNet:</b> The BigEarthNet archive was constructed by the Remote Sensing Image Analysis (<a href="https://www.rsim.tu-berlin.de/menue/remote_sensing_image_analysis_group/" target="_blank">RSiM</a>) Group and the Database Systems and Information Management (<a href="https://www.dima.tu-berlin.de/menue/database_systems_and_information_management_group/" target="_blank">DIMA</a>) Group at the Technische Universität Berlin (TU Berlin). This work is supported by the European Research Council under the ERC Starting Grant `BigEarth` and by the Berlin Institute for the Foundations of Learning and Data <a href="http://bifold.berlin" target="_blank">(BIFOLD)</a>.
		</p>
		<p>
			For the details about BigEarthNet, please visit <a href="http://bigearth.net" target="_blank">BigEarthNet</a>.
		</p>
		<p>
			If you have publicly available BigEarthNet related datasets and software tools, please let us know via <a href="mailto:contact@bigearth.eu">contact@bigearth.eu</a>! We would be happy to list your work here!
		</p>
		<hr />
		<div class="row">
			<div class="col-lg-3 col-lg-12-pull">
				<img class="publication-image mx-auto d-block" src="./assets/externals/images/RSVQAxBEN.png">
			</div>
			<div class="col-lg-9 col-lg-12-push">
				RSVQAxBEN
				<br/>
				<a href="https://zenodo.org/record/5084904#.YfaLu_go9D8" target="_blank">RSVQAxBEN Dataset</a>
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-lg-3 col-lg-12-pull">
				<img class="publication-image mx-auto d-block" src="./assets/externals/images/radiant-earth.png">
			</div>
			<div class="col-lg-9 col-lg-12-push">
				<a href="https://www.radiant.earth" target="_blank">Radiant Earth Team</a>
				<br/>
				<a href="https://towardsdatascience.com/outperforming-google-cloud-automl-vision-with-tensorflow-and-google-deep-learning-vm-34a45e3860ae" target="_blank">Radiant MLHub - Open Geospatial Datasets Library</a>
				<br/>
				GitHub Repository: <a href="https://github.com/radiantearth/mlhub-tutorials/blob/master/notebooks/radiant-mlhub-bigearthnet.ipynb" target="_blank">https://github.com/radiantearth/mlhub-tutorials/blob/master/notebooks/radiant-mlhub-bigearthnet.ipynb</a>
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-lg-3 col-lg-12-pull">
				<img class="publication-image mx-auto d-block" src="./assets/externals/images/detecting-clouds.png">
			</div>
			<div class="col-lg-9 col-lg-12-push">
				<a href="https://www.linkedin.com/in/shane-keller-ba891315/" target="_blank">Shane Keller</a>
				<br/>
				<a href="https://towardsdatascience.com/outperforming-google-cloud-automl-vision-with-tensorflow-and-google-deep-learning-vm-34a45e3860ae" target="_blank">Detecting Clouds in Satellite Images with Deep Learning</a>
				<br/>
				GitHub Repository: <a href="https://github.com/skeller88/deep_learning_project" target="_blank">https://github.com/skeller88/deep_learning_project</a>
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-lg-3 col-lg-12-pull">
				<img class="publication-image mx-auto d-block" src="./assets/externals/images/satim-net.png">
			</div>
			<div class="col-lg-9 col-lg-12-push">
				Vasileios Syrris, Ondrej Pesek, Pierre Soille
				<br/>
				<a href="https://arxiv.org/abs/2006.10623" target="_blank">SatImNet: Structured and Harmonised Training Data for Enhanced Satellite Imagery Classification</a>
				<br/>
				GitHub Repository: TBD
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-lg-3 col-lg-12-pull">
				<img class="publication-image mx-auto d-block" src="./assets/externals/images/google-earth-engine.png">
			</div>
			<div class="col-lg-9 col-lg-12-push">
				Google Earth Engine BigEarthNet Catalog
				<br/>
				<a href="https://developers.google.com/earth-engine/datasets/catalog/TUBerlin_BigEarthNet_v1" target="_blank">TUBerlin/BigEarthNet/v1</a>
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-lg-3 col-lg-12-pull">
				<img class="publication-image mx-auto d-block" src="./assets/externals/images/tensorflow.png">
			</div>
			<div class="col-lg-9 col-lg-12-push">
				TensorFlow Open Source Library
				<br/>
				<a href="https://www.tensorflow.org/datasets/catalog/bigearthnet" target="_blank">BigEarthNet Catalog</a>
			</div>
		</div>
	</div>
</div>


<!-- Modal -->
<!-- The Modal -->
<div id="modalBox" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="modalImg" />
  <div id="caption"></div>
</div>

<script type="text/javascript">

// Get the modal
var modal = document.getElementById('modalBox');

// Get the image and insert it inside the modal - use its "alt" text as a caption
// var img = document.getElementById('dspImg');
var modalImg = document.getElementById("modalImg");
var captionText = document.getElementById("caption");

publication_images = document.getElementsByClassName("publication-image");

for (var i = publication_images.length - 1; i >= 0; i--) {
	img = publication_images[i]

	img.onclick = function(){
	    modal.style.display = "block";
	    modalImg.src = this.src;
	    captionText.innerHTML = this.alt;
	}
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() {
    modal.style.display = "none";
}

// When user clicks into the modal, close the modal
modal.addEventListener('click',function(){
 	this.style.display="none";
})

// When user hits ESC, close the modal
document.addEventListener("keydown", function(event) {
	if (event.keyCode == 27) {
		modal.style.display="none";
	}
})
</script>

<style type="text/css">
 /* Style the Image Used to Trigger the Modal */
.publication-image:hover {
	opacity: 0.7;
	cursor: pointer;
}

/* The Modal (background) */
.modal {
    display: none; /* Hidden by default */
    position: fixed; /* Stay in place */
    z-index: 1; /* Sit on top */
    padding-top: 100px; /* Location of the box */
    left: 0;
    top: 0;
    width: 100%; /* Full width */
    height: 100%; /* Full height */
    overflow: auto; /* Enable scroll if needed */
    background-color: rgb(0,0,0); /* Fallback color */
    background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
    z-index: 2030;
}

/* Modal Content (Image) */
.modal-content {
    margin: auto;
    display: block;
    width: 80%;
    max-width: 700px;
}

/* Caption of Modal Image (Image Text) - Same Width as the Image */
#caption {
    margin: auto;
    display: block;
    width: 80%;
    max-width: 700px;
    text-align: center;
    color: #ccc;
    padding: 10px 0;
    height: 150px;
}

/* Add Animation - Zoom in the Modal */
.modal-content, #caption {
    animation-name: zoom;
    animation-duration: 0.6s;
}

@keyframes zoom {
    from {transform:scale(0)}
    to {transform:scale(1)}
}

/* The Close Button */
.close {
    position: absolute;
    top: 15px;
    right: 35px;
    color: #f1f1f1;
    font-size: 40px;
    font-weight: bold;
    transition: 0.3s;
}

.close:hover,
.close:focus {
    color: #bbb;
    text-decoration: none;
    cursor: pointer;
}

/* 100% Image Width on Smaller Screens */
@media only screen and (max-width: 700px){
    .modal-content {
        width: 100%;
    }
}
</style>

