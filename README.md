<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/open-feature/community/0e23508c163a6a1ac8c0ced3e4bd78faafe627c7/assets/logo/horizontal/white/openfeature-horizontal-white.svg">
    <img align="center" alt="OpenFeature Logo" src="https://raw.githubusercontent.com/open-feature/community/0e23508c163a6a1ac8c0ced3e4bd78faafe627c7/assets/logo/horizontal/black/openfeature-horizontal-black.svg" />
  </picture>
</p>

# Contribfest-EU-24
## Open issues by language

- [Go](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+state%3Aopen+language%3AGo+&type=issues&state=open)
- [Java](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+state%3Aopen+language%3Ajava+&type=issues&state=open)
- [TS/JS](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+state%3Aopen+language%3ATypescript+&type=issues&state=open)
- [C#](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+language%3AC%23+++&type=issues&state=open)
- [Python](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+state%3Aopen+language%3Apython+&type=issues&state=open)
- [Ruby](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+state%3Aopen+language%3Aruby+&type=issues&state=open)

## Providers

Providers are the abstractions that bridge the gap between the SDK and the vendors or tools that store, manage and server feature flags.
See the [provider spec](https://openfeature.dev/specification/sections/providers), and [FAQ](https://openfeature.dev/docs/reference/concepts/provider#faq).

- Check out [existing providers](https://openfeature.dev/ecosystem)
  - Consider implementing an "env_var" provider if none exists for the language in question
  - Consider implementing a provider for a vendor or tool you are familiar with
- find in contrib repos
 
## Hooks

Hooks add arbitrary functionality to a flag evaluation.
See the [hook spec](https://openfeature.dev/specification/sections/hooks) and [concept section](https://openfeature.dev/docs/reference/concepts/hooks).
 - Consider implementing a validation hook (see [Go example](https://github.com/open-feature/go-sdk-contrib/tree/main/hooks/validator))

## Related tools

### flagd

A "cloud native" backend for feature flags, with providers in multiple languages.

- [flagd repo](https://github.com/open-feature/flagd)
- [docs](https://flagd.dev/)
- flagd providers can be found in [contrib repos](https://github.com/orgs/open-feature/repositories?q=sdk-contrib)
### OpenFeature Operator

Manage feature flags as Kubernetes resources (CRs) and automatically inject and configure flagd.

[Repo](https://github.com/open-feature/open-feature-operator)

### Go Feature Flag

An OpenFeature-compatible, open-source backend

[Repo](https://github.com/thomaspoignant/go-feature-flag)


