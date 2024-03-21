
| **Summary Technical Log**                                 |
|-----------------------------------------------------------|

**Goal:** Get familiar with collection data solutions 
**Status:** In Proccess
**Time expended**         000    

| **Date**              | **Step No**              | **Documentation** |
|-----------------------|--------------------------|-------------------|
| 2024-03-15 13:00:00   | ArcGIS Workforce         | [here](https://fleming.maps.arcgis.com/apps/workforce/projects/13b23d4f37834ed9b7aa03f814078f0e/dispatch/assignments)      |
| 2024-03-15 14:32:00   | End                      |
| 2024-03-20 9:00:00   | KoboToolbox              |       |
| 2024-03-20 10:42:00   | End                      |
| 2024-00-00 00:00:00   | Survey123                |       |
| 2024-00-00 00:00:00   | qfield                   |      |
| 2024-00-00 00:00:00   | field maps               |       |
| 2024-00-00 00:00:00   | End                      |

**Link to this solution:**  
[ArcGIS Workforce](#ArcGIS-Workforce)  
[KoboToolbox](#KoboToolbox)  
[Survey123](Survey123)  
[qfield](qfield)  
[field maps](#field-maps)  


**Next steps:**
Make a website to open the survey and also, display the data.

| **Notes for the process**                                |
|-----------------------------------------------------------|

# ArcGIS Workforce
Tutorial: Link: https://doc.arcgis.com/en/workforce/android-phone/help/create-your-first-project.htm
## Create a project in the Workforce web app
Open Workforce web app from the app launcher in ArcGIS Online
![imagen](../a00templates/img/img134.png)   
Click Create Project.
![imagen](../a00templates/img/img135.png)  
Give a name an summary to the project  
![imagen](../a00templates/img/img136.png)  
### Project Setup
note:  
![imagen](../a00templates/img/img137.png)  
Define Types of assignment  
![imagen](../a00templates/img/img138.png)  
Define roles: Dispatchers create and assign assignments and mobile workers have assigned assignments in your organization or partnered collaboration from other organization.
Tip: Add yourself as a mobile worker so you can test your project in the mobile app before deploying it.
Tip: mobile workers list .csv can be upload add worker from file.
![imagen](../a00templates/img/img139.png)  
### Customize map  
Click in dispatcher/Worker map to modified/add/remove/update  
![imagen](../a00templates/img/img140.png)  
You can upload layers to the dispatcher and then those layers will be available and can be put on the mobile worker map, you can add and edit the layers, customize feature pop-ups and labels. And also, create offline map area  
![imagen](../a00templates/img/img141.png)  
![imagen](../a00templates/img/img142.png)  
![imagen](../a00templates/img/img143.png)  
![imagen](../a00templates/img/img144.png)  
![imagen](../a00templates/img/img145.png)  
![imagen](../a00templates/img/img146.png)  
![imagen](../a00templates/img/img147.png)  
![imagen](../a00templates/img/img148.png)  
### Integrate other Esri apps
Navigator is integrated by default, and Field Maps, Collector, Explorer, and Survey123 can be integrated.
![imagen](../a00templates/img/img149.png)  
-	Integrate ArcGIS Field Maps with existing maps or by defaults.
![imagen](../a00templates/img/img150.png)  
-	Integrate with the project or specific assignment types.
![imagen](../a00templates/img/img151.png) 
## Test the project
Open the project
![imagen](../a00templates/img/img152.png)
Create example assignments.
![imagen](../a00templates/img/img153.png)
![imagen](../a00templates/img/img154.png)
![imagen](../a00templates/img/img155.png)
![imagen](../a00templates/img/img156.png)
![imagen](../a00templates/img/img157.png)
Test the task updated and upload properly
![imagen](../a00templates/img/img158.png)
![imagen](../a00templates/img/img159.png)
![imagen](../a00templates/img/img160.png)


----------------------------------------------------------------------
# KoboToolbox
Link: https://doc.arcgis.com/en/workforce/android-phone/help/create-your-first-project.htm  
This is the interface once you register on the page  
![image](../a00templates/img/img161.png)  
In this link there is the documentation for the use of this solution  
 https://support.kobotoolbox.org/getting-started.html  
![image](../a00templates/img/img162.png)  
For the current purpose, matters concerning data collection will be reviewed.  
![image](../a00templates/img/img163.png)  
### New Project  
Click create new project  
![image](../a00templates/img/img164.png)  
It can be created from scratch, use a template that you have already configured, upload an Excel from your local drive or from the internet with a url  
![image](../a00templates/img/img165.png)  
Creating the project from scratch will ask you to give it a name and other information, then create project  
![image](../a00templates/img/img166.png)  
Initially the project will be empty  
![image](../a00templates/img/img167.png)  
### Add questions  
Ask your first question  
![image](../a00templates/img/img168.png)  
A list of options is presented for the type of response to be answered in the survey question
Multiple choice, number, location, ranking, photo  
![image](../a00templates/img/img169.png)  
Each option will give you more options if applicable, such as the option to select one  
![image](../a00templates/img/img170.png)  
You can also see the preview of how the survey is going or click save to update the changes made or you can also simply click the plus sign to add more questions  
![image](../a00templates/img/img171.png)  
Previous will show you a version of the final presentation of the survey  
![image](../a00templates/img/img172.png)  
Add another question such as Location, you will be able to see in the preview how you can select the location by clicking or searching for the address or entering the coordinates, answering the preview will give you an idea of the experience but you do not enter data  
![image](../a00templates/img/img173.png)  
With sustained control you can select the questions you want to group  
![image](../a00templates/img/img174.png)  
You can add more questions within the group or outside the group, this will also allow you to collapse the questions within the group, the group name can also be edited  
![image](../a00templates/img/img175.png)  
### Questions with special settings  
Create 1. A note, then create questions 2 and 3 and group them  
Open group settings  
![image](../a00templates/img/img176.png)  
In the group configuration options it will allow you to add a button to repeat the question if necessary, this will allow the user to enter more than one answer to this question in the same form, note that there are other configuration options, such as making the answer mandatory  
![image](../a00templates/img/img177.png)  
The preview will show you what a question of this type looks like.  
![image](../a00templates/img/img178.png)  
You can also ask a question only if the previous question meets a requirement  
For example, only show fruit trees if the user says they have fruit.  
![image](../a00templates/img/img179.png)  
In the configuration of the second question, in the Skip logic option you can put a condition  
![image](../a00templates/img/img180.png)  
This condition must add the previous field that determines whether this question will be shown or not and can have several logic operators in this case it is only = yes, if the condition is met, the question we are configuring will be shown  
![image](../a00templates/img/img181.png)  
It will look like a cascading question.  
![image](../a00templates/img/img182.png)  
You can configure that if a question is answered in a certain way, it asks another series of questions and skips them, but to avoid having to configure each question individually by putting the condition in the group  
![image](../a00templates/img/img183.png)  

----------------------------------------------------------------------  
# Survey123

# qfield

# field maps
