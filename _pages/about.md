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
		{% include figure.html path="assets/img/BannerPhotos/elongasome_cover_white.png" class="mySlides img-fluid rounded z-depth-1" %}
		{% include figure.html path="assets/img/BannerPhotos/STORM_Bsub_cell_wall_crop.jpg" class="mySlides img-fluid rounded z-depth-1" %}
	</div>	
</div> 


Welcome to the Elongasome sLOLA project website!

We are multi-disciplinary consortium of scientists working to understand the molecular basis of  bacterial cell wall synthesis by the elongasome protein complex. 

The elongasome is a protein complex that builds the cell wall of rod-shaped bacteria. This protein complex is a major antibiotic target and is found in many bacteria, including major pathogens such as *Eschericia coli* and *Pseudomonas aeruginosa*.

This project is funded by the UK Biotechnology and Biological Sciences Research Council *Strategic Longer and Larger (sLOLA)* initiative.


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
