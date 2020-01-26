---
id: 2
title: media
author: admin
layout: page
guid: http://www.bigearth.eu/media
---

<div class="bg-faded p-4 my-4">
	<div class="bg-faded p-4 my-4">
		<div class="row">
			<div class="col-3">
				<img class="publication-image" src="./assets/news/images/dl-models-ben.jpg">
			</div>
			<div class="col-9">
				<b>January 2020</b> - Deep Learning Models trained on BigEarthNet have been released. For the details, please visit <a href="http://bigearth.net/#downloads">BigEarthNet website</a>.
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-3">
				<img class="publication-image" src="./assets/news/images/BigEarthNetRSiM.png">
			</div>
			<div class="col-9">
				<b>March 2019</b> - We have made public our <a href="http://www.bigearth.net" target="_blank">BigEarthNet</a> archive that is significantly larger than the existing archives in remote sensing and opens up promising directions to advance research for the analysis of large-scale remote sensing image archives.
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-3">
				<img class="publication-image" src="./assets/news/images/ieee_grss_2018.jpg">
			</div>
			<div class="col-9">
				<b>November 2018</b> - Prof. Dr. Demir has been appointed as an Associate Editor for the <a href="http://www.grss-ieee.org/publication-category/grsl/" target="_blank">IEEE Geoscience and Remote Sensing Letters</a>.
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-3">
				<img class="publication-image" src="./assets/news/images/we_are_hiring.png">
			</div>
			<div class="col-9">
				<b>August 2018</b> - We are hiring! <br />
				Please check the <a href="http://bigearth.eu/openpositions.html">open positions</a> for details.
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-3">
				<img class="publication-image" src="./assets/news/images/early_career_award_2018.jpg" id="modalHandleImg">
			</div>
			<div class="col-9">
				<b>July 2018</b> - Prof. Dr. Demir is the recipient of the prestigious <b>“2018 Early Career Award”</b> presented by the IEEE Geoscience and Remote Sensing Society (GRSS).  IEEE GRSS founded in 1962 is the most important international scientific society in the field of geosciences and remote sensing. Factors considered for assigning the award are: quality, the significance and impact of contributions, papers published in archival journals, papers presented at conferences and symposia, a demonstration of leadership, and advancement of the profession.
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-3">
				<img class="publication-image" src="./assets/news/images/tu_berlin_rector_2018.jpg">
			</div>
			<div class="col-9">
				<b>April 2018</b> - BigEarth has moved to TU Berlin and officially started in April 1st! <br />
				<a href="http://www.pressestelle.tu-berlin.de/menue/tub_medien/publikationen/medieninformationen/2018/mai_2018/medieninformation_nr_732018/">For more details...</a>
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-3">
				<img class="publication-image" src="./assets/news/images/corriere-del-trentino-20170916.png">
			</div>
			<div class="col-9">
				<b>September 2017</b> - BigEarth is on <a href="http://www.pressreader.com/italy/corriere-del-trentino/20170916/281487866520040" target="_blank">Corriere del Trentino</a>.
			</div>
		</div>
		<hr />
		<div class="row">
			<div class="col-3">
				<img class="publication-image-default" src="./assets/images/bigearth.png">
			</div>
			<div class="col-9">
				<b>September 2017</b> - BigEarth is on <a href="http://www.buyukkocaeli.com.tr/tarih-seni-yazacak-begum-hoca-11692h.htm" target="_blank">local Turkish newspaper</a>.
			</div>
		</div>
		<hr />		
		<div class="row">
			<div class="col-3">
				<img class="publication-image" src="./assets/news/images/dream_big_set_goals_take_action.png">
			</div>
			<div class="col-9">
				<b>September 2017</b> - Thanks to <a href="https://erc.europa.eu" target="_blank">European Research Council (ERC)</a> <a href="https://erc.europa.eu/sites/default/files/document/file/erc_2017_stg_results_pe.pdf" target="_blank">Starting Grant</a>, Begüm Demir will make her dreams on 'BigEarth - Accurate and Scalable Processing of Big Data in Earth Observation' come true.
			</div>
		</div>
	</div>
</div>


<!-- Modal -->
<!-- The Modal -->
<div id="modalBox" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="modalImg">
  <div id="caption"></div>
</div>

<script>
// Get the modal
var modal = document.getElementById('modalBox');

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById('modalHandleImg');
var modalImg = document.getElementById("modalImg");
var captionText = document.getElementById("caption");

img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
    modal.style.display = "none";
}

modal.addEventListener('click',function(){
  this.style.display="none";
})
</script>