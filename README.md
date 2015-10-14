# i-board
![](http://i.imgur.com/W1zWB5O.png)
**i-board** is a multiple instagram account management app, it helps you to login to multiple instagram accounts from your  iOS or Android device and do various instagram activities like follow, unfollow,comment,like, scheduling posts etc. Its a a very powerful instagram marketing automation app.

Features:
============================

> **Multi accounts manager:** You can manage your multiple instagram accounts and easily switch between accounts without logging in again and again        ![](http://i.imgur.com/1bAINYl.png)
> **Feeds view:** You can check your all updates in this section, long press to save images in external source. ![](http://i.imgur.com/rjlzCT3.png)            
>**Follows:** You can see list of user whom you are following. ![](http://i.imgur.com/f2FfDpY.png) 
> **NonFollowers:** You can check who are all not following you on instagram ![](http://i.imgur.com/iW4oTZ9.png)

> **Photo Que:** upload photo, set time and date, sit back and relax , iboard will remind you to upload it on instagram on one tap. ![](http://i.imgur.com/epXonbP.png) 

> **Followed By:** Tired of tracking followers  from different accounts, one tap to switch between account and check the list of recent followers in all your instagram accounts. ![](http://i.imgur.com/g2knrj7.png) 

>**Fans:** Check the list of users who follows you but you are not following them. Yes it is not same algorithm  which instagarm shows followed-by list. ![](http://i.imgur.com/DcuhJQS.png) 

>**Mutual:** Find out who all follows you as well as you are following them. ![](http://i.imgur.com/na9FIg9.png) 
 
>**PhotoBucket:** See your own media files ![](http://i.imgur.com/0Kozy83.png) 

>**CopyFollowers/Follwed-by:**  Search any user by typing username and get all his/her followers and follwed-by list, then copy to your list by just typing on follow button. ![](http://i.imgur.com/mIoxgMa.png)



Installation guide for android:
============================

The easiest way to build is to install Android IDE, Once installed, then you can import the project into Android Studio:
1. Open File
2.	Import Project
3.	Select iboardpro, instagram library and android support library.
4.	Click OK.![](http://i.imgur.com/d3v3MIJ.png)  ![](http://i.imgur.com/nUBibNz.png)
   


 
 After building the project while running on your device ,you might find that your device doesn't let you install your build if you already have the version from Google Play installed. This is standard Android security as it it won't let you directly replace an app that's been signed with a different key. Manually uninstall iboardpro from your device and you will then be able to install your own built version.
 
 Installation guide for iOS:
============================

1. Extract the downloaded i-boardpro.zip file.
2. Open the i-boardpro folder,you will find i-boardpro.xcodeProject file and double click on that folder to open Xcode. ![](http://i.imgur.com/lpEMsn2.png)
3. Click on project file from Project navigator and click on the i-boardpro under the Targets. ![](http://i.imgur.com/aAnc59y.png) 
4. Click on General , set the proper Bundle Identifier and go to Build settings menu, change Provisioning profile under Code Signing. ![](http://i.imgur.com/YrlK4kv.png) ![](http://i.imgur.com/Ko7cI1i.png)
5. Go to webViewViewController and set the client_id,redirectUrl and client_secrete. 
6. Build and run the application. ![](http://i.imgur.com/wJZCtRk.png) 



Guide to create app in Instagram developer console:
==================================================
1. Go to https://instagram.com/developer/
2. Click on Manage clients  ![](http://i.imgur.com/ya3i3O5.png)
3. Click on "Register new Client" ![](http://i.imgur.com/xsoZnHQ.png)
4. Fill the dtails of your application in given form and click on register. ![](http://i.imgur.com/P86z2to.png)
5. Copy client id,client-secret and redirect url and paste it in ApplicationData.java file inside android application.
   ![](http://i.imgur.com/NVlwoNu.png)

For android
![](http://i.imgur.com/Ysa11eL.png)

For ios
![](http://i.imgur.com/VA0xEav.png)

