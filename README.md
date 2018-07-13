# ffprobe-json-api
This project currently examines a video file using ffprobe to create a JSON output file.

# Original Objective
Create an API that accepts a url path to a video file. The API must examine the video and return the following data about the video in the specified json format provided.

• File name  
• Duration  
• List of video streams and specified details  
• List of audio streams and specified details  
• List of caption streams and specified details

# Explanation
I used ffprobe as it is an excutable that is specifically designed to return video metadata. I chose to use a WISA stack all running locally on my PC as it is the stack I am most familar with.

Whilst I have not been able to successfully create an API that queries the sample video files to return a JSON file, I have been able to query video files locally on my Windows machine using command line syntax.

By querying the video files locally I have succesfully been able to examine the video files, return the required data and output it in the required JSON format - it is just missing the API component.

# API Progress
I was able to create a very simple API using a WISA stack locally on my PC by using Visual Studio 2017. However combining it with ffprobe and developing the API to the point where it outputting the JSON response has not yet been acheived.

# Conclusion
If this was a real world situation opertaing within a business, I would imagine that I would have peers and slightly more time to help me achieve this goal. I consider this quite a complex task for junior role too.

I have never built an API before, limited experience with ffmpeg and JSON so to acheive what I have in the time allocated I feel that I have made excellent progress and created some great foundations in terms of my knowledge of API's, ffprobe and the JSON format.
