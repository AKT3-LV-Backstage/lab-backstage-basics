# This Dockerfile uses a distroless Node.js 24 image based on Debian 12 as the base image.
# For the Backstage Lab, you should not need to modify this file.

FROM gcr.io/distroless/nodejs24-debian12

WORKDIR /app
COPY src/main.js ./

EXPOSE 8000

CMD ["main.js"]