FROM mhart/alpine-node
RUN mkdir /app
WORKDIR /app/
ADD package.json /app/
RUN npm install --production
ADD . /app/
EXPOSE 3000
CMD ["npm", "start"]
