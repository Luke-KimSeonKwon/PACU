*How to use 'pacu SuperEyeTracking ' - written by Luke (SEONKWON, KIM) godmakessky@naver.com
1. Push the button 'window icon' + 'R' on the keyboard, You can see a 'Run' window
2. Put the command 'cmd' on a Terminal window
3. Put the command 'cd C:\pacu'
4. Put the command 'python manage.py runserver'
5. Check the display on command windiw
	Django version 2.0.2, using settings 'pacu.settings'
	Starting development server at http://127.0.0.1:8000/
	Quit the server with CTRL-BREAK.
6. Put the address http://127.0.0.1:8000/upload on your Internet (recomand chrome)
7. And use it

*Notification
1. Upload files such as mat files and npy files saved in your C:\pacu\media folder
   When you are done, delete the upload files in media folder
   For your computer memory
2. The results such as jpeg image files saved in your C:\pacu\result folder  
   When you are done, delete the result files in result folder
   For your computer memory
3. The main pacu  folder must be located in 'C:\'(just put the pacu folder in your 'C drive'
   Check the pacu folder location
   By clicking your mouse right button on your pacu folder
   And Clicking properties
   You can see the pacu folder location
4. First to Fourth parameters please enter the integers
   And Fifth and Sixth parameters please enter the floating numbers

*System Prerequirement
1. Python3.4 - install the python3.4 version on the python webpage
2. Set the System User Path into C:\Python34, C:\Python34\Scripts
3. Python modules - install the numpy module by commanding 'pip install numpy' on a Terminal window
                    install the h5py module by commanding 'pip install h5py' on a Terminal window
		    install the openCV module by commanding 'pip install opencv-contrib-python'
		    install the tiffffile module by commanding like this example First, 'cd C:\pacu\tiffffile_module
                                                                                         (move to your folder that has a 'tifffile-2017.9.29-cp34-cp34m-win_amd64.whl')
                                                                                 Second 'pip install tifffile-2017.9.29-cp34-cp34m-win_amd64.whl'
                    install the pillow module by commanding 'pip install pillow' on the Terminal window
                    install the scipy module by commanding 'pip install scipy' on the Terminal window
                    and the last, install the django by commanding 'pip install django' on the Terminal window
