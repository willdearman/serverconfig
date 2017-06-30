# We'll inherit from the official NGINX image
# Note: I'm using the 'alpine' version which is a very light weight image
FROM nginx:alpine

# Let's copy over all our configs into the image
ADD sites/* /etc/nginx/conf.d/

# And expose port 80 for redundency
EXPOSE 80