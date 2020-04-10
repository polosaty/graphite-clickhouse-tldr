FROM openmetric/carbonapi:0.11.0

COPY ./root/etc/carbonapi.yaml /etc/carbonapi.yaml

# ENTRYPOINT ["sh" "-c" "'carbonapi -config /etc/carbonapi.yaml'"]
ENTRYPOINT ["carbonapi" "-config" "/etc/carbonapi.yaml"]
