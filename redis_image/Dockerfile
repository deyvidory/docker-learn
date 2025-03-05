# Use existing docker image as a base

FROM alpine

# Download and install dependencie

RUN apk add --update redis
RUN apk add --update gcc

# Tell my image what to to when it starts as a container.

CMD ["redis-server"]
