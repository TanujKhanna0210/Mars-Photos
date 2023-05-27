# Mars Photos
Mars Photos is an app which shows images of Mars surface. This app connects to a web service to retrieve and display the Mars photos. The images are real-life photos from Mars captured from NASA's Mars rovers.  

A layer for the network service is created that communicates with the backend server and fetches the required data. We use a third party library to implement this, called __Retrofit__.  
We use the __Moshi__ library with Retrofit to parse the JSON response from the web service into useful Kotlin objects which represent Mars photos.  
Then, we use the __Coil__ library to load and display the images.  
The final app contains a grid of thumbnail property images, built with a _RecyclerView_.
