FROM node:0.10.36-slim
ADD bundle /
WORKDIR /bundle
RUN cd programs/server && npm install
CMD ["node", "main.js"]
