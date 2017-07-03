# quick-rancher

Quickly spawn a Rancher instance.
These images used Route53 AWS to generate the Let's Encrypt certificate.

## Usage

Edit the docker-compose.yml file and add your :
- AWS keys
- Your DNS domain

then simply run :

```bash
$> docker-compose.yml -d
```


