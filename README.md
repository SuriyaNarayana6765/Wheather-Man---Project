# THE WEATHER MAN PROJECT
This is a simple Django project which displays the weather details (current + forecast + previous) of any location in the world.

Resources Used
Google Places JavaScript API: For the place name auto-completion
Open Weather Maps API: For getting the weather details
Chart.js: For plotting the charts of previous data
AOS: For Animation on Scroll effect
How To Use
Follow the steps to start the local server on your machine:

1.Enter Your Google API Key (./templates/core/home.html) and Open Weather Maps API KEY (./weather_details/views.py). You receive the key after you make an account in the Google Cloud Platform (and Activate Google Places JavaScript API) and Open Weather Maps
2.Download and install Python 3. x
3.Navigate to the repository folder
4.Open the Terminal/CMD/PowerShell at the location (Shift + Right Click => Run Command Prompt/PowerShell for Windows or Right Click => Run Terminal for Linux-based system)
5.Run the Command 'pip install -r requirements.txt' (to download and install the dependencies)
6.Run the Command 'python manage.py run server
7.Run the website (Navigate to '127.0.0.1:8000' on a web browser)
