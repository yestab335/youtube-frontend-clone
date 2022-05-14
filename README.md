# YouTube Frontend Clone
![Website Preview](img/Website.png)

Youtube is a very popular video serving platform. Learn to create youtube Home page clone with HTML, css and JS . Learn about youtube API to fetch youtube data and learn to process the fetched data.

# Connect YouTube API
1. Search for [Google Cloud](https://cloud.google.com/) and sign in.
2. Once logged in, go to your console.
3. Next to the Google Cloud Platform logo is an area where you can select a project. Select the current project and/or click on 'new project'.
4. Give your project a name and click 'CREATE'.
5. Open the side navigation bar by clicking on the hamburger menu in the top left corner, and navigate to a link titled 'APIs & Services'.
6. In the side navigation bar, click and open your 'Library'.
7. Search for the library titled "YouTube Data API V3".
8. Enable the library.
9. In the side navigation bar, click and open your 'Credentials'.
10. In the top navigation bar, locate 'CREATE CREDENTIALS' and click it to create an API key.
11. Copy the API key.
12. Click on the 'edit' icon and make sure the "Application retrictions" is set to none. Otherwise the PI will not accept requests from the local IP.
13. Open the app.js file and set a variable with the API key.
`let api_key = (api key)`
14. After, go to [youtube API documentations](https://developers.google.com/youtube/v3/docs/videos/list#request) and open the 'Video' list in the side navigation bar.
15. Copy the 'HTTP request'
16. Open the app.js file and set a variable with the HTTP request code.
`let video_http = https://www.googleapis.com/youtube/v3/videos?`