# terraform-provider-ipso

[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/ipsofacto-io/terraform-provider-ipso/badge)](https://scorecard.dev/viewer/?uri=github.com/ipsofacto-io/terraform-provider-ipso)

Terraform and OpenTofu provider for managing [ipso](https://github.com/ipsofacto-io/ipso) decisions, scopes, and waivers as code.

> Status: skeleton. Provider resources and data sources will land in an upcoming release.

## Scope

Once implemented, this provider will manage decisions, scopes, and waivers declaratively through the [ipso-server](https://github.com/ipsofacto-io/ipso-server) control-plane API.

It lives in its own repository to satisfy Terraform Registry naming conventions and uses the MPL-2.0 license standard across the Terraform provider ecosystem.

## License

Mozilla Public License, Version 2.0. See [LICENSE](LICENSE).

Copyright 2026 Luca Bertelli.

## Contributing

Follow the contributor guidelines in [ipsofacto-io/.github](https://github.com/ipsofacto-io/.github/blob/main/CONTRIBUTING.md). All commits require a `Signed-off-by` trailer (`git commit -s`).
