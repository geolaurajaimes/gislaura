| **Summary Technical Log**                                 |
|-----------------------------------------------------------|

**Task:** Creating an image and logging in on Google Cloud Platform  
**Software/Application:** ArcGIS Server, GCP  
**Goal:** ArcGIS Server on GCP
**Status:** Ended
  
**Time run successfully** 30 min  
**Time expended**         420 min  
**Link to final product** [www.com](http://www.com)  
**No attempt** 03 de 03  
  
  
| **Date**              | **Step No** | **Key/Tip** | **Description/Notes** | **Documentation** |
|-----------------------|-------------|-------------|-----------------------|-------------------|
| 2024-02-27 13:00:00   | Step01_Create VM | notes       | notes                 | doc/link          |
| 2024-02-27 16:00:00   | Step01_step | notes       | notes                 | doc/link          |  

    
**Results:**  
 

**Next steps:**

# Notes for the process
This process starts assuming there are credits in Google Cloud. 
## Step 01_ Create VM (Virtual Machine)
**Virtual Machine:** A virtual machine (VM) is a digital version of a physical computer. Virtual machine software can run programs and operating systems, store data, connect to networks, and do other computing functions, and requires maintenance such as updates and system monitoring. https://cloud.google.com/learn/what-is-a-virtual-machine  
in https://console.cloud.google.com/welcome  
  
![New VM](../a00templates/img/img1.png)  
  
It still doesn't work, first you need to "Enable" Compute Engine API
![Enable](../a00templates/img/img2.png)  
  
      
Now an image will be taken and deployed into this as a virtual machine.  

1. Create instance ![create instance](../a00templates/img/img3.png) 

2. In the Create instance windows  
   - Name:  arcgisserverdemo  
   - Region:  us-central1 (Ioma)  
   - Zone:  us-central1-a  
   - Machine:  
     - Series: E2  
     - Machine type: e2-medium (2 vCFU, 4 GB memory)  
     - Boot disk: if is linux, can be changed to windows  
     - Custom Images Tab  
       (+) Source project for images: the project which contain the image, if the image is in a different project, then click CHANGE, after select the project which contain the image, and OK.  
       (+) image: select the image  
     - Firewall: Allow HTTP and HTTPS traffic
     - Create

3. Under Related actions: Set up firewall rules
   - create a Firewall Rule
     - Name: flemingrdp444
     - Direction of traffic: Ingress
     - Action on match: Allow
     - Targets: All instances in the network
     - Source filter: iPv4 ranges
     - Source of iPv4 ranges: Enter the external ip for your computer -> restricted or 0.0.0.0/0 -> unrestricted
     - Protocols and ports:  
       (+) TCP: 444  (3389 is default for RDP, 444 will work at fleming)
     - Create
