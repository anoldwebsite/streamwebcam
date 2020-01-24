# streamwebcam

Using Express socket.io and opencv4node.js strream your webcam on localhost

On Windows:

1. Download and install node
2. Download VS Code.
3. Open Power shell as admin and type command given after colon and press enter: set OPENCV4NODEJS_DISABLE_AUTOBUILD=1
4. Install the developer tools using (npm install --global windows-build-tools) using Windows Powershell with admin rights.
5. Download cmak and install it from here https://cmake.org/download/ and then restart your computer.
6. set OPENCV4NODEJS_DISABLE_AUTOBUILD=1 in terminal on Visual Studio Code
7. In VS Code on terminal type npm install --save opencv4nodejs and press enter. This will take a lot of time so be patient.

On Mac:
export OPENCV4NODEJS_DISABLE_AUTOBUILD=1

1. Download and install node
2. Download VS Code.
3. Open a terminal and type: export OPENCV4NODEJS_DISABLE_AUTOBUILD=1
4. brew update
5. brew install opencv@4
6. brew link --force opencv@4

Built following video tutorial by Cody Seibert: https://www.youtube.com/watch?v=qexy4Ph66JE

If you face issues with the installation of opencv4nodejs have a look at these instructions https://gist.github.com/adwellj/61e7f202bcfe5b96f312293e9c812ca6
