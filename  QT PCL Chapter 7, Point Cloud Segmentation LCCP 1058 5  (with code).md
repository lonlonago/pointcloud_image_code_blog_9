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

