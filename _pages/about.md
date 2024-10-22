---
layout: about
title: About
permalink: /


news: true  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

<div class="row">
	<div class="Slideshow" style="margin-bottom:1cm;">
       <img class="mySlides" src="assets/img/BannerPhotos/elongasome_cover_white.png" style="width:100%;border-radius:5px;">
       <img class="mySlides" src="assets/img/BannerPhotos/STORM_Bsub_cell_wall_crop.jpg" style="width:100%;border-radius:5px;">
	</div>	
</div> 

We are multi-disciplinary consortium of scientists working to understand how a multi-protein machine called the elongasome builds the bacterial cell wall.  

The elongasome is a protein complex that builds the cell wall of rod-shaped bacteria. This protein complex is a major antibiotic target and is found in many bacteria, including major pathogens such as *Eschericia coli* and *Pseudomonas aeruginosa*.

This project is funded by the UK Biotechnology and Biological Sciences Research Council *Strategic Longer and Larger (sLOLA)* initiative.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/ukri-bbsrc-square-logo.png" class="img-fluid rounded" width="40%" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/aubergine_master_logo_for_digital_png.jpg" class="img-fluid rounded" width="50%" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
		{% include figure.html path="assets/img/Queens-University-Belfast-logo-1.jpg" class="img-fluid rounded" width="70%" %}
    </div>	
</div>

<script>
    var myIndex = 0;
    carousel();

    function carousel() {
        var i;
        var x = document.getElementsByClassName("mySlides");
        for (i = 0; i < x.length; i++) {
            x[i].style.display = "none";  
        }
        myIndex++;
        if (myIndex > x.length) {myIndex = 1}    
        x[myIndex-1].style.display = "block";  
        setTimeout(carousel, 4000); // Change image every 2 seconds
    }
</script> 
