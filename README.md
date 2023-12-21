# MinGW
GCC - MinGW (Minimalist GNU for Windows)

Download: [CTOOLS](https://1drv.ms/u/s!ArNqTPJsXPC9hKkCvEeGrXbhuosA_g?e=GUvrtf)

## Installing GCC on windows

To use GCC on operation system on Windows, we actually use a minimalist GNU (the MinGW). After Downloading the CTOOS, extract it on C:.

![image](https://user-images.githubusercontent.com/58916022/205927227-8ec69d47-a7d5-45fb-8ee5-63dcccb7fee6.png)

Type in the 'env' in the Windows search bar. You will be able to edit the Environment Variables (see next image).

![image](https://user-images.githubusercontent.com/58916022/205927627-286374b5-f4a9-45e4-994f-bf8bf401603c.png)

Then click in the variable 'Path' and then Edit...

![image](https://user-images.githubusercontent.com/58916022/205927746-cb4fed0b-d763-4afb-9a4d-1e68b6e50233.png)

Add the following paths:

![image](https://user-images.githubusercontent.com/58916022/205927813-2b5a6e54-0fe9-41ac-a14c-c40129525eeb.png)

It's possible to test just running the 'gcc' command line the Command Prompt (type cmd in the search bar).

![image](https://user-images.githubusercontent.com/58916022/205927993-75bfc920-5bd0-4974-a51e-d37202a25381.png)

## Creating a host project

**That is an example and can be used to all host projects inside STM32CubeIDE.**

Go to File -> New -> C/C++ Project.

![image](https://user-images.githubusercontent.com/58916022/205923420-43bcf662-971d-4883-8909-6585f5d97769.png)

Then choose the option C Managed Build and click Next >.

![image](https://user-images.githubusercontent.com/58916022/205923606-4fdf31b7-ae01-4472-ab02-dcdc0b916cca.png)

Give the project a name and choose the MinGW GCC compiler and click Finish.

![image](https://user-images.githubusercontent.com/58916022/205923768-63ad66b0-33aa-4cbf-9e3c-258756a0cea2.png)

Right click in the project (inside the Project Explorer window) and go New -> Source File to create a new source file.

![image](https://user-images.githubusercontent.com/58916022/205923983-6409d174-eb3c-468c-8a70-fb9b95f7809e.png)

Type its name and do not forget to add its extension (.c).

![image](https://user-images.githubusercontent.com/58916022/205924151-9311b4ea-3d6a-4b97-93f3-f70b07650058.png)
