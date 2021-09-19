FROM node

WORKDIR /workspace

ADD . /workspace

RUN cd apps/hello && npm i

CMD node apps/hello/index.mjs
