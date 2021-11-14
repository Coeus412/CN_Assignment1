# CN_Assignment1

**Step 01**: We must run the server first: run the terminal in the directory containing the file Server.py (Where port_server should greater than 1024).
```sh
python Server.py 1888
```
**Step 02**: We open a new terminal in the folder containing the ClientLauncher.py file to connect to the Server we opened in step 01.
– «host_name»: is the IP of the Server on the computer you are using, here is "Macintosh"
– «port_server»: is the port initialized in step 1, here is 1888
– «port_RTP»: for example, we choose 8888
– «name_video»: the name of the video, here is movie.Mjpeg
```sh
python ClientLauncher.py Macintosh 1888 8888 movie.Mjpeg
```
**Step 03**: Click Setup to create RTP stream and press Play to watch video, Pause to stop and Teardown to finish.