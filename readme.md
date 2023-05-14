# Video Player Web Application

This is a web application that enables users to play a video file using a custom video player. The project consists of two parts: a frontend application and a backend server. The frontend application is responsible for displaying the video player and sending a request to the backend server to retrieve the video file. The backend server streams the video file to the client in chunks to enable efficient and responsive playback.

## Technologies Used

The project uses the following technologies:

- **Express.js**: A Node.js web application framework used to build the backend server.
- **cors**: A middleware package used to enable cross-origin resource sharing (CORS) between the frontend and backend applications.
- **fs**: A Node.js module used to read the video file from disk.
- **HTML5 video player**: A built-in HTML5 feature used to display the video player in the frontend application.
- **JavaScript Fetch API**: A web API used to send HTTP requests from the frontend application to the backend server.

## Getting Started

To get started with the video player web application, follow these steps:

1. Clone the repository to your local machine:

```
git clone https://github.com/deepthapliyal/Video-Streaming-with-Node-js.git
```

2. Install the dependencies for the backend server:

```
cd Backend
npm install
```

3. Start the backend server:

```
node index.js
```

4. Open the `index.html` file in your browser to access the frontend application.

5. Press the play button in the video player to start playing the video.

## Usage

The video player web application provides a user-friendly interface for playing video files. Users can play, pause, adjust the volume, and toggle full-screen mode using the video player controls. The video is streamed in chunks from the backend server, which enables efficient and responsive playback.

## Roadmap

Some potential improvements for the video player web application include:

- **Support for multiple video formats**: Currently, the application only supports the MP4 video format. Adding support for additional video formats, such as WebM or AVI, would be beneficial.
- **Improved error handling**: The application currently displays a generic error message if an error occurs during video playback. Displaying more specific error messages to assist users in resolving issues would be helpful.
- **Video playback controls**: The application currently only supports basic video playback controls (play/pause, volume, and full-screen). Adding additional playback controls, such as rewind and fast-forward, could enhance the user experience.

## Contributing

Contributions to the video player web application are welcome. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/bugfix/issue:
```
git checkout -b your-branch-name
```
3. Implement your changes.
4. Push your changes to your branch:
```
git push origin your-branch-name
```
5. Create a pull request on the original repository.

## License

The video player web application is released under the [MIT License](https://opensource.org/licenses/MIT).
