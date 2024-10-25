FROM alpine:latest
RUN apk add --no-cache python3
COPY ./app /app
WORKDIR /app
CMD ["python3", "-m", "http.server", "8080"]
