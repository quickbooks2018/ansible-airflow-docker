# Apache Airflow in docker

- cloudgeeks.ca

- checking host memory

```mem
docker run --rm "debian:bullseye-slim" bash -c 'numfmt --to iec $(echo $(($(getconf _PHYS_PAGES) * $(getconf PAGE_SIZE))))'
```