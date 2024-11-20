# My E-Commerce Website

This is a simple e-commerce website built using HTML, CSS, and hosted on AWS. It demonstrates how to list products and deploy a static website on AWS EC2 using Nginx.

## Features

- Product listing with images, descriptions, and prices.
- Simple UI with a responsive design.
- Deployed on AWS EC2 using Nginx web server.

## Technologies Used

- **Frontend**: HTML, CSS
- **Hosting**: AWS EC2, Nginx

## Installation

To run this project locally, follow these steps:

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/my-ecommerce-site.git
cd my-ecommerce-site

2. Serve using a local web server:
You can open the index.html in a browser, or use a simple web server like http-server (Node.js required):

bash
Copy code
npm install -g http-server
http-server

3. Access the site at http://localhost:8080.


Deployment
The website is deployed on an AWS EC2 instance with Nginx. Follow the steps below to set up the environment.

1. Launch an EC2 instance on AWS (Ubuntu/Amazon Linux).
2. Install Nginx:
bash
Copy code
sudo apt install nginx  # On Ubuntu
sudo yum install nginx  # On Amazon Linux 2
3. Clone the repository to the EC2 instance:
bash
Copy code
git clone https://github.com/yourusername/my-ecommerce-site.git
cd my-ecommerce-site
4. Copy the files to the Nginx web server directory:
bash
Copy code
sudo cp -r * /usr/share/nginx/html/
5. Access the website:
Open the public IP address of your EC2 instance in a browser:

vbnet
Copy code
http://<your-ec2-public-ip>








