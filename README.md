# Asp.NetCore-Cropper.Js
This repository contains the project to Crop images  in an ASP.Net Core application on Client Side Browser using Cropper.Js

•	The 'use strict' statement is used to enable strict mode in JavaScript, which catches common coding mistakes and restricts certain actions to improve code quality.

•	The 'Cropper' and 'URL' variables are defined. The 'Cropper' variable is used to store the Cropper object, which is used to manipulate the image, and the 'URL' variable is used to store the URL object, which is used to create URLs for the image.

•	The 'container' variable is used to select the container element that contains the image.

•	The 'image' variable is used to select the image element that will be cropped.

•	The 'download', 'actions', and various 'data' variables are used to select elements that will be used later on in the code.

•	The 'options' object is used to set up the options for the cropper, including the aspect ratio, preview, and various events such as 'ready', 'cropstart', 'cropmove', 'cropend', and 'crop'.

•	The 'cropper' variable is used to create a new Cropper object, passing in the 'image' and 'options' variables.

•	The 'originalImageURL' variable is used to store the URL of the original image.

•	The 'uploadedImageType' variable is used to store the type of image that is uploaded.

•	The 'uploadedImageURL' variable is used to store the URL of the uploaded image.

•	The $('[data-toggle="tooltip"]').tooltip(); line sets up a tooltip that is triggered when the user hovers over an element with the 'data-toggle' attribute set to 'tooltip'.

•	The $('button[data-method="getCroppedCanvas"]').prop('disabled', true); line disables the 'getCroppedCanvas' button if the canvas element is not supported by the browser.

•	The $('button[data-method="rotate"]').prop('disabled', true); and $('button[data-method="scale"]').prop('disabled', true); lines disable the 'rotate' and 'scale' buttons if the browser does not support CSS transitions.

•	The if (typeof download.download === 'undefined') line disables the download button if the browser does not support the 'download' attribute.

•	The actions.querySelector('.docs-toggles').onchange function is triggered when the user interacts with a checkbox or radio button in the 'docs-toggles' element.

•	The actions.querySelector('.docs-buttons').onclick function is triggered when the user clicks a button in the 'docs-buttons' element.

•	The document.body.onkeydown function is triggered when the user presses a key on the keyboard.

•	The inputImage.onchange function is triggered when the user selects an image to upload.
