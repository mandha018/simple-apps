# PULL IMAGE
FROM node:18.16.0

# DIRECTORY UTAMA
WORKDIR /apps

# COPY FILE dari directory apps ke workdir container /apps
ADD . /apps

# build image + install module
RUN npm install

# open port
EXPOSE 3000

# run container + run apps
CMD ["npm", "start"]