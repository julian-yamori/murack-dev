FROM mcr.microsoft.com/devcontainers/rust:dev-1-bookworm

RUN apt-get update && apt-get install --no-install-recommends -y \
    # egui の Demo に必要なパッケージ
    libclang-dev \
    libgtk-3-dev \
    libxcb-render0-dev \
    libxcb-shape0-dev \
    libxcb-xfixes0-dev \
    libxkbcommon-dev \
    libssl-dev \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

USER vscode
RUN cargo install cargo-audit \
    && cargo install sqlx-cli --no-default-features --features native-tls,postgres
