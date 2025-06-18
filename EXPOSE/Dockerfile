FROM almalinux:9
RUN dnf install nginx -y
# There is no functionality for EXPOSE, it is just for information
EXPOSE 8080
CMD ["nginx", "-g", "daemon off;"]