FROM node:18-alpine

WORKDIR /app

COPY package.json package-lock.json* ./
RUN npm install

COPY . .

EXPOSE 8505
ENV PORT=8505

CMD ["npm", "start"] 