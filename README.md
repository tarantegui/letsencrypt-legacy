# Letsencrypt

https://letsencrypt.org/

Letsencrypt is a service that allows to create and manage authorized certificates for free.

The usage of this service is very simple, run the `docker-compose` and select the service that you need.

```
docker-compose -f letsencrypt.yml run SERVICE
```

The services are:

**help** - Shows letsencrypt help, pretty simple.

**auth** - Starts the assistant for create a new certificate.

**renew** - Starts the assistant for renewing a certificate.

**revoke** - Starts the assistant for revoking a certificate.
