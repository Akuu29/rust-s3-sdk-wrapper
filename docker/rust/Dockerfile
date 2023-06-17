FROM rust:1.67
RUN apt-get update && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* && \
    rustup component add rustfmt rust-analysis clippy && \
    cargo install cargo-watch cargo-make
