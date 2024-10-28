FROM alpine

RUN apk add curl git && \
    curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl" && \
    cp kubectl /usr/local/bin/kubectl && \
    chmod +x /usr/local/bin/kubectl
