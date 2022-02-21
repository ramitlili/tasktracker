FROM node:14.18.0
WORKDIR /tasktracker
COPY . .
RUN npm install -g json-server 
CMD ["json-server"  , "--watch" , "/tasktracker/db.json"  , "--port" , "5000" , "--host" , "0.0.0.0"]