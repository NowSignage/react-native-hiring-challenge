## NowSignage Programming Challenge (React Native)

Create a simple React Native application that will check a user-entered PIN against a hardcoded correct value of "00000". If the correct PIN is entered, the app will make a GET request to retrieve a list of items and store images and videos using the file system. The application will then display the items in a sequential manner and in full screen, with images displayed for 5 seconds and videos for their full length. The app will check the file system every time it runs, displaying the content if it has already been stored, or downloading it if it is not available. The application must be able to work offline if the content has been previously downloaded.

### Breakdown:

1.  Use the latest version of React Native to create the app, you can use either Expo or React Native CLI.
2.  For this exercise, you do not need to build any API logic or make any API requests to authenticate the PIN. Instead, you should hardcode the correct PIN as "00000" and check the user's input against this hardcoded value. If the user enters any other PIN, an error message should be displayed.
3. If the user enters the "00000" PIN, the app should make a GET request to the following URL https://cdn.nowsignage.com/challenge/items.json and retrieve the list of items (in the "items" key) then it should store all the images and videos using the file system.
4.  The app should check the file system every time it runs, if the images and videos are already stored, it will display them and won't make any network request, otherwise, it will download them and store them in the file system.
5.  The app should display the items in a sequential manner and in full screen (images for 5 seconds and video for its length). This means that the first image should be displayed in full screen for 5 seconds, then the video for its length, and then the other image for 5 seconds, before returning to the first image to repeat the sequence.
6.  The app must work in offline mode if the content (images and videos) has been previously downloaded.

### Notes:

-   The app should be well-organized and easy to read.
-   The app should handle errors gracefully, such as when the API request fails.
-   The app should be visually appealing, and should follow best practices for React Native app development.

### Expected Deliverable:
A zip file containing the source code and a short video demonstration of the app, or a Github repository link containing the source code, and a short video demonstration of the app.

### Deadline:
48 hours
