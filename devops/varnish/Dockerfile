# syntax=docker/dockerfile:1
FROM varnish:7.4

LABEL maintainer="William <william.maciel@tre-ms.jus.br>" \
      org.label-schema.name="trems-varnish" \
      org.label-schema.description="Treinamento TRE-MS Varnish image." \
      org.label-schema.vendor="William"

COPY etc/varnish.vcl /etc/varnish/default.vcl
