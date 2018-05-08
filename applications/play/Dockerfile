FROM node:8@sha256:89171382ea2e08a7ca84f653cd37e30e47b9c305baaee272899e25c912172f26
ADD . /playground
WORKDIR /playground
RUN npm install && npm run build

EXPOSE 3000

CMD ["/playground/node_modules/.bin/next", "start", "--host", "0.0.0.0"]
