FROM alpine:3.10

ENV PATH "/usr/bin:/usr/sbin:/bin:/sbin:/home/developer/.gem/ruby/2.5.0/bin"

RUN apk add --no-cache git build-base shadow zip ruby ruby-etc ruby-irb ruby-json \
        ruby-rake ruby-rdoc ruby-webrick ruby-dev && \
      useradd --create-home developer && \
      echo "gem: --suggestions --user-install" > /etc/gemrc

USER developer
