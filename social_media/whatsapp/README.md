# WhatsApp — Block List

Pasta de bloqueio para **WhatsApp**, contendo domínios, IPs, URLs e ASNs para uso em firewalls.

## Resumo da coleta

| Arquivo | Entradas | Descrição |
|---|---|---|
| `domains.txt` | 388 | Domínios e subdomínios conhecidos |
| `ips.txt` | 244 | Blocos de IP / CIDRs |
| `urls.txt` | 13 | URLs específicas para bloqueio |
| `asn.txt` | 3 | Números de Sistema Autônomo (ASN) |

**Data da coleta:** 2026-03-09

## ASNs

| ASN |
|---|
| `AS11917` |
| `AS32934` |
| `AS63293` |

## Uso no firewall

| Arquivo | Camada | Aplicação |
|---|---|---|
| `domains.txt` | DNS / Layer 7 | Bloqueio por domínio via DNS ou proxy |
| `ips.txt` | Layer 3/4 | Bloqueio por endereço IP ou CIDR |
| `urls.txt` | Layer 7 | Bloqueio por URL específica via proxy |
| `asn.txt` | Layer 3 | Bloqueio de todo o bloco de roteamento do AS |

## Observações

Domínios e IPs foram coletados de listas públicas do GitHub (HybridNetworks/whatsapp-cidr) e informações do Netify AI. As URLs são exemplos de endpoints relevantes para bloqueio. É importante notar que a lista de IPs do GitHub pode conter entradas que não são CIDRs, mas IPs individuais. Além disso, a lista de domínios foi filtrada para remover entradas que contêm ".fna.whatsapp.net" pois são domínios de CDN dinâmicos e muito numerosos, podendo ser menos úteis para bloqueio estático em firewalls.

---

> **Fonte:** Dados coletados de fontes públicas (bgp.he.net, ipinfo.io, HaGeZi DNS Blocklists, StevenBlack Hosts, documentação oficial).
> Atualizado em: 2026-03-09
