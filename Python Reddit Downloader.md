# Python-Reddit-Downloader
 - Downloads Videos, Gifs, and Images from Subreddits, and Reddit Users

 --- SETUP ---

 - Run the "Install Requirements" file

 - Log into any Reddit Account in Microsoft Edge

 - Install the "get cookies.txt LOCALLY" extension

 - Go to the Reddit Home Page, click the Extension, and Export

 - Save the txt it downloads in the ASSETS folder, and name it "cookies"

 - Go Here: https://www.reddit.com/prefs/apps

 - Create an application
 -  - Script app
 -  - Redirect Uri: http://localhost:8080

 - Once created, your client_id is the string under where it says "personal use script", under your app name
 -  - Put this string in the reddit_auth json in the "client_id" line

 - Put the secret string in the "client_secret" line

 - Add your username in the "user_agent" line after the "by u/"



 --- HOW IT WORKS ---

 - When ran, it will ask what media you want, it can do Videos, Gifs, Images, or All

 - Run "Get Links" to have it save links from the listed subreddits in the jsons in the LINKS folder

 - Run "Get Files" to have it download media from the listed subreddits into the MEDIA folder, in specified folders

 - Edit the "subreddits" json in the ASSETS folder to change what subreddits its looking at
