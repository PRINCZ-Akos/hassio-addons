ARG BUILD_FROM
FROM $BUILD_FROM

# Setup base
RUN apk add --no-cache openssl curl

# Copy data
COPY rootfs /

WORKDIR /