FROM php
COPY ./ /usr/src/myapp
WORKDIR /usr/src/myapp
RUN pwd
RUN ls -la 
EXPOSE 80
CMD [ "php","-S","0.0.0.0:80" ]

