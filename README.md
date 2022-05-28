<h1 align="center">Pomodoro timer</h1>
<p align="center">
The Italian word for tomato is Pomodoro. The Pomodoro technique is a time management system that consists of 25-minute spans of focused work separated by 3-to-5 minute breaks and 15-to-30 minute breaks after four work sessions.

By following these instructions, I have made a Pomodoro timer. This was developed as coursework for the [100 Days Of Code](https://www.udemy.com/course/100-days-of-code/?utm_source=adwords&utm_medium=udemyads&utm_campaign=Python_v.PROF_la.EN_cc.ROW_ti.7380&utm_content=deal4584&utm_term=_._ag_85724077624_._ad_535397245836_._kw__._de_c_._dm__._pl__._ti_dsa-774930046209_._li_9069450_._pd__._&matchtype=&gclid=CjwKCAjwyryUBhBSEiwAGN5OCPV3CUOc2OQWyaAVGBrwu9dOxoXnLpF6vqtyd0UcoznnZmAZCxFdMBoCnMMQAvD_BwE) course. I have used 25 minutes of work time in this timer, followed by three 5 minutes of short breaks and a 20 min long break. The timer will start after clicking the **START** button and reset if the **Reset** button is clicked.
</p>
<img align= "middle" src=https://user-images.githubusercontent.com/57942968/170537323-425db6be-fada-40e5-99fd-b567b868f8f2.png>


## Updated

Now we can use the **Pomodoro Timer** as an executable file. To make it an **.exe** file, just follow the following steps:

<li>
First, go to the directory where the python scripts are located. Then on the directory bar, click and type <b>cmd</b>
</li>
	
<li>
Then when the command prompt pops up, install <b>pyinstaller</b> using the following command.
  
	pip pyinstaller

</li>

<li>
When the installation is completed, type the following command.

	pyinstaller --onefile -w -i ICON_NAME.ico SCRIPT_NAME.py
	
"**-w**" command prevents from opening additional **cmd** window while executing the .exe file
"**-i**" command is used for adding icon to the exe file. The icon needs to be in .ico format, otherwise the command line won't work and will show errors.
</li>

<h3 align="center">Happy Coding!</h3>
