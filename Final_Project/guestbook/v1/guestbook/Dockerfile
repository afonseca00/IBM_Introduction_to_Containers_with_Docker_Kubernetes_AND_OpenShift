# Please choose from the below set of Docker commands to complete your Dockerfile:

# COPY
# RUN
# ADD
# EXPOSE
# FROM
# CMD
# PUSH
# PULL
# WORKDIR


# Stage 1: Build the application
FROM golang:1.18 as builder

WORKDIR /app

COPY main.go .

RUN go mod init guestbook
RUN go mod tidy

RUN go build -o main main.go

# Stage 2: Create the final image
FROM ubuntu:18.04

# Copy the built application from the builder stage
COPY --from=builder /app/main /app/guestbook

# Copy the static files
COPY public/index.html /app/public/index.html
COPY public/script.js /app/public/script.js
COPY public/style.css /app/public/style.css
COPY public/jquery.min.js /app/public/jquery.min.js

WORKDIR /app

# Command to run the application
CMD ["./guestbook"]

# Expose port 3000
EXPOSE 3000
