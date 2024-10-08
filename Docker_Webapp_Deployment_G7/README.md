# Deploying-a-Web-Application-on-AWS-EC2-with-Docker

## Project Overview

This project showcases the development and deployment of a web application utilizing HTML, CSS, and JavaScript, packaged in a Docker container and hosted on an AWS EC2 instance running on Ubuntu. This approach ensures scalability, reliability, and ease of management.

## Features

- **Responsive Design:** Built with HTML, CSS, and JavaScript for a dynamic user experience.
- **Containerization:** Dockerfile included for packaging the application, ensuring consistency across environments.
- **Cloud Hosting:** Deployed on AWS EC2, allowing for robust hosting and resource management.

## Objectives
- Launch an EC2 instance on AWS with a suitable OS (e.g., Amazon Linux or Ubuntu).
- Install and configure Docker on the EC2 instance.
- Create a Dockerfile and build a Docker image for the web application.
- Upload the necessary project files (HTML, CSS, JavaScript, Dockerfile) to the EC2 instance.
- Run the Docker container to host the web application.
- Configure security group settings to allow HTTP traffic on port 80.
- Access the web application through the EC2 instance's public IP or DNS. 

## Technologies Used
- **HTML**
- **CSS**
- **JavaScript**
- **Docker**
- **AWS EC2**

## Project Setup

  ### Prerequisites
  
  - **AWS account with EC2 access.**
  - **SSH key pair for accessing the EC2 instance.**
  - **Basic understanding of HTML, CSS, JavaScript, and cloud deployment**

  ### Steps
   1. **Create EC2 Instance:** Launch an EC2 instance on AWS with Ubuntu OS.
   2. **Connect to EC2 Instance:** Access the EC2 instance via SSH.
   3. **Install Docker:** Run the provided installation script to set up Docker and update it.
   4. **Start Docker:** Start and run Docker using the appropriate command.
   5. **Upload Files:** Copy the necessary files (index.html,style.css,script.js,dockerfile) to the docker directory on the EC2 instance.
   7. **Build and Run the Docker Container on EC2:** navigate to the project directory, build the docker image and run it with the help of Dockerfile.
   8. **Access the Application:** go to your instance and navigate to <public-ipv4> to see your web application running on the web.
 
 
## Future Enhancements
  1. **Responsive Design Improvements:** Implement advanced responsive design using CSS frameworks like Bootstrap or Tailwind CSS for better aesthetics and 
 usability across devices.
  2. **User Authentication**: Implement user authentication with  OAuth for account creation and login.

## Contributing
   Contributions are welcome! If you have suggestions or improvements, please open a pull request or raise an issue.

## Contact Information
- **Gaurav Kumar**
- [LinkedIn](https://www.linkedin.com/in/gaurav-kumar-4724602a9/)
