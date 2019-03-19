# base os
FROM node:carbon

# nodejs project setting from package.json file
COPY package.json /src/package.json
RUN cd /src; npm install

# copy a source code
COPY . /src

# out bound port
EXPOSE 1337

# set workspace path
WORKDIR /src

# execute command on the container
CMD node index.js 