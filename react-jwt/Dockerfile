# pull official base image
FROM node:10

# set working directory
WORKDIR /

# install app dependencies
COPY package.json /


RUN npm install



# add app
COPY . /

# start app
CMD ["npm", "start"] 


