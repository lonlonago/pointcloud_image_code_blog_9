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

