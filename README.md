# Octava PRO DSX App
This app allows control of the Octava PRO DSX Video Over IP system.<br>
Allows user to create system for: 20 video source, 40 displays and includes one(1) 2x2 Video Wall.<br>
2x2 Video Wall : <br>
Top Left = RX 0.41 ( 172.41.3.41)<br>
Top Right = RX 0.41 ( 172.41.3.42)<br>
Bottom Left = RX 0.41 ( 172.41.3.43)<br>
Bottom Right = RX 0.41 ( 172.41.3.44)<br>

This app can be uploaded to the PRO DSX TX. Recommend loading to TX 1 ( 172.31.2.1).

Procedure:

1.	Create a Folder. The Folder name must be call “www”

2.	Put the html and associated  files in a directory inside of 'www'folder. 

    Example, placing files in octavaswitch directly inside of 'www' folder

      /www/octavaswitch

      user can access the app by typing in: 172.31.2.1/octavaswitch


3.	Use 7-zip and select tar to compress the 'www' Folder.    (www.tar)

4.	Use 7-zip and select gzip to compress the www.tar.    (www.tar.gz)

5.	Open TX/RX IP/index_update.html   (Ex: http://169.254.3.1/index_update.html)

6.	Select the www.tar.gz than update.

7.	When Update success ,please reboot the device.


Note: The www.tar file size must  (>2M byte)



