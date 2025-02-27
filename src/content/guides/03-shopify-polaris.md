---
title: "Astro template for Shopify's Polaris Admin System"
description: ""
tags: ["astro"]
---

Here is a quick theme template [https://github.com/getmarkus/astro-shopify-polaris](https://github.com/getmarkus/astro-shopify-polaris) to experiment with Shopify's design system for Admin Apps called [Polaris](https://polaris.shopify.com/). The goal is to see if it works with [Astro](https://astro.build).

```bash
npm create astro@latest -- --template getmarkus/astro-shopify-polaris
```

[Live Demo](https://www.cmsoftdev.com/astro-shopify-polaris/). Please keep in mind this is a work in progress and not functionally complete.

Breaking down this implementation into three broad steps.

### See if Shopify's opinionated React components play well with Astro

So far so good, Shopify's design system and [React components](https://github.com/Shopify/polaris/tree/main/polaris-react) seem to work well together on first attempt. The only core requirement was to make sure the Components are always wrapped in their [App provider](https://polaris.shopify.com/components/utilities/app-provider).

### See if this integrates in with Shopify's system (WIP)

As would be expected Shopify has requirements for building Apps and Admin extentions that developers need to [follow](https://shopify.dev/docs/apps/tools#app-templates).

Shopify recommends and provides [remix](https://github.com/Shopify/shopify-app-template-remix) and [node](https://github.com/Shopify/shopify-app-template-node) templates to get started. So this next experiment will be to see if Astro also works.

### Finish out and comply with the full suite of App Design Guildlines (WIP)

Are their any Astro gotchas? I doubt it but this last step will test it out. Need to makes sure this will cover Shopify's [App Design Guidelines](https://shopify.dev/docs/apps/design-guidelines)
