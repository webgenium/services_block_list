# Reddit — Block List

Pasta de bloqueio para **Reddit**, contendo domínios, IPs, URLs e ASNs para uso em firewalls.

## Resumo da coleta

| Arquivo | Entradas | Descrição |
|---|---|---|
| `domains.txt` | 27 | Domínios e subdomínios conhecidos |
| `ips.txt` | 9 | Blocos de IP / CIDRs |
| `urls.txt` | 0 | URLs específicas para bloqueio |
| `asn.txt` | 1 | Números de Sistema Autônomo (ASN) |

**Data da coleta:** 2026-03-09

## ASNs

| ASN |
|---|
| `AS36492` |

## Uso no firewall

| Arquivo | Camada | Aplicação |
|---|---|---|
| `domains.txt` | DNS / Layer 7 | Bloqueio por domínio via DNS ou proxy |
| `ips.txt` | Layer 3/4 | Bloqueio por endereço IP ou CIDR |
| `urls.txt` | Layer 7 | Bloqueio por URL específica via proxy |
| `asn.txt` | Layer 3 | Bloqueio de todo o bloco de roteamento do AS |

## Observações

A ASN AS36492 foi identificada como pertencente ao Google, LLC, e não diretamente ao Reddit, Inc. A pesquisa por um ASN oficial do Reddit não retornou resultados conclusivos. Os blocos de IP foram obtidos de fontes de pesquisa e podem não ser exaustivos.

---

> **Fonte:** Dados coletados de fontes públicas (bgp.he.net, ipinfo.io, HaGeZi DNS Blocklists, StevenBlack Hosts, documentação oficial).
> Atualizado em: 2026-03-09
