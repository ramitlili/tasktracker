FROM node:14.18.0
WORKDIR /tasktracker
COPY . .
RUN npm i
RUN npm i -g @angular/cli@11.2.18
CMD ["ng", "serve", "--host", "0.0.0.0"]


