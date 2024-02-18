#  foreword 

Fully refer to the aforementioned ICP-related registration settings 

#  First, the core code 

The code is opposite the ICP point, as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573819299
 ```  


--------------------------------------------------------------------------------

#  foreword 

The layout is as shown in the previous sections: 

#  First, the core code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573841476
 ```  


--------------------------------------------------------------------------------

#  First, the effect display 

![avatar]( f6ce284232154f4482b887536f5a1d5f.gif) 

#  QT Settings 

![avatar]( 0e74f0705d874f24abdf8aa3c7258aa0.png) 

#  III. Core Code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573844989
 ```  


--------------------------------------------------------------------------------

#  First, the effect display 

![avatar]( d7edb7feef584bfdab15fc2a2d6c49f9.gif) 

 This section continues to add the CPC algorithm, with the following effects:  

#  II. Core Code 

The CPC code in the PCL is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957378057
 ```  
#  III. QT Settings 

1. Set in ui, according to the settings in the demonstration. 2. pcl_function, add the core code 3. In mainwindow, add the slot function as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 202402030957378057
 ```  
Qmake, build it and run it. 

#  follow-up 

The next chapter adds the minimum cut. 



--------------------------------------------------------------------------------

#  First, the effect display 

This section implements point cloud LCCP segmentation. The segmentation principle refers to LCCP + CPC. The effects are as follows: 

#  II. Core Code 

The core code of LCCP segmentation in PCL is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573789891
 ```  
Note that after the LCCP is divided in PCL, just add a Label to each point, and then you need to extract each class according to the label yourself. 

#  III. Interface Settings 

1, ui settings, according to the required parameters set by themselves 2, pcl_function settings, add LCCP code pcl_function, as follows, according to the label extraction point cloud set by themselves, you need to private me. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573789891
 ```  
3. Mainwindow settings, add relevant header files and parameter functions in mainwindow. And connect the action to the slot function. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573789891
 ```  
Qmake, just build it. 

#  follow-up 

The next chapter continues with CPC segmentation 



--------------------------------------------------------------------------------

#  First, the effect display 

![avatar]( 946c63d9833f4af89d44687bc77f9856.gif) 

 This section continues to add point cloud area growth segmentation, one of the commonly used segmentation methods for point clouds, with the following effects:  

#  II. Core Code 

The region growth segmentation code in PCL is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573831712
 ```  
#  III. Interface Settings 

1. UI settings, you can set the dialog according to the demo in the figure, determine the number of parameters according to the core code, and set the layout according to your own style. 2. pcl_function module, the code is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573831712
 ```  
3. The setting slot function in mainwindow is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573831712
 ```  
Qmake, build it, and it can be run. 

#  follow-up 

![avatar]( ac06d99b204a48d4a74ae9c33fad5433.png) 

 The relevant properties are shown in the parameter list in the next section Implementing LCCP segmentation. 



--------------------------------------------------------------------------------

#  First, the effect display 

![avatar]( 2101d0061f3f460fb4dc71deaae21ed5.gif) 

 In this section, the circular segmentation of point clouds in PCL is realized. The specific effects are as follows.  

#  II. Core Code 

The core code of circular segmentation in PCL is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573823768
 ```  
#  III. QT Settings 

1. UI settings. According to the core code, set the number of parameters that need to be passed to carry out ui layout. 2. Since there are few circular segmentation codes, it is not added to the pcl_function, but directly added to the relevant slot functions in the mainwindow. Remember to add relevant header files, actions in the menu bar, etc. The implementation of slot functions is mainly as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573823768
 ```  
Qmake, build it and run it. 

#  follow-up 

![avatar]( 479388e50c0040618dfd16f49f013644.png) 

 The desired result can be displayed in the parameter section, such as radius, circular equation, etc. As follows: The next section implements point cloud cylinder segmentation. 



--------------------------------------------------------------------------------

#  First, the effect display 

![avatar]( f097aabc61cf4f9b9322a92162308cb0.gif) 

 In this section, add a cylindrical split section to the QT, with the following effect:  

#  II. Core Code 

The cylindrical segmentation code in PCL is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573884867
 ```  
#  III. QT Settings 

1. UI settings, according to the number of parameters required to pass the core code, the parameters are passed, and the layout is set by itself. You can refer to the filtering sections. 2. The segmentation code is implemented in the slot function, and it is necessary to add action to connect with the slot function. The slot function code is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573884867
 ```  
Qmake, build it, you can achieve cylindrical segmentation. 

#  follow-up 

![avatar]( 8106625113c84320ac95bfefb1123a54.png) 

 1. The point cloud cylindrical equation or the core parameters can be displayed in the parameter section, as follows: 2. The next section implements Euclidean clustering. 



--------------------------------------------------------------------------------

#  First, the effect display 

![avatar]( d31cd2ff120f49b3b94cdb6091084226.gif) 

 In this section, add PCL's European clustering segmentation module to the software, the effect is as follows, and the segmentation effect is better for scattered objects.  

#  II. Core Code 

The EC partition code in PCL is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573845219
 ```  
#  III. QT Settings 

1. UI layout, set according to the number of parameters required in the core code, and the layout is developed according to your own preferences. 2. The code in the pcl_function is as above, which is the core code. 3. Mainwindow settings .h file adds relevant header files, .cpp adds action, and connects with the slot function. The slot function is implemented as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573845219
 ```  
Qmake, build it, and you can perform related operations. 

#  follow-up 

![avatar]( ac611aa06ebf481283834d71920f9f49.png) 

 Relevant parameter settings, the next section continues with regional growth clustering. 



--------------------------------------------------------------------------------

#  foreword 

#  First, the effect display 

![avatar]( 4f196f0028fb4eab890a2fba61f783e5.gif) 

#  II. Core Code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573867358
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573867358
 ```  
#  III. QT Settings 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573867358
 ```  
 1).h file 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573867358
 ```  
 2).cpp file 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573867358
 ```  
#  IV. Conclusion 

![avatar]( b20e96d20b5b4211bf4ff8af8430eefd.png) 

![avatar]( 0e1fecda0288418796d7e3bd0a739dd6.png) 



--------------------------------------------------------------------------------

#  First, the effect display 

In this section, add a planar segmentation module to QT 

#  II. Core Code 

The planar division in PCL is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573812567
 ```  
#  III. QT Settings 

1. UI settings, determine the number of transmission parameters according to the core code, and set the layout according to your own preferences. 2. Add the menu bar action yourself to realize the connection with connect. The segmentation function is implemented in the slot function. The slot function code is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573812567
 ```  
Qmake, build it, that is, complete the relevant operations. 

#  follow-up 

![avatar]( 78f85127b12942e9b9dbbb87c295d6a9.png) 

 1) Set the relevant plane equation in the parameters as follows:  

2) The next section implements cylindrical segmentation. 



--------------------------------------------------------------------------------

#  First, the effect display 

![avatar]( 290d7b0098854b0ba869e2698434aa81.gif) 

 Today, the PCL line detection module is integrated into the QT, and the results are as follows:  

#  II. Core Code 

The line division module in PCL is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573824320
 ```  


--------------------------------------------------------------------------------

#  First, the effect display 

![avatar]( ed679eb45798449a88ca9ea2c975d867.gif) 

#  II. Core Code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573899515
 ```  
Different display methods: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573899515
 ```  
#  III. QT layout 

Reference filter section related settings 



--------------------------------------------------------------------------------

#  First, the effect display 

![avatar]( d6f52e1d46ee4b8da5f2b85b9df3b8bb.gif) 

#  QT layout 

![avatar]( ac87fbca5a78465b9c4564c288545ff9.png) 

#  III. Core Code 

Poisson reconstructed code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573878602
 ```  
#  other 

1. Build the relevant signals and slots, and pass several parameters to the following function. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573878602
 ```  


--------------------------------------------------------------------------------

#  First, the display effect 

According to the previous article GROR Replica, today it is integrated into QT software 

![avatar]( 4bbfc768d1304a6f8ec4f9e4f4d02479.gif) 

#  II. UI design 

![avatar]( c4127feca4d940f6a6391aac0bfb3392.png) 

#  III. Code 

##  3.1 Adding code 

![avatar]( 65be76fa59134ead855956c7ac11d6ce.png) 

 The header file and source file of qt still add relevant code.  

![avatar]( aa6b9abad12f4a5daa7b7a0c108533ee.png) 

Among them, if there is a function conflict, change it to an internal connection function and add inline. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573744016
 ```  
The function implementation code is as follows: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573744016
 ```  


--------------------------------------------------------------------------------

#  First, the effect display 

![avatar]( cd82d012c416431db4b8943379c918bf.gif) 

#  UI design 

![avatar]( 7102135a708e437abf9d0dad3a649acf.png) 

#  III. Source code 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573799290
 ```  
 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573799290
 ```  
#  IV. Reference 

Refer to "PCL + QT" demo 



--------------------------------------------------------------------------------

#  effect display 

![avatar]( 3b240df951194ba49c1113eb31c02e94.gif) 

#  key code 

##  Corresponding to Qt6 and pcl1.13 

click 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573736873
 ```  
box selection 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573736873
 ```  
##  Corresponding to Qt6 and pcl1.12 

##  Corresponding to Qt5 and pcl1.12 

##  Corresponding to Qt5 and pcl1.11 

#  resource 

Follow-up updates! 



--------------------------------------------------------------------------------

#  I. Introduction 

 1. The problem 

![avatar]( f19fc9bd652c4c749a03acfbc2b97728.png) 

 2. Solution 

Take the addition of the tree control source code as an example, and add simple filtering operations and registration operations. The final effect is such as the effect display part. 3. Main functions 

 4. Final result 

Final source code download 

#  Effect display 

![avatar]( 459c038c0e25420aad040845b92d3d04.gif) 

#  III. Interface layout 

Reference: QT PCL Voxel Filtering 

QT PCL point cloud registration 

#  IV. Code 

The code part only has two points: 1. Select point cloud operation 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573749485
 ```  
2. Registration - how to select multiple items 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573749485
 ```  
![avatar]( 2b8199fe510448a0b6b03972aa182aaf.png) 

over!!! 



--------------------------------------------------------------------------------

#  First, the effect display 

![avatar]( a2636bb8a2f444ddbed4eb26ca728841.gif) 

#  Code settings 

##  2.1 UI Settings 

![avatar]( da754043998b4351b06bb1c303ae7401.png) 

 Create an action in the toolbar and go to Slot Functions.  

##  2.2 Code Settings 

Take the top view as an example and adjust the camera's viewing angle. 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309573749844
 ```  
![avatar]( 739840a43cfe476a8745ce36877b8c5e.png) 

OVER！！！ 



--------------------------------------------------------------------------------

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


--------------------------------------------------------------------------------

