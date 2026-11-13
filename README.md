<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img src="assets/hero-light.svg" width="100%" alt="Khaled Al-Haj Salem — Senior Software Engineer, Backend & Systems Architect. SaaS platforms, FinTech and payments, e-invoicing. Gaza, Palestine.">
</picture>

<br>

I design and build backend systems, APIs and business-critical platforms: SaaS products, payment and financial integrations, and e-invoicing. I work across the whole backend lifecycle — architecture, database design, API development, integrations, performance and production troubleshooting — mostly in PHP and Laravel.

More than ten years of production work have left me with a clear preference: clean architecture, reliability and long-term maintainability over quick fixes. I'm happiest on systems where correctness, security and scale actually matter.

Currently **Senior Software Engineer at Tarat** (remote).

## Open source

Saudi Arabia's Phase 2 e-invoicing rules ask a lot of every single invoice: it has to be built as UBL XML, hashed, cryptographically signed, chained to the invoice before it, given a QR code, and then cleared or reported through ZATCA's API. Integrating that for the first time was a real challenge, so I turned what I learned into libraries anyone can use.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/pipeline-dark.svg">
  <img src="assets/pipeline-light.svg" width="100%" alt="The steps the libraries perform: invoice data → UBL 2.1 XML → SHA-256 hash → ECDSA signature → QR code → cleared or reported by ZATCA.">
</picture>

<table>
  <tr>
    <td width="38%" valign="top">
      <a href="https://github.com/khaledhajsalem/zatca-php"><b>zatca-php</b></a><br>
      <a href="https://github.com/khaledhajsalem/zatca-php/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/khaledhajsalem/zatca-php?style=flat-square&labelColor=1e293b&color=059669"></a>
      <a href="https://packagist.org/packages/khaledhajsalem/zatca-php"><img alt="Packagist downloads" src="https://img.shields.io/packagist/dt/khaledhajsalem/zatca-php?style=flat-square&labelColor=1e293b&color=059669"></a>
      <a href="https://packagist.org/packages/khaledhajsalem/zatca-php"><img alt="Latest version" src="https://img.shields.io/packagist/v/khaledhajsalem/zatca-php?style=flat-square&labelColor=1e293b&color=475569&label=release"></a>
    </td>
    <td valign="top">
      The whole Phase 2 flow for <b>PHP</b>: XML generation, signing, QR codes, device onboarding, clearance and reporting. Its invoice scenarios are checked, one by one, against ZATCA's own sandbox validator.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <a href="https://github.com/khaledhajsalem/zatca-node"><b>zatca-node</b></a><br>
      <a href="https://github.com/khaledhajsalem/zatca-node/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/khaledhajsalem/zatca-node?style=flat-square&labelColor=1e293b&color=059669"></a>
      <a href="https://www.npmjs.com/package/@khaledhajsalem/zatca-node"><img alt="npm downloads" src="https://img.shields.io/npm/dm/%40khaledhajsalem%2Fzatca-node?style=flat-square&labelColor=1e293b&color=059669"></a>
      <a href="https://www.npmjs.com/package/@khaledhajsalem/zatca-node"><img alt="Latest version" src="https://img.shields.io/npm/v/%40khaledhajsalem%2Fzatca-node?style=flat-square&labelColor=1e293b&color=475569&label=release"></a>
    </td>
    <td valign="top">
      The same flow for <b>Node.js</b>, written in TypeScript: invoice processing, signing and submission.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>ZATCA Hub for Laravel</b><br>
      <img alt="In progress" src="https://img.shields.io/badge/status-in%20progress-b45309?style=flat-square&labelColor=1e293b">
    </td>
    <td valign="top">
      A self-hosted management center built on zatca-php: companies and devices, guided onboarding with ZATCA, encrypted credentials, in English and Arabic.
    </td>
  </tr>
</table>

<sub>These libraries are unofficial and are not affiliated with or endorsed by ZATCA.</sub>

Smaller things: [langchain-pdf-assistant](https://github.com/khaledhajsalem/langchain-pdf-assistant), a PDF question-answering assistant in Python, and [jspdf-vue-cli-arabic-example](https://github.com/khaledhajsalem/jspdf-vue-cli-arabic-example), a working recipe for printing Arabic PDFs from Vue.

## What I work on

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Architecture</b><br><br>
      Backend and systems architecture<br>
      REST API design<br>
      Database design and optimization
    </td>
    <td width="33%" valign="top">
      <b>Integrations</b><br><br>
      Payments and financial integrations<br>
      E-invoicing (ZATCA Phase 2)<br>
      Third-party services
    </td>
    <td width="33%" valign="top">
      <b>Production</b><br><br>
      Performance optimization<br>
      Troubleshooting live systems<br>
      Linux servers
    </td>
  </tr>
</table>

<p>
  <img alt="PHP" src="https://img.shields.io/badge/PHP-1e293b?style=flat-square&logo=php&logoColor=a5b4fc">
  <img alt="Laravel" src="https://img.shields.io/badge/Laravel-1e293b?style=flat-square&logo=laravel&logoColor=f87171">
  <img alt="Livewire" src="https://img.shields.io/badge/Livewire-1e293b?style=flat-square&logo=livewire&logoColor=f472b6">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-1e293b?style=flat-square&logo=nodedotjs&logoColor=86efac">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-1e293b?style=flat-square&logo=typescript&logoColor=93c5fd">
  <img alt="Vue" src="https://img.shields.io/badge/Vue-1e293b?style=flat-square&logo=vuedotjs&logoColor=6ee7b7">
  <img alt="Python" src="https://img.shields.io/badge/Python-1e293b?style=flat-square&logo=python&logoColor=fde68a">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-1e293b?style=flat-square&logo=mysql&logoColor=7dd3fc">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-1e293b?style=flat-square&logo=linux&logoColor=fcd34d">
  <img alt="Git" src="https://img.shields.io/badge/Git-1e293b?style=flat-square&logo=git&logoColor=fdba74">
</p>

## Path

<table>
  <tr><td><b>2024 — now</b></td><td>Senior Software Engineer · Tarat · remote</td></tr>
  <tr><td><b>2019 — 2025</b></td><td>Senior Software Engineer / Backend Engineer · iPhone Alsham · Gaza</td></tr>
  <tr><td><b>2018 — 2019</b></td><td>Full-stack Web Developer · FIS · Gaza</td></tr>
  <tr><td><b>2015 — 2019</b></td><td>Freelance Software Engineer, backend and APIs, for international clients</td></tr>
  <tr><td><b>Education</b></td><td>B.Sc. in Information Technology · Islamic University of Gaza</td></tr>
</table>

## Say hello

<a href="https://www.linkedin.com/in/khaledhajsalem/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-khaledhajsalem-1e293b?style=flat-square&logo=linkedin&logoColor=7dd3fc"></a>

<sub>The QR code at the top is real: it opens the same profile.</sub>
