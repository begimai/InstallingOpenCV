![OpenCV logo](http://1.bp.blogspot.com/-QSMSic3f_j8/TbwFSb4fJAI/AAAAAAAAAKk/zMNELOGe1_E/s1600/logoweblarge640_480.png)




# Install OpenCV-Python in Windows
Most tutorials on installations I found online were only for Python 2.7, 
so I decided to help others in installing latest versions.


## What we need
* ## Python 3.6

    First of all we have to install Python itself. The latest stable version for 13th of May is Python 3.6, There are [32-bit](https://www.python.org/ftp/python/3.6.1/python-3.6.1.exe) and [64-bit](https://www.python.org/ftp/python/3.6.1/python-3.6.1-amd64.exe)

    Start the installer and select **Customize installation**

    On the **Optional Features** leave all the optional features checked

    On the **Advanced Options** screen make sure to check **Add Python to environment variables** and **Precompile standard library**. I would recommend to customize installation location to **"C:\Python36"** since it will make your life easier later on

    When you are done go to _cmd_ and type **`python`**. If it says **'python' is not recognized as an internal or external command, operable program or batch file.**, then do following:

    1. Go to system properties -> Advance ( or type "system env" in start menu.)

    2. Click environment variables

    3. Edit the 'PATH' variable

    4. Add 2 new paths _'C:\Python36-32'_ and _'C:\Python36-32\scripts'_

    5. Run _cmd_ again and type python.

* ## NumPy

    Here is a [link](http://www.lfd.uci.edu/~gohlke/pythonlibs/#numpy), where you can download NumPy.

    I have choosen _numpy‑1.13.0rc1+mkl‑cp36‑cp36m‑win32.whl_, because my Python was 32-bit

    Navigate your **cmd** to Downloads folder and type **pip install numpy-1.13.0rc1-cp36-none-win32.whl**

    You have to see **Successfully installed …** message after this command.

* ## OpenCV

    Install from [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv)

    I would recommend **opencv_python‑3.2.0‑cp36‑cp36m‑win32.whl**

    Navigate your **cmd** to Downloads folder and type **pip install opencv_python‑3.2.0‑cp36‑cp36m‑win32.whl**

    After **Successfully installed …** message, you are ready to go to **IDLE Python** and type:

    **`import cv2`**

    **`print(cv2.__version__)`**

# Congratulations! Now you can start your amazing projects!!!!
