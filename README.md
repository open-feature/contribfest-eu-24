# Contribfest-EU-24

## Open issues by language

- [Go](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+state%3Aopen+language%3AGo+&type=issues&state=open)
- [Java](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+state%3Aopen+language%3Ajava+&type=issues&state=open)
- [TS/JS](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+state%3Aopen+language%3ATypescript+&type=issues&state=open)
- [C#](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+language%3AC%23+++&type=issues&state=open)
- [Python](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+state%3Aopen+language%3Apython+&type=issues&state=open)
- [Ruby](https://github.com/search?q=org%3Aopen-feature+type%3Aissue+label%3Acontribfest+state%3Aopen+language%3Aruby+&type=issues&state=open)

## Providers

Providers are the abstractions that brige the gap between the SDK and the vendors or tools that store, manage and server feature flags.
See the [provider spec](https://openfeature.dev/specification/sections/providers)https://openfeature.dev/specification/sections/providers, and [FAQ (https://openfeature.dev/docs/reference/concepts/provider#faq)https://openfeature.dev/docs/reference/concepts/provider#faq

- Check out [existing providers](https://openfeature.dev/ecosystem)https://openfeature.dev/ecosystem
  - Consider implementing an "env_var" provider if none exist for the language in question
  - Consider implementing a provider for a vendor or tool you are familiar with
- find in contrib repos
 
## Hooks

Hooks add arbitrary functionality to a flag evaluation.
See the [hook spec](https://openfeature.dev/specification/sections/hooks) and [concept section](https://openfeature.dev/docs/reference/concepts/hooks)https://openfeature.dev/docs/reference/concepts/hooks.

## Related tools

### flagd

A "cloud native" backend for feature flags, with providers in multiple langauges.

- [flagd repo](https://github.com/open-feature/flagd)
- [docs](https://flagd.dev/)
- flagd providers can be found in [contrib repos](https://github.com/orgs/open-feature/repositories?q=sdk-contrib)https://github.com/orgs/open-feature/repositories?q=sdk-contrib

### OpenFeature Operator

Manage feature flags as Kubernetes resources (CRs) and automatically inject and configure flagd.

[Repo](https://github.com/open-feature/open-feature-operator)

### Go Feature Flag

An OpenFeature-compatible, open-source backend

https://github.com/thomaspoignant/go-feature-flag


