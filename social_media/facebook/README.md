# Facebook — Block List

Pasta de bloqueio para **Facebook**, contendo domínios, IPs, URLs e ASNs para uso em firewalls.

## Resumo da coleta

| Arquivo | Entradas | Descrição |
|---|---|---|
| `domains.txt` | 13 | Domínios e subdomínios conhecidos |
| `ips.txt` | 8 | Blocos de IP / CIDRs |
| `urls.txt` | 7 | URLs específicas para bloqueio |
| `asn.txt` | 1 | Números de Sistema Autônomo (ASN) |

**Data da coleta:** 2026-03-09

## ASNs

| ASN |
|---|
| `AS32934` |

## Uso no firewall

| Arquivo | Camada | Aplicação |
|---|---|---|
| `domains.txt` | DNS / Layer 7 | Bloqueio por domínio via DNS ou proxy |
| `ips.txt` | Layer 3/4 | Bloqueio por endereço IP ou CIDR |
| `urls.txt` | Layer 7 | Bloqueio por URL específica via proxy |
| `asn.txt` | Layer 3 | Bloqueio de todo o bloco de roteamento do AS |

## Observações

Os dados foram coletados de diversas fontes, incluindo ipinfo.io, bgp.he.net, GitHub (dyne/domain-list, JamieFarrelly/Popular-Site-Subdomains) e artigos relacionados. As URLs com curinga (*.fbcdn.net, *.akamaihd.net) são sugestões para bloqueio de CDNs. A lista de IPs pode não ser exaustiva, pois as redes são dinâmicas.

---

> **Fonte:** Dados coletados de fontes públicas (bgp.he.net, ipinfo.io, HaGeZi DNS Blocklists, StevenBlack Hosts, documentação oficial).
> Atualizado em: 2026-03-09
