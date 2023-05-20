# Image_Target
Image Target project that uses augmented reality to display 3D objects on the 2D images
-------------------------------------------------------------------------------------------------------------------------------------------------------------
PROJECT DEMO:

Follow these steps to checkout this project :

https://github.com/Priyal-tech/Image_Target/assets/76651983/6205b288-214b-4bdc-9eb3-07e151bb8273

--------------------------------------------------------------------------------------------------------------------------------------------------------------
1) Clone the folder
2) Download Vuforia sdk using link https://developer.vuforia.com/downloads/sdk?_=1684552394 or
Go to link https://developer.vuforia.com/ then > Downloads > Add Vuforia Engine to a Unity Project or upgrade to the latest version add-vuforia-package-10-15-4.unitypackage (139.57 MB) , login to Download
3) Drop and drag vuforia package downloaded in step2 and garden package downloaded in step 1 to assest folder of unity.
---------------------------------------------------------------------------------------------------------------------------------------------------------------

CREATING FROM BEGINNING:

Inorder to CREATE Image target using Augmented Reality , downloads required are:
1) Download UNITY 
2) Download a clear image in .jpeg or .jpg format
3) Download a 3d model (.fbx recommended) use https://sketchfab.com/search?type=models to find 3d models
4) Download Vuforia sdk using link https://developer.vuforia.com/downloads/sdk?_=1684552394 or
Go to link https://developer.vuforia.com/ then > Downloads > Add Vuforia Engine to a Unity Project or upgrade to the latest version add-vuforia-package-10-15-4.unitypackage (139.57 MB) , login to Download
---------------------------------------------------------------------------------------------------------------------------------------------------------------

After downloading the packages , follow these steps to create a image target using Augmented Reality:
1) Open unity hub> create a new 3d core project> select a name for the project. THe project will be opened in the unity.
2) In the Projects window, drop and drag vuforia package download number - 4 into assets folder > click import. (#vufoia folder is now created#)
3) Go to vuforia porrtal > Develop > Licensce Manager > Get Basic > Double click on the licensce key to copy.
4) In the hierarchy window (at the topmost left corner) in unity , right click and select open unity within vuforia Engine > AR camera.
5) Select AR camera and in the Inspector window (at the rightmost corner) in unity . select open vuforia engine configuration > Paste the licensce key copied from vuforia portal.
6) Go to vuforia porrtal > Develop > Target Manager > Add Database > Name database and select Device > open database > Add target >Select the image downloaded 2
7) In Unity , Drag and drop downloaded database into assest folder and click import also drop the .fbx model into assest folder.
8) In the hierarchy window (at the topmost left corner) in unity , right click and select open unity within 3D objects > Image Target.
9) Click on the Image target , under the inspector tab > Image Target Behaviour Type : change from image to database . select your database name.
10) Under image target drop .fbx model and now push play button to jump from Scene to Game and finally you can show image to track and import targetted image.

---------------------------------------------------------------------------------------------------------------------------------------------------------------
