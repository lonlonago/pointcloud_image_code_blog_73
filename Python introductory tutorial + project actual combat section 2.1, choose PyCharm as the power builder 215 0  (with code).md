directory 

2.1.1 pycharm Introduction 2.1.2 pycharm Installation 2.1.3 Configuring Python Interpreter 

##  2.1.1 PyCharm 

PyCharm is an IDE tool designed for Python development, providing many features to help programmers improve development efficiency, such as code debugging, syntax highlighting, code jumping, auto-completion, and smart prompts. 

>  IDE is the abbreviation of Integrated Development Environment, that is, integrated development environment. The so-called integrated development environment refers to a power builder that integrates code writing, compilation, and debugging functions. 

PyCharm is divided into a commercial version and a community version. The commercial version is paid for. The community version is aimed at learners in the Python community. The features it provides are not much different from the commercial version. Generally speaking, using the community version can meet the development needs of most programmers. 

##  2.1.2 PyCharm installation 

Download page of PyCharm Community Edition: Download PyCharm: Python IDE for Professional Developers by JetBrains 

The download page is shown below: 

![avatar]( befc9af8bdb085fac71b416bc59a8b79.png) 

Directly click the download button under English Commuity to download the community version of PyCharm. After downloading, directly click the icon to install. 

>  This tutorial is explained in the 2021.1 version of PyCharm Community Edition. Please download the corresponding version on the official website. 

##  2.1.3 configure the Python interpreter 

After installing Pycharm, you need to configure the IDE and add the Python interpreter to the IDE. Now please follow these steps: 

(1) Click on the PyCharm icon on the desktop 

After clicking on the PyCharm Community Edition 2021.1 icon on the desktop, the following window will appear: 

![avatar]( 3fa9949d53e8a155dea2525e891031de.png) 

Tick I confirm that I have read and accept the terms of this User Agreement, and click the Continue button. The following welcome window will appear: 

![avatar]( 50d53e91a1aa991f9e4d34200d8fb358.png) 

In this welcome interface, click Projects to create or open a Python project, and click Customize to customize the theme, fonts, and global configuration of the IDE. 

(2) Configuring the Python interpreter 

Click on the Customize menu of the welcome interface and the following panel will appear: 

![avatar]( 93074d463c72a6548b079fee730437d4.png) 

Clicking Configure... in the panel will bring up the following configuration window: 

![avatar]( 73fd6a204644b4bc2cf89612adba3101.png) 

Click on Python Interpreter in the navigation menu on the left side of the page, then click on the drop-down box Python Interpreter in the right window, and you will see a Show All... option: 

![avatar]( 8a32e979c10f4341ae6a075e301199b9.png) 

In the small window that pops up later, click the + button in the upper left corner: 

![avatar]( 14662c920b74a3ebf02c6b2e43aa4c2f.png) 

After clicking the + button, PyCharm will automatically add the Python interpreter, as shown in the following figure: 

![avatar]( 051d2924be9d6828bca3af8a40a2beb1.png) 

The Base interpreter in the blue box is used to configure the Python interpreter. If PyCharm is not automatically added, you need to manually configure the absolute path of the Python interpreter. Continue to check Make available to all projects under the Base interpreter, and then click the OK button at the bottom right. PyCharm will automatically create a virtual environment for Python. After the creation is successful, the window shown in the following image will appear: 

![avatar]( eb0dd012d76a60d61e422fed62f2589b.png) 

Finally, click the OK button in all the windows that appear. After the operation is completed, it will continue to return to the welcome interface: 

![avatar]( 8c722b7160743c1a27bad0c5d5a45338.png) 

Click New Project in the Projects panel to create a new project. The following image shows the configuration window for the new project: 

![avatar]( d73e50ec22eea684f3ecd7fead5f01b8.png) 

The reader can rename the project name in the Location column, or choose not to create the project's main.py file. After clicking the Create button at the bottom right, the project is created successfully: 

![avatar]( b88ad31c1de29bea3e30ac1c8ce360cf.png) 

(3) Test the execution of Python programs 

 Right-click in the left column of the project window and click New, Python File in turn: 

![avatar]( c448894aacc71a01fbd04cb76310d720.png) 

Enter the name of the Python script file in the window shown below: 

![avatar]( 51ba4dd71d0815d3ca542d69358ca8a0.png) 

After entering the file name, press the Enter key on the keyboard, and finally enter the following code in the file: 

![avatar]( d21fb4521dbf07b75ff66754b0e3a650.png) 

Press CTRL + SHIFT + F10 shortcut to run the Python script directly in the current window. After the program is executed, the output of the program can be seen in the bottom output window of PyCharm: 

![avatar]( 88f601fff8cbb4fe738019f1102957e9.png) 

##   Systematic learning of Python 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 

