# Weather-App-on-Android-Android-Studio
Weather App on Android – Android Studio

Create your weather app on Android is esay and a damm cool thing ..
You can get thoue information including Temperature ,
Pressure,Humidity..
Weather status by using weather api ,
there are many website you can search on Google
(api.openweathermap.org).

# Step to create weather app

1.First of all create a  weather api for  http://openweathermap.org/

2. Create a new project in Android Studio

3. Open your AndroidManifest.xml file and add internet connect permission. Your manifest file will look like this-

4.open youe activity_main.xml use RelativeLayout to arrange the text views.

5.Now you need to create a java file Function.java  Her we will write all our function so that we can use them esaly from ManinActivity.java

6. We use the HttpURLConnection class to make the remote request . The OpenWether  API
    in an HTTP header name x-api-key. Tjis is specified in our request using the setRequestProperty method.
    
    We use a BufferedReader to read the API's response into a StringBuffer.
7.When we have complete response we convert it to a JSONObject object.

8.##Don't forget to use your API key in the following line.
    <--private static final String OPEN_WEATHER_MAP_API = "====== YOUR OPEN WEATHER MAP API ======";

-->

9.Now time to go MainActivity.java class 

..              Happy Coding :: Android Make World Better Place                  


