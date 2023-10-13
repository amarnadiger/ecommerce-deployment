FROM node:14 #base image 
WORKDIR /usr/src/app/frontend #setting the directory 
COPY package*.json ./ #copying dependency files
RUN npm install # Installing dependencies
COPY . .  #copying source code related to frontend
CMD ["npm", "start"]

