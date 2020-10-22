# pay-egress

Alpine image that has squid installed.

Squid config is done via the `SQUID_CONFIG` environment variable.

## Usage

```
docker run -e "SQUID_CONFIG=$(cat /path/to/squid/config)" govukpay/egress
```

## Licence
[MIT License](LICENCE)

## Responsible Disclosure
GOV.UK Pay aims to stay secure for everyone. If you are a security researcher and have discovered a security vulnerability in this code, we appreciate your help in disclosing it to us in a responsible manner. We will give appropriate credit to those reporting confirmed issues. Please e-mail gds-team-pay-security@digital.cabinet-office.gov.uk with details of any issue you find, we aim to reply quickly.
