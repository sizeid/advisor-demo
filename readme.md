# SizeID Advisor Demo
Demo of [SizeID Advisor](http://demo.sizeid.com/advisor.products/).

## Installation

1. Download via composer

```
composer create-project sizeid/advisor-demo
```

### Preconfigured

1. Run `index.html` with webserver.

### Custom credentials

1. Register at [SizeID for Business](https://business.sizeid.com/public/sign-up/). Free tariff available.

2. Get your `Identity Key` at [SizeID for Business](https://business.sizeid.com/integration.settings/#credentials) and paste it into `[data-sizeid-identity-key]` attribute.

2. Whitelist your domain at [SizeID for Business](https://business.sizeid.com/integration.settings/#credentials) - for localhost just add localhost

3. Add at least one active size chart at [SizeID for Business](https://business.sizeid.com/size-charts.database/) and paste it\`s id into `[data-sizeid-size-chart]` attribute.

4. Run `index.html` with webserver.

See console for errors.
