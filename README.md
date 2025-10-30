#  Cloud Auto Scaling and Load Balancer Setup

##  Overview
This project demonstrates how to build a **highly available and scalable web application** on AWS using **EC2 instances**, an **Auto Scaling Group (ASG)**, and an **Application Load Balancer (ALB)**.

---

##  Steps Performed

1. **Created EC2 Instances**
   - Launched two EC2 instances and hosted a simple `index.html` webpage on each.

2. **Created a Launch Template**
   - Defined instance configuration including AMI, instance type, and security groups.

3. **Added User Data**
   - Added startup script to automatically install Apache and deploy the HTML file.

4. **Configured an Auto Scaling Group (ASG)**
   - Used the Launch Template to automatically manage EC2 capacity.

5. **Selected Multiple Subnets**
   - Distributed instances across different Availability Zones for high availability.

6. **Created a Target Group**
   - Target type set to **Instance** with HTTP protocol (port 80).

7. **Set Up an Application Load Balancer (ALB)**
   - Connected the ALB to the Target Group to distribute incoming traffic.

8. **Tested the Application**
   - Accessed the **Load Balancer DNS name** in a browser and confirmed the webpage loaded successfully.

9. **Verified Auto Scaling**
   - Terminated one EC2 instance → Auto Scaling automatically launched a new one as a replacement.

---

##  Deliverables (Screenshots)

- ✅ **Load Balancer Dashboard** showing connected backend instances.  
- ✅ **Target Group** health check status (Healthy).  
- ✅ **Auto Scaling Group** configuration and scaling activity log.  
- ✅ **EC2 Instances** view displaying scaling event.  
- ✅ **Browser Output** showing webpage loaded through Load Balancer DNS.

---

##  Outcome

- Successfully implemented **Auto Scaling** and **Load Balancing** for a simple web application.  
- Demonstrated **fault tolerance** and **automatic recovery** in AWS.  
- Learned the fundamentals of **high availability** and **scalable infrastructure**.
