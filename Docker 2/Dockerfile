FROM node

WORKDIR /app

COPY . /app

RUN npm i

EXPOSE 80

CMD [ "node" ,"server.js" ]


#  0 docker build .
#  1 docker run 069b3f2acad5264f6270cc15c4bcf898fbc858298d19c5f8b20455bdf4c7d634
#  2 docker ps
#  3 docker stop amazing_snyder
#  4 docker ps
#  5 docker ps -a
#  6 docker run -p 3000:80  069b3f2acad5264f6270cc15c4bcf898fbc858298d19c5f8b20455bdf4c7d634
#  7 docker ps
#  8 docker stop competent_tharp