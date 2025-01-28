# Auto Scaling Solution

![te](https://github.com/YomiDavies/AWSProjects/blob/056a731ae08ffc3ae246de43d9f2825b3b75c9e0/Auto_Scaling_solution/images/Auto%20Scaling%20Architecture.png)   

This project reflects the importance I place on concepts like auto-scaling, cost efficiency, and security. In this implementation, I developed a solution for an e-commerce website hosted on an EC2 instance. While the setup initially remains stable, the sales department’s promotional campaigns—which often go viral—cause sudden traffic spikes at unpredictable intervals. These surges overload the server, eventually causing it to fail and take the website offline, frustrating customers who can’t access the platform.

The tech team explored scaling options, first considering vertical scaling (upgrading the EC2 instance’s resources, e.g., increasing from 10 vCPUs and 20GB of RAM to 20 vCPUs and 30GB of RAM). However, after analyzing usage patterns, they realized traffic spikes occurred only once or twice a week. Maintaining a larger instance for rare events proved cost-ineffective.

Instead, the team opted for horizontal scaling, which dynamically adjusts the number of instances to match demand. Rather than relying on a single large instance, this approach uses smaller instances that automatically scale up or down based on traffic.

My task was to configure auto-scaling to ensure seamless adaptation. The goal was to create a web server infrastructure that:

1. Scales up by adding EC2 instances during high traffic (e.g., sales promotions).

2. Scales down during low traffic to minimize costs.

This solution ensures reliability during traffic spikes while optimizing resource usage and cost-efficiency.





