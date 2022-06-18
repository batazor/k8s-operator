FROM alpine:3.16

ADD tmp/_output/bin/k8s-operator /usr/local/bin/k8s-operator

RUN adduser -D k8s-operator
USER k8s-operator
