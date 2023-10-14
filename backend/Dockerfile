FROM mongo:5.9.10
WORKDIR /usr/src/app/backend 
COPY package*.json ./  
RUN npm install 
COPY . .  
CMD ["npm", "start"]

