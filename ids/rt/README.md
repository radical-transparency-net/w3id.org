# /rt/

Permanent identifiers for the **Radical Transparency Network** (open science & semantic interoperability).

- Homepage: <https://radical-transparency.net/>
- Semantic Assets Repository: <https://github.com/radical-transparency-net/semantic-assets>

## Structure & Redirects

- [`./.htaccess`](./.htaccess) — Redirects `https://w3id.org/rt/` (`302`) to <https://radical-transparency.net/>.
- [`./ns/.htaccess`](./ns/.htaccess) — Manages RDF vocabulary namespaces under `https://w3id.org/rt/ns/*`:

| Identifier | Accept / Extension | Status | Target |
| :--- | :--- | :--- | :--- |
| `https://w3id.org/rt/ns/weblink` | `text/turtle` or `.ttl` | `303` | `https://radical-transparency-net.github.io/semantic-assets/weblink/weblink.ttl` |
| `https://w3id.org/rt/ns/weblink` | `application/ld+json` or `.jsonld` | `303` | `https://radical-transparency-net.github.io/semantic-assets/weblink/weblink.jsonld` |
| `https://w3id.org/rt/ns/weblink` | `application/linkset+json` or `.linkset.json` | `303` | `https://radical-transparency-net.github.io/semantic-assets/weblink/weblink.linkset.json` |
| `https://w3id.org/rt/ns/weblink` | `application/linkset` or `.linkset` | `303` | `https://radical-transparency-net.github.io/semantic-assets/weblink/weblink.linkset` |
| `https://w3id.org/rt/ns/weblink` | `text/html` / default or `.html` | `303` | `https://radical-transparency-net.github.io/semantic-assets/weblink/index.html` |

All `/rt/ns/weblink` responses also expose `Link` headers pointing to the RFC 9264 variant-menu linksets (`application/linkset+json` and `application/linkset`) in accordance with Radical Transparency pattern **RT-P03**.

## Contacts

- Marc Portier (Flanders Marine Institute - VLIZ)
  - <marc.portier@vliz.be>
  - ORCID: [0000-0002-9648-6484](https://orcid.org/0000-0002-9648-6484)
  - GitHub: [@marc-portier](https://github.com/marc-portier)
- Cedric Decruw (Flanders Marine Institute - VLIZ)
  - ORCID: [0000-0001-6387-5988](https://orcid.org/0000-0001-6387-5988)
  - GitHub: [@cedricd](https://github.com/cedricd)
