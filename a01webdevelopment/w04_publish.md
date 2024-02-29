| **Summary Technical Log**                                 |
|-----------------------------------------------------------|

**Task:** Creating an image and logging in on Google Cloud Platform  
**Software/Application:** ArcGIS Server, Google Cloud Platform  
**Goal:** ArcGIS Server on GCP
**Status:** Ended
  
**Time run successfully** 15 min  
**Time expended**         15 min  
**Link to final product** [NA](http://www.com)  
**No attempt** 01 de 01  
  
  
| **Date**              | **Step No**                                   | **Key/Tip** | **Description/Notes** | **Documentation** |
|-----------------------|-----------------------------------------------|-------------|-----------------------|-------------------|
| 2024-02-29 11:35:00   | Step01_Publish                                | notes       | notes below           | [doc/link](https://www.youtube.com/watch?v=dyFeyBX9jIY)          |
| 2024-02-29 12:20:00   | End                                           |

**Results:**  
A web map was publish

**Next steps:**
Include the map in a web application.

| **Notes for the process**                                |
|-----------------------------------------------------------|

# Step01_Publish
*Assuming DNS for the ip of the VM and certificate was made*  
*Assuming the map project in ArcGIS Pro is done and ready to be published*
1. Start the VM  
![imagen](../a00templates/img/img37.png)
2. Copy the url  
![imagen](../a00templates/img/img38.png)
3. update the DNS domain  
![imagen](../a00templates/img/img39.png)
4. Test the machine is running in your browser  
![imagen](../a00templates/img/img41.png)
5. Test the arcgis server is running  
![imagen](../a00templates/img/img42.png)
6. can also login  
![imagen](../a00templates/img/img43.png)
7. login as administrator  
   :6443 .../manager  
![imagen](../a00templates/img/img44.png)  
![imagen](../a00templates/img/img45.png)
8. start the virtual machine in a remote desktop
![imagen](../a00templates/img/img40.png)
9. make a copy of the project data following the same path make it easier but it can be done in a different path

10. the publication will be done from the pc where ArcGIS Pro is install and the project is ready to be published    
    the VM does not have ArcGIS Pro.  
    Conect the server  
    ![imagen](../a00templates/img/img48.png)
    ![imagen](../a00templates/img/img49.png)
    ![imagen](../a00templates/img/img50.png)
12. publish
    ![imagen](../a00templates/img/img47.png)
for publish the data can be reference to the vm data path or can be copy  
  
| Map Service:    | myCanada                             | myCanada2                               |
| --------------- | ------------------------------------ | --------------------------------------- |
| Descripción:    | Color                                | Grayscale                               |
|                 | ![img](../a00templates/img/img51.png)| ![img](../a00templates/img/img52.png)   |
| Data:           | Copy All Data                        | Reference Registered Data               |
|                 | Data will be copied to this path ⬇   | Means the data in the server has to be specified |
|                 |                                      | reference the data in the validation 24011 fixing |
|                 |                                      | ![img](../a00templates/img/img53.png)   |  
|                 |                                      | same or different path will be depend or where the data in the VM was storege |  
|                 |                                      | ![img](../a00templates/img/img54.png)   |   
|                 | ![img](../a00templates/img/img55.png)| ![img](../a00templates/img/img56.png)   |
|                 | ![img](../a00templates/img/img58.png)| ![img](../a00templates/img/img59.png)   |

now data will be available  

| REST ENDPOINT:  | 
| --------------- | 
| ![img](../a00templates/img/img57.png)    |  
| ![img](../a00templates/img/img60.png)    |  
| ![img](../a00templates/img/img61.png)    |  
