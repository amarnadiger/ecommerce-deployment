FROM node:14
WORKDIR /usr/src/app/backend #Setting directories
COPY package*.json ./ #copying json files which contains dependencies 
RUN npm install #installing the dependencies
COPY . .  #cpoying the entire source code which is related to backend
CMD ["npm", "start"]

