# Aurora-Database-with-EC2
In this project, we're creating an Amazon Aurora database to store and display data for our very own web application!. 

I had read about Aurora before, but using it was different. Aurora is relational like RDS, but faster and better optimized for large-scale applications. I wanted to see what made it so special, so I paired it with an EC2 instance to simulate a web server.

The first step was setting up the Aurora database. I chose the MySQL flavor since I was already familiar with it. Aurora’s default features — like automated backups and replication — made it feel like a more advanced version of RDS.

Next, I created an EC2 instance. This would act as the “front end” of the project, hosting a basic web server. Configuring the EC2 instance to connect to Aurora involved setting up endpoints and adjusting security group rules. When the connection worked, it felt satisfying. I could see how Aurora could handle the demands of a real application.

![architecture-diagram5](https://github.com/user-attachments/assets/bd4832fe-e1c2-46fc-8282-15640ce70a75)
