# python-cli-sqlserver-ssl-to-multi-node-elk-client-without-ssl-pop

## Description
Reads a multi node cluster for data in `pop-demo` document.

Uses `pop` table in database. then covverts it to json with logstash for elasticsearch multi node cluster to use.

Sql server uses self-signed ssl.

## Tech stack
- python
- elasticsearch
- kibana
- logstash
- mssql

## Docker stack
- alpine:edge
- python
- elasticsearch
- kibana
- logstash
- mcr.microsoft.com/mssql/server:2017-CU17-ubuntu

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Docker setup](https://lynn-kwong.medium.com/all-you-need-to-know-about-using-elasticsearch-in-python-b9ed00e0fdf0)
- [Search setup](https://www.elastic.co/guide/en/elasticsearch/client/python-api/master/examples.html)