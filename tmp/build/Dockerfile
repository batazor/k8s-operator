FROM alpine:3.13

ADD tmp/_output/bin/k8s-operator /usr/local/bin/k8s-operator

RUN adduser -D k8s-operator
USER k8s-operator
