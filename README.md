# kongsberg_auv_image_pipeline
end to end processing of cathx camera images, from 1st import from AUV to plotting classified detections on a map.
1. import images
2. run megaladon object detector to extract images with features.
3. run clustering to sort into rough species groups
4. extract lat, long, altitude and time from images
5. plot images ID'd in step 3 on a map
6. assess impact of altitude on detections of each cluster

TO DO:
- Use the clustered images, check/refine the sorting into functional categories and train a classifier.
- then use the classified images for the above
- extract transect coordinates from post processed navigation files
- draw out all transects
