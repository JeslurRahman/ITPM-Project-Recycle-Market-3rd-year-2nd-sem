#Base image
FROM node:18.15.0

#working directory
WORKDIR /app

#copy package.json to /app
COPY package.json .

#npm install
RUN npm install --force

#copy all files
COPY . .

#Port expose
EXPOSE 3000

#Run the code
CMD ["npm", "start"]