# FROM        centos:7
# RUN         yum install epel-release -y 
# RUN         yum install nginx -y
# COPY        index.html /usr/share/nginx/html/index.html
# EXPOSE      80
# ENV         environment=dev
# CMD         ["nginx", "-g", "daemon off;"]



FROM        centos:7
RUN         useradd roboshop
USER        roboshop
CMD         ["google.com"]
ENTRYPOINT  ["ping" ,"-c" , "5"]