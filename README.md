Cloud Auto Scaling and Load Balancer Setup
# created 2 EC2 instances and run a simple index HTML in that 
# Created a Launch Template .
# Added user data to install Apache and deploy the HTML file.
# Created an Auto Scaling Group  using the  Launch Template.
# Selected subnets across multiple Availability Zones for high availability.
# Created a Target Group  using target type = Instance.
# Created an Auto Load bancer 
# Accessed the Load Balancer DNS name in a browser.
# Page displayed successfully, proving load balancing works.
# Terminated one instance → Auto Scaling automatically replaced it.
