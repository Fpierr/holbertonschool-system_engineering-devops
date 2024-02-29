# Web Infrastructure Design

This project was desainged in 4 stages. It's to understand what is a web infractructure. So, in this project, a web infrastructure for www.foobar.com was initially designed with one server, including an Nginx web server, an application server, a MySQL database, application files, and a domain name foobar.com configured to point to the server's IP address 8.8.8.8. To enhance reliability and scalability, two additional servers were added, along with an HAproxy load balancer for balanced traffic distribution. Subsequently, three firewalls were included to reinforce security, an SSL certificate was installed to enable secure connections via HTTPS, and three monitoring clients were integrated to collect data. Additionally, one more server and an HAproxy load balancer configured as a cluster with the other one were introduced, and components such as web server, application server, and database were split, each residing on its dedicated server.

## Author

[Fanuel Pierre](https://www.github.com/Fpierr)
