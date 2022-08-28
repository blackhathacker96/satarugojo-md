FROM quay.io/souravkl11/raganork:multidevice

RUN git https://github.com/blackhathacker96/satarugojo-md /skl/Raganork
WORKDIR /skl/Raganork
ENV TZ=Asia/Kolkata
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
