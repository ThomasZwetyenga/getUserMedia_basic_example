# getUserMedia_basic_example
Take pictures from smartphone/computer web browser (Google Chrome, Firefox, Safari, etc) with getUserMedia in Full Screen.

This example only use one HTML page also containing JavaSript/JQuery.

## HTTPS
⚠️ This will only work using HTTPS and after the user allowed the use of the camera.
  
  If for test reasons, you cannot get HTTPS, you can use Google Chrome and go to chrome://flags
  
  Then you can add the website address to #unsafely-treat-insecure-origin-as-secure 
  
  Never use that for any other website than your own.

## Camera / Picture dimensions
I left default camera dimensions so it could be tested on any device.
You may have to add width height values to video and img elements.
The taken picture has the dimensions 480 * 640. You'll have to change it too.

## Some customization
By default, the front camera is used. To use the rear camera, please uncomment the line:

//video: { facingMode: { exact: "environment" } }

On smartphones, you can choose the Full Screen orientation. For example, you can uncomment:

//screen.orientation.lock("landscape");
