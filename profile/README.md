# WAFio

WAFio is a self-hosted web application firewall with a host firewall and runtime security for Linux servers. You
run a control plane, and agents on the servers you protect report to it.

**Start at [Wafio/wafio](https://github.com/Wafio/wafio)**: what WAFio is, how to install it, the releases, and where
to report a problem.

```sh
curl -fsSL https://wafio.cloud/install.sh | sudo bash
```

Documentation: <https://wafio.cloud/docs>

## Repositories

| Repository | What it is |
|---|---|
| [wafio](https://github.com/Wafio/wafio) | Front page of the project: install, releases, issues about the whole product, security and support |
| [wafio-cp-backend](https://github.com/Wafio/wafio-cp-backend) | Control plane: HTTP API, agent server, database migrations |
| [wafio-cp-frontend](https://github.com/Wafio/wafio-cp-frontend) | Dashboard |
| [wafio-agent-waf](https://github.com/Wafio/wafio-agent-waf) | WAF agent: the reverse proxy in front of your application |
| [wafio-agent-host](https://github.com/Wafio/wafio-agent-host) | Host agent: eBPF firewall and runtime security |
| [uddin-lang-rs](https://github.com/Wafio/uddin-lang-rs) | Interpreter of the uddin script language used by script rules |

The semantic detection engine and the installers are not published. The README of
[Wafio/wafio](https://github.com/Wafio/wafio) says what each repository holds, its licence and how they fit together.

## Sponsors

<a href="https://zetguard.com"><img src="https://raw.githubusercontent.com/Wafio/wafio/main/docs/sponsors/zetguard.png" alt="ZetGuard" height="36"></a>

[ZetGuard](https://zetguard.com) funds the development of WAFio. ZetGuard's server and application protection is
built on the WAFio code.

To sponsor WAFio, write to <hello@wafio.cloud>.

## Security

A security problem never goes into a public issue. Report it privately:
<https://github.com/Wafio/wafio/security/advisories/new>.
