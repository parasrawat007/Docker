From node:14

WORKDIR /app

COPY package.json .

RUN npm i

COPY . .

EXPOSE 3000

CMD [ "node","app.mjs" ]

#    0: docker run node
#    1: docker ps -a
#    2: node -v
#    3: docker run it node
#    4: docker run -it node
#    5: docker ps -a
#    6: docker kill nervous_bassi
   