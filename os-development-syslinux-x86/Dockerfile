FROM whaledo/os-development-x86:latest

ARG SYSLINUX_VERSION=6.03
RUN apk add --no-cache wget && \
    cd /tmp && \
    wget https://www.kernel.org/pub/linux/utils/boot/syslinux/syslinux-${SYSLINUX_VERSION}.tar.gz && \
    tar xzf /tmp/syslinux-${SYSLINUX_VERSION}.tar.gz && \
    mv /tmp/syslinux-${SYSLINUX_VERSION} /tmp/syslinux
