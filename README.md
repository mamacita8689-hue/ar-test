# ar-test

A small WebAR experiment built with A-Frame and MindAR.

The project recognizes an image target with the camera and displays a video over it. When the target is lost, the video stops.

## How to run

1. Open the project in a browser through a web server.
2. Allow camera access.
3. Point the camera at the target image.
4. The video should appear over the recognized image.

## Main files

- `index.html` — main page and WebAR logic.
- `marker.jpg` — target image.
- `targets.mind` — compiled image target for MindAR.
- `unicorn.webm` — video displayed in AR.

## Technologies

- HTML
- A-Frame
- MindAR
