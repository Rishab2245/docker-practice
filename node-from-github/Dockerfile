FROM node
WORKDIR /developer/nodejs/app_from_github
RUN apt-get update && apt-get install -y git 
RUN git clone https://github.com/Rishab2245/express-server-github.git .
ENV PORT=3000
RUN npm install
CMD ["npm" , "start"]