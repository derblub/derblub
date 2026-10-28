<div align="center">

<a href="https://pushingpixels.at">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="banner-dark.svg" />
    <img src="banner-light.svg" alt="Pushing Pixels" width="870" height="120" />
  </picture>
</a>

# Daniel Kurdoghlian

**Developer and consultant · Vienna, Austria**

I test with your own examples whether AI can take over a task in your business, and whether it pays off. Then I build the solution myself.
Consulting and development stay with one person, so nothing gets lost in a handover. I also build web applications for founders and product teams.

[![Website](https://img.shields.io/badge/pushingpixels.at-000000?style=for-the-badge)](https://pushingpixels.at)
[![Bluesky](https://img.shields.io/badge/derblub.com-000000?style=for-the-badge&logo=bluesky&logoColor=white)](https://bsky.app/profile/derblub.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NSAyMC40NWgtMy41NXYtNS41N2MwLTEuMzMtLjAzLTMuMDQtMS44NS0zLjA0LTEuODYgMC0yLjE0IDEuNDUtMi4xNCAyLjk0djUuNjdIOS4zNVY5aDMuNDF2MS41NmguMDVjLjQ4LS45IDEuNjQtMS44NTAgMy4zNy0xLjg1IDMuNiAwIDQuMjcgMi4zNyA0LjI3IDUuNDZ2Ni4yOHpNNS4zNCA3LjQzYTIuMDYgMi4wNiAwIDEgMSAwLTQuMTIgMi4wNiAyLjA2IDAgMCAxIDAgNC4xMnpNNy4xMiAyMC40NUgzLjU2VjloMy41NnYxMS40NXpNMjIuMjIgMEgxLjc3Qy43OSAwIDAgLjc3IDAgMS43M3YyMC41NEMwIDIzLjIzLjc5IDI0IDEuNzcwIDI0aDIwLjQ1Yy45OCAwIDEuNzgtLjc3IDEuNzgtMS43M1YxLjczQzI0IC43NyAyMy4yIDAgMjIuMjIgMHoiLz48L3N2Zz4%3D)](https://www.linkedin.com/in/daniel-kurdoghlian)

</div>

---

### Open source

**[changereel](https://github.com/derblub/changereel)**: finds what a pull request changed on the pages of a site and shows it as a before and after video. Claude can add one sentence to each change. Runs as a GitHub Action and on the command line, which also comments on GitLab merge requests.

**[django-upgrade-report](https://github.com/derblub/django-upgrade-report)**: which of your dependencies block a Django upgrade, and in which order to upgrade them. It reads your lockfile, asks PyPI what every Django package declares and prints the plan. Also runs in CI as a GitHub Action.

```console
uvx django-upgrade-report
```

**[axe-routes](https://github.com/derblub/axe-routes)**: checks every route of a site with axe-core, from the sitemap, at desktop and phone size. Runs as a GitHub Action or from the command line and fails the build on a WCAG violation.

**[barrierefreiheitserklaerung-at](https://github.com/derblub/barrierefreiheitserklaerung-at)**: a template (in German) for the accessibility information the Austrian Barrierefreiheitsgesetz requires from online shops and booking flows, with a filled-in example.

Contributions to other projects:

- [nuxt/ui #7151](https://github.com/nuxt/ui/pull/7151): screen readers now get the pagination labels in the user's language (merged).
- [eslint-plugin-vuejs-accessibility #1489](https://github.com/vue-a11y/eslint-plugin-vuejs-accessibility/pull/1489): `anchor-has-content` no longer reports links that are hidden from screen readers with `aria-hidden` (merged).
- [django-auditlog #854](https://github.com/django-commons/django-auditlog/pull/854), [django-constance #678](https://github.com/django-commons/django-constance/pull/678): both are now tested on Django 6.1 and declare it, django-constance on 6.0 as well (merged).
- [google-keyword-planner-mcp #29](https://github.com/ncosentino/google-keyword-planner-mcp/pull/29), [#30](https://github.com/ncosentino/google-keyword-planner-mcp/pull/30), [#31](https://github.com/ncosentino/google-keyword-planner-mcp/pull/31): an MCP server that gives AI agents Google Keyword Planner data. Limited and enriched keyword ideas, ISO codes for targeting, forecasts requested in parallel (merged).

Most of my client work lives in private repositories on my own GitLab, so the contribution graph here shows only the public part.

---

### What I do

<table>
  <tr>
    <td width="33%" valign="top">
      <h4><a href="https://pushingpixels.at/creates/ki-beratung">AI consulting</a></h4>
      <p>An AI feasibility check from €1,900, with the result in one week: vendors compared on your own examples, a written assessment that is yours, then a prototype if it pays off.</p>
    </td>
    <td width="33%" valign="top">
      <h4><a href="https://pushingpixels.at/creates/web-apps">Web applications</a></h4>
      <p>Custom web applications with Django and Nuxt: architecture, APIs, testing and deployment.</p>
    </td>
    <td width="33%" valign="top">
      <h4><a href="https://pushingpixels.at/creates/devops-and-infra">DevOps and infrastructure</a></h4>
      <p>CI/CD pipelines, containers and cloud infrastructure that make deployments repeatable and outages visible.</p>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h4><a href="https://pushingpixels.at/creates/django-upgrades">Django upgrade audit</a></h4>
      <p>Fixed price: which dependencies block your upgrade, in which order to move, and what it will cost.</p>
    </td>
    <td width="33%" valign="top">
      <h4><a href="https://pushingpixels.at/creates/accessibility-audit">Accessibility audit</a></h4>
      <p>Fixed price: WCAG 2.2 AA with automated checks, keyboard and screen reader testing, and a prioritised list of fixes.</p>
    </td>
    <td width="33%" valign="top">
      <h4><a href="https://pushingpixels.at/creates/wordpress">WordPress</a></h4>
      <p>Custom Gutenberg builds and headless setups that marketing teams can run themselves.</p>
    </td>
  </tr>
</table>

---

### Case studies

14 case studies with code and interactive demos at [pushingpixels.at/portfolio](https://pushingpixels.at/portfolio), for example:

- [Zero-downtime schema migrations](https://pushingpixels.at/portfolio/zero-downtime-migrations): a four-million-row table changed during peak traffic.
- [Automated property exposés](https://pushingpixels.at/portfolio/pdf-generation): a 45-minute InDesign job per listing became a three-second generator.
- [Three payment gateways, one checkout](https://pushingpixels.at/portfolio/payment-orchestration): synchronous, redirect and webhook flows behind a single pipeline.

Articles: [Which packages block my Django upgrade?](https://pushingpixels.at/articles/django-upgrade-dependencies) · [Django 4.2 is end of life: what now?](https://pushingpixels.at/articles/django-4-2-end-of-life)

---

### Tech stack

- **Backend:** Django and Python on PostgreSQL, from [schema migrations under load](https://pushingpixels.at/portfolio/zero-downtime-migrations) to [payment pipelines](https://pushingpixels.at/portfolio/payment-orchestration).
- **Frontend:** Nuxt and Vue with TypeScript and Tailwind. [pushingpixels.at](https://pushingpixels.at) is built with them.
- **Infrastructure:** Docker, GitLab CI, AWS and Linux servers, see [DevOps and infrastructure](https://pushingpixels.at/creates/devops-and-infra).
- **Also:** WordPress and WooCommerce, Rust, PHP, Flask, React, Angular, Bash, Figma.

---

<div align="center">

**15+ years** · **30+ clients** · **50+ projects**

<a href="https://pushingpixels.at/contact"><img src="https://img.shields.io/badge/Get_in_touch-000000?style=for-the-badge" alt="Get in touch" height="40" /></a>

</div>
