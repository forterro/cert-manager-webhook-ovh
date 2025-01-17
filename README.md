# OVH Webhook for Cert Manager

![OVH Webhook for Cert Manager](assets/images/cert-manager-webhook-ovh.svg "OVH Webhook for Cert Manager")

This is a webhook solver for [OVH](http://www.ovh.com) DNS. In short, if your domain has its DNS servers hosted with OVH, you can solve DNS challenges using Cert Manager and OVH Webhook for Cert Manager.

Please star this repository to help others find it.

## Features

- Solve DNS01 challenges using OVH DNS servers
- Supports Cert Manager `ClusterIssuer` and `Issuer`
- Helm chart repository for ease and simplicity
- Store OVH credentials in a secret per issuer, or use secret references
- Role based access control, across namespace

## Documentation

The documentation is available at [https://aureq.github.io/cert-manager-webhook-ovh/](https://aureq.github.io/cert-manager-webhook-ovh/)

## Artifact details

See [artifacthub.io](https://artifacthub.io/packages/helm/cert-manager-webhook-ovh/cert-manager-webhook-ovh)

## Support

We would like to inform our users that this repository is maintained by a volunteer, and as such, it is a best effort support, and not a commercial service.
While we strive to provide the best possible support to our users, we cannot guarantee immediate or comprehensive responses to all queries.
Therefore, we advise that users seeking professional support should contact the author directly.

We also want to emphasize that any form of abuse or entitlement towards our volunteer maintainers will not be tolerated.
Our volunteers work hard to provide support to the community, and we expect all users to treat them with respect and appreciation.
We appreciate your understanding and cooperation in maintaining a positive and productive environment for everyone involved in this community-driven project.

## Release workflow

- Prepare `CHANGELOG.md` for `vx.y.z`
- Commit all changes
- Push all commits
- run `bash .github/scripts/changelog.sh vx.y.z`

## Maintainers

- [@aureq](https://github.com/aureq)

## Contributors

- [@munnerz](https://github.com/munnerz)
- [@Diaphteiros](https://github.com/Diaphteiros)
- [@baarde](https://github.com/baarde)
- Xaver Baun
- lcavajani
- Ricardo Pchevuzinske Katz
- [@MattiasGees](https://github.com/MattiasGees)
- Jean-Marc Andre
- [@IDerr](https://github.com/IDerr)
- Robin KERDILES
- Julian Stiller
- [@julienkosinski](https://github.com/julienkosinski)
- [@aegaeonit](https://github.com/aegaeonit)
- [@TartanLeGrand](https://github.com/TartanLeGrand)
- [@Zcool85](https://github.com/Zcool85)
- [@Yethal](https://github.com/Yethal)
