FROM rust:1.43

WORKDIR /app

COPY bin .

RUN cargo install --path .

CMD ["main"]
