![image alt] (https://github.com/YomiDavies/AWSProjects/blob/main/Auto_Scaling_solution/images/Auto%20Scaling%20Architecture.png?raw=true)   



                         
        
               




     This project idea is that of Fikayomi Fashanu of Cloud Career mentor. The sole purpose is to solve the challenge of an E-commerce website. This project will also reflect my appreciation of the importance of concepts such as auto scaling, cost saving and Security.
    In this project i will implement a solution for an E-commerce website that has an ec2 instance hosting a web server, everything is stable until the sales department starts a sales promotion that instantly becomes popular, as a result of this, the website receives a spike in traffic at different times. Every time there is a spike in traffic the server gets overloaded until it fails, which causes the website to go down, this then leads to customers being disgruntled because they can't access the site. The tech team then brainstorm and considers some scaling alternatives like vertical scaling,which simply means increasing the resources of the ec2 instance for example if the intance was originally 10vcpu and 20 gig of RAM, scaling this inscrance vertically could mean increasing the reources to 20 vcpu and 30 gig of RAM, but after devoting enough time to the data the came to the realization the the spike only occurs once or twice a week, and it was not cost effective to deploy an ec2 instance waith a larger resource.
    The tech team then decides to opt for the horizontal scaling option, which is increasing the number of instances to meet the demand, so in essence rather than having one big instance you can have two or smaller instances that will automatically scale up or down to meet the traffic demand. The task for me is to setup auto-scaling, so this happens automatically, the goal is to create a webserver that can scale up or down to meet up wit the demands of the traffic, for example if the e-commerce website is receiving alot of traffic then it adds more ec2 instances to deal with the increase in workload and when the traffic to the site is reduced, the number of ec2 instances is reduced to save on cost.

