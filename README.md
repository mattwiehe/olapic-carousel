# olapic-carousel
Based on documentation, I see that I can GET MEDIA OF A CUSTOMER based on the provided key and customer ID
I assembled the API query with sorting by recent and otherwise default parameters
I used a REST client to make the call and found that the "media" is in an array @ "data._embedded.mediaArray"
I used a for loop to iterate through the array and retrieve the image of normal size
The example shows navigation arrows, so I'm setting the owlCarousel nav option to true
