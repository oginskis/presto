# Presto Dockerfile

Dockerfile for PrestoDB with Apache Pulsar connector image

Set desired `PRESTO_VERSION` and `PULSAR_VERSION` arguments and run `docker build . -t <tag>`

For example, the image can be used to deploy Presto cluster using <https://github.com/oginskis/charts/tree/master/stable/presto> Helm chart

Some image versions are pushed to <https://hub.docker.com/r/oginskis/prestodb>
