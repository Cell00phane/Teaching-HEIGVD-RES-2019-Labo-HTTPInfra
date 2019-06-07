# Report

## Static php apache
Html template taken from bootstrap, run from docker image using docker run -d -p 9090:80 res/apache.

## Dynamic content
Using express.js framework to create a http server that listens on port 3000 and that sends out a list of wanna be author animals who give out inspirational quotes. (Credits to inspirational-quotes and chance npm modules). 
Using a dockerfile to copy the content of src, which itself contains the index.js that we're using to generate the dynamic content, into a docker container. Then we can start that docker container built from that image.
