ARG DENO_VERSION=1.39.0

FROM denoland/deno:bin-$DENO_VERSION AS deno
FROM mcr.microsoft.com/devcontainers/base:jammy AS ubuntu

COPY --from=deno /deno /usr/local/bin/deno