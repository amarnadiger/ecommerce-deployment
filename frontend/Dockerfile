FROM node:14-alpine
WORKDIR /usr/src/app/frontend 
COPY package*.json ./ 
RUN npm install 
RUN npm audit fix --force
COPY . .  
CMD ["npm", "start"]

