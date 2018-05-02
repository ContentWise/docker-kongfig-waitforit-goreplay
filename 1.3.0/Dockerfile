FROM contentwisetv/node-waitforit-goreplay:9

ARG KONGFIG_VERSION=1.3.0

USER root
RUN npm install -g kongfig@${KONGFIG_VERSION}
USER node
WORKDIR /home/node

CMD ["sh"]