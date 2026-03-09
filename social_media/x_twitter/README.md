# X (Twitter) — Block List

Pasta de bloqueio para **X (Twitter)**, contendo domínios, IPs, URLs e ASNs para uso em firewalls.

## Resumo da coleta

| Arquivo | Entradas | Descrição |
|---|---|---|
| `domains.txt` | 25 | Domínios e subdomínios conhecidos |
| `ips.txt` | 13 | Blocos de IP / CIDRs |
| `urls.txt` | 0 | URLs específicas para bloqueio |
| `asn.txt` | 1 | Números de Sistema Autônomo (ASN) |

**Data da coleta:** 2026-03-09

## ASNs

| ASN |
|---|
| `AS13414` |

## Uso no firewall

| Arquivo | Camada | Aplicação |
|---|---|---|
| `domains.txt` | DNS / Layer 7 | Bloqueio por domínio via DNS ou proxy |
| `ips.txt` | Layer 3/4 | Bloqueio por endereço IP ou CIDR |
| `urls.txt` | Layer 7 | Bloqueio por URL específica via proxy |
| `asn.txt` | Layer 3 | Bloqueio de todo o bloco de roteamento do AS |

## Observações

Os domínios e IPs foram coletados de netify.ai, ipinfo.io e github.com/v2fly/domain-list-community. Não foram encontradas URLs específicas para bloqueio além dos domínios listados. Alguns blocos de IP podem ser compartilhados com outras entidades, conforme indicado na fonte ipinfo.io para 188.64.224.0/21 (X INTERNET UNLIMITED COMPANY).

---

> **Fonte:** Dados coletados de fontes públicas (bgp.he.net, ipinfo.io, HaGeZi DNS Blocklists, StevenBlack Hosts, documentação oficial).
> Atualizado em: 2026-03-09
