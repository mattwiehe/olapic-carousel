# olapic-carousel
Based on documentation, I see that I can GET MEDIA OF A CUSTOMER based on the provided key and customer ID  
I assembled the API query with sorting by recent and otherwise default parameters  
I used a REST client to make the call and found that the "media" is in an array @ "data._embedded.mediaArray"  
I assign the above to the provided var mediaArray= stub  
I used a for loop to iterate through the array and retrieve the image of normal size  
I assign the above as olapicImage as required in the append statement  
The example shows navigation arrows, so I'm setting the owlCarousel nav option to true  
I removed max-width from .owl-stage-outer because it's preventing all 4 images from being displayed  
I removed max-width from .item because it causes gray space between images which are not consistent with the example  
I set position, left, and right on .owl-prev and .owl-next so that the nav arrows would appear on the sides  
I set top:40%; on .owl-nav to vertically center the nav arrows  
I set height:375px; on .item to match the photos in the example  
