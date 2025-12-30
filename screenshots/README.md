Screenshots showing step-by-step execution and results.

📸 Screenshot 1 – EC2 Instance Connect (Terminal Access)

Description:
This screenshot shows successful connection to the EC2 instance using EC2 Instance Connect.
It confirms that the instance is running and accessible for server configuration.

📸 Screenshot 2 – Apache Service Installation & Status

Description:
Apache web server is installed and started on the EC2 instance using systemctl commands.
The service status shows Apache is active and running successfully.

📸 Screenshot 3 – Web Page Response from EC2 Instance 1

Description:
This output confirms that EC2 Instance 1 is serving HTTP requests correctly.
The custom message helps identify responses coming from this specific instance.

📸 Screenshot 4 – Web Page Response from EC2 Instance 2

Description:
This output verifies that EC2 Instance 2 is also serving HTTP traffic properly.
Different response text is used to distinguish traffic routing between instances.

📸 Screenshot 5 – Target Group Health Status

Description:
Both EC2 instances are registered under the target group and marked as healthy.
This confirms successful health checks and readiness for load balancing.

📸 Screenshot 6 – Application Load Balancer Creation (Basic Configuration)

Description:
This screen shows the creation of an Internet-facing Application Load Balancer.
The ALB is configured to distribute incoming HTTP traffic across multiple AZs.

📸 Screenshot 7 – Load Balancer Active State

Description:
The Application Load Balancer is successfully created and in an active state.
It confirms that the ALB is ready to accept and route client requests.

📸 Screenshot 8 – Target Group Attached to Load Balancer

Description:
This screenshot shows the target group linked to the Application Load Balancer.
Traffic received by the ALB will now be forwarded to healthy EC2 instances.
