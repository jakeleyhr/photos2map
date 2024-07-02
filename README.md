This jupyter notebook is designed to take a folder of photos (containing location and time/date metadata) and generate a map of locations and the paths inbetween them over time.
Perfect for easily visualising the path of a holiday, road trip, or in my example case, conference and field trip around Canada:
![output](https://github.com/jakeleyhr/photos2map/assets/154226340/185cf73b-1e69-405d-932a-10fcda8a63a5)
It also produces a simple output of the distance travelled each day:
![output2](https://github.com/jakeleyhr/photos2map/assets/154226340/7945b356-a3ea-4098-a9a0-6300112a44ac)

Just download the .ipynb file and associated mapfiles folder (containing Natural Earth datasets), then modify the start of the script with the right filepaths to the mapfiles folder and to the folder of your iamges.
It runs quite fast, taking around 10s on my very old laptop to generate the above map from ~500 photos. The limiting factor is the total path area rather than number of photos, so if you have photos from all over the world it may take a couple of minutes to complete.

To easily obtain images with metadata from Apple's iPhoto, I select the images and go to File>Export>Export N photos, then choose the lowest quality/size settings (the metadata is the important part for the script, not the image quality).
