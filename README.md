Docker Hub-
Backend- https://hub.docker.com/r/joueur7/s3iam
Frontend- https://hub.docker.com/r/joueur7/s3iamfe

To use this image sharing app on your systems:
1. git clone https://github.com/Joueur7/s3iam.git

2. open Backend, run the following commands:
   i)npm install 
   ii)sudo npm install -g --force nodemon
   iii)nodemon server.js
   Your Backend will be up and running on 8080 port, do config the .env file for your S3 bucket
   
3. open frontend, run npm install and then npm start, React will launch itself on 3000 port


Now simply add a file that you want to share and click 'Submit' your nodemon will you you the shareable link for the image file.

The project is also live on AWS-EC2 instance
