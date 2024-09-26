FROM node:18-alpine

# Install nodemon globally
RUN npm install -g nodemon

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

# Make sure nodemon is in the path
ENV PATH="/usr/local/bin/:$PATH"

EXPOSE 4000

CMD ["npm", "run", "dev"]
