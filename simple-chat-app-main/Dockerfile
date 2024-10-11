FROM denoland/deno:latest

EXPOSE 7777 

WORKDIR /

COPY . .

CMD [ "run", "--unstable", "--allow-net", "--allow-read", "--allow-write", "--allow-env", "--no-check", "app.js" ]  
