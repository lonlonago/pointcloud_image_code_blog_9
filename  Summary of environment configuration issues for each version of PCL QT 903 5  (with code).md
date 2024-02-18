#  Resource download 

Here are the versions of PCL I have compiled. Pay attention to the corresponding relationship: 

##  1、vs2015 -pcl1.8.1 - qt5.12 -vtk8 

 The oldest version 

PCL 1.8.1 is too long, the computer can't be found. 

##  2、 vs2019-pcl 1.11.1-qt 5.12-vtk8.2 

 Personally, I think the best version is qt5 + pcl1.11. 

##  3、 vs2019-pcl1.12.1-qt 6.2.4-vtk9.1 

QT6 + pcl1.12 version 

##  4 、vs2022-pcl1.13.0-qt 6.2.4-vtk9.2 

QT6 + pcl1.13 version 

#  Version 

##  1、 vs2015 -pcl1.8.1 - qt5.12 -vtk8 

Test case: pcl 1.8.1 test case 

##  2、 vs2019-pcl 1.11.1-qt 5.12-vtk8.2 

Test case: pcl 1.11.1 test case 

##  3、 vs2019-pcl1.12.1-qt 6.2.4-vtk9.1 

Test case: 

PCL 1.12.1 Test Case 

##  4 、vs2022-pcl1.13.0-qt 6.2.4-vtk9.2 

Test case: 

PCL 1.13.0 Test Case 

##  5. Configure the process yourself 

Refer to the online configuration PCL1.12 + VTK9.1 + QT6 

##  6. Simple configuration tutorial 

###  1. Download the corresponding version I compiled 

![avatar]( 8a15c78abdef44dfad54dcf80801fb1d.png) 

 Take pcl 1.13.0 as an example, pay attention to the corresponding version relationship between qt and pcl   

###  Change the corresponding path 

Open environment variables and change the path of OpenNI2 first 

![avatar]( 4c130df3ec7d4a1f8c88e802a2426dca.png) 

![avatar]( 9dc38d48cd154ce4bcc1e61ed15d10ab.png) 

 Continue to modify the path in the system path and change it.  

#  III. Precautions after upgrading QT6 

##  1. PCL1.12, 1.13 version pointer release problem 

###  PCL pointer release issue 

VS solution: pcl memory release QT solution: pro file added 

>  QMAKE_CXXFLAGS += /arch:AVX 

##  2. VTK display problem in QT6 

The following is the display of PCL in QT, which is slightly different from QT5. 

###  Display Code QVTKOpenGLNativeWidget PCL 1.12 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
###  Display Code QVTKOpenGLNativeWidget PCL 1.13 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
###  Window display controls QVTKOpenGLNativeWidget 

![avatar]( 65f44e61c9954a32b30ae4699af7e0f9.png) 

###  pro file 

If an error is reported, it may be that the following is not added! 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
##  3, QT6 PCL display window QVTKOpenGLNativeWidget not updated 

###  pcl1.12 

Each time you add a point cloud, add the following first: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
Or (recommended): 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
full display 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
Recommend this method: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
###  pcl1.13 

Each time you add a point cloud, add the following first 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
Or (recommended): 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
full display 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
recommend 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
##  3. Viewing angle display problems in PCL1.12 and 1.13 

 The viewing code in qvtkwidgets is as follows: 

viewing angle settings 

However, in the QVTKOpenGLNativeWidget, change the code will appear out of thin air a window, temporarily did not find the reason, so directly with VTK source code to change the perspective, without PCL calls, the main code is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573794740
 ```  
