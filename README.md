NGINX-SERVER
This repository provides a basic setup for an NGINX server configured to serve static HTML content.

About
This project sets up a simple NGINX server to serve static HTML pages. It includes sample index.html and about.html files as examples.

Getting Started
Pre-requisites
Ensure you have the following installed:

NGINX
Installation
Clone the repository:
git clone https://github.com/pushparajwastaken/NGINX-SERVER.git

Navigate to the project directory:
cd NGINX-SERVER

Copy the HTML files to the NGINX web root directory:
sudo cp *.html /usr/share/nginx/html/

Start the NGINX server:
sudo systemctl start nginx

Verify the server is running by visiting:
http://localhost/index.html
http://localhost/about.html

Usage
This setup serves the index.html and about.html pages via NGINX. You can modify these files or add new HTML files to the /usr/share/nginx/html/ directory to serve additional content.

Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your changes.
