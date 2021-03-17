# tasks_in_wallpaper
a python program to change your wallpaper with your task list. This program will only work in ubuntu


At first you have to configure the directory of the  svgfile and tasks.md file in the python script:
```py
picture_with_dir = "/home/saadman/Desktop/My_Workspace/wallpaper_change/test.svg" #the path of your test.svg file
tasklist_with_dir = "/home/saadman/Desktop/My_Workspace/wallpaper_change/tasks.md" #the path of your tasks.md file
```

Then u should add tasks in the tasks.md file.

If the task is important, put a star at the end of the task.

If you want to specify time, add " -t {your time}" at the end of the task.

example:

```md
task1
task2*
task3 -t 6:00pm
task4* -t 7:30 pm
```
