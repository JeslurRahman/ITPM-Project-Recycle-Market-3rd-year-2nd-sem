#Base image
FROM node

#working directory
WORKDIR /server

#copy package.json to /app
COPY package.json .

#npm install
RUN npm install

#copy all files
COPY . .

#Port expose
EXPOSE 5000

#Run the code
CMD ["npm", "start"]

