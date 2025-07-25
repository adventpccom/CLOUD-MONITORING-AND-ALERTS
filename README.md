# CLOUD-MONITORING-AND-ALERTS

*COMPANY* : CODTECH IT SOULTIONS

*NAME* : AKASH RAJ

*INTERNID* : CT04DH590

*DOMAIN* : CLOUD COMPUTING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

##DESCRIPTION OF TASK 2 :
In Task 2 of the CodTech internship, I worked on setting up cloud monitoring and alerts using AWS. The main goal of this task was to track system performance and get notified when something unusual happens — like high CPU usage or low disk space — so that action can be taken before the system crashes or slows down. I started by creating an EC2 instance, which is basically a virtual server running on the cloud. I chose Ubuntu as the OS and enabled monitoring through AWS CloudWatch. CloudWatch is a service that collects real-time metrics from AWS resources and lets you visualize them on a dashboard. After setting up the instance, I explored how to monitor key system-level metrics like CPU utilization, network traffic, and disk I/O. I created a custom CloudWatch dashboard and added these metrics to it, so I could easily track them in one place.

The next step was to create alarms. I set up a CPU utilization alarm that would trigger if the usage went above a certain percentage. I also created another alarm related to disk space, which I monitored using a custom metric since disk space isn’t tracked by default. Once the alarms were in place, I connected them to Amazon SNS (Simple Notification Service) to send out notifications. I created an SNS topic, subscribed my email address to it, and tested it by stressing the CPU on the instance. As expected, once the usage crossed the threshold, the alarm triggered and I got an email alert from AWS SNS. It was a clear example of how monitoring and alerts work together in real-world cloud setups.

Throughout this task, I got hands-on experience with CloudWatch, EC2, and SNS — all major parts of the AWS ecosystem. I understood how these services are interconnected and how monitoring isn't just about watching metrics but actually about creating meaningful alerts that can help take quick action. I also realized how important it is to set proper thresholds for alarms — not too strict, not too lenient — otherwise, you either get too many alerts or miss real issues. I documented the entire process and took screenshots of the EC2 instance, dashboard, alarms, and the alert email. All these files are uploaded in the Task-2 folder in the repo. I kept everything structured so that anyone can go through it and understand what was done.

This task made me more confident in working with AWS and cloud monitoring in general. It gave me a small but solid idea of how DevOps teams ensure server reliability and performance in production. Overall, Task 2 was not only about completing a checklist but also about understanding the role of observability in cloud infrastructure. I also faced and solved minor issues like IAM permissions and blocked alerts during setup, which gave me more practical exposure. I feel that this task pushed me to explore deeper and made me more comfortable with real-world cloud tools and workflows.


<img width="1899" height="966" alt="Image" src="https://github.com/user-attachments/assets/6c9a6462-1773-490c-9d1c-f3235165e083" />

<img width="1909" height="960" alt="Image" src="https://github.com/user-attachments/assets/1580f84c-44e4-4183-8883-02da0b2d93c5" />
<img width="1906" height="973" alt="Image" src="https://github.com/user-attachments/assets/c8e031be-c049-461f-9b1b-050854cd8970" />
<img width="1909" height="960" alt="Image" src="https://github.com/user-attachments/assets/90e8ba25-aad4-4b18-90ce-b926bfb8dfca" />
<img width="1919" height="909" alt="Image" src="https://github.com/user-attachments/assets/282f0c2f-52df-49ad-a45f-a487b31ca664" />
<img width="1913" height="957" alt="Image" src="https://github.com/user-attachments/assets/d6ea057d-ca0b-49ce-90e0-8bb6794a9a51" />
<img width="1907" height="958" alt="Image" src="https://github.com/user-attachments/assets/a4ec867b-9d8c-4188-9d97-1f277f38a6b5" />
<img width="1915" height="911" alt="Image" src="https://github.com/user-attachments/assets/aafbc039-d490-4d95-a341-36f2fe1c4ba4" />
<img width="1486" height="651" alt="Image" src="https://github.com/user-attachments/assets/c684ffdb-d66c-4e98-95b5-a4c8a682882f" />

