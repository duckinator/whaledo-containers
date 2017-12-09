FROM alpine:edge

RUN apk add --no-cache qemu qemu-system-i386

ENTRYPOINT ["qemu-system-i386", "-display", "none"]
