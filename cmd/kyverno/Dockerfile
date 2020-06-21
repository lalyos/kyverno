FROM alpine
ADD https://github.com/lalyos/kyverno/releases/download/v1.1.6.hack/kyverno-linux /kyverno
RUN chmod +x /kyverno
ENTRYPOINT ["/kyverno"]