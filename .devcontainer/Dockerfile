FROM mcr.microsoft.com/devcontainers/rust:dev-1-bookworm

# RUN apt-get update && apt-get install --no-install-recommends -y \
#     # egui の Demo に必要なパッケージ
#     libclang-dev \
#     libgtk-3-dev \
#     libxcb-render0-dev \
#     libxcb-shape0-dev \
#     libxcb-xfixes0-dev \
#     libxkbcommon-dev \
#     libssl-dev \
#     # web frontend の gen-api で使う
#     curl \
#     # github-cli の feature で使う
#     wget \
#     && apt-get clean \
#     && rm -rf /var/lib/apt/lists/*

# WORKDIR /workspace

# ARG USERNAME=user
# ARG GROUPNAME=user
# ARG UID=1000
# ARG GID=1000
# RUN groupadd -g $GID $GROUPNAME && \
#     useradd -m -s /bin/bash -u $UID -g $GID $USERNAME
# USER $USERNAME

# RUN rustup component add clippy \
#     && rustup component add rustfmt \
#     && cargo install cargo-audit \
#     && cargo install sqlx-cli --no-default-features --features native-tls,postgres \
#     && mkdir ~/.claude
