# TikTok — Block List

Pasta de bloqueio para **TikTok**, contendo domínios, IPs, URLs e ASNs para uso em firewalls.

## Resumo da coleta

| Arquivo | Entradas | Descrição |
|---|---|---|
| `domains.txt` | 37 | Domínios e subdomínios conhecidos |
| `ips.txt` | 10 | Blocos de IP / CIDRs |
| `urls.txt` | 5 | URLs específicas para bloqueio |
| `asn.txt` | 1 | Números de Sistema Autônomo (ASN) |

**Data da coleta:** 2026-03-09

## ASNs

| ASN |
|---|
| `AS138699` |

## Uso no firewall

| Arquivo | Camada | Aplicação |
|---|---|---|
| `domains.txt` | DNS / Layer 7 | Bloqueio por domínio via DNS ou proxy |
| `ips.txt` | Layer 3/4 | Bloqueio por endereço IP ou CIDR |
| `urls.txt` | Layer 7 | Bloqueio por URL específica via proxy |
| `asn.txt` | Layer 3 | Bloqueio de todo o bloco de roteamento do AS |

## Observações

A lista de domínios, URLs, IPs e ASN foi compilada a partir de fontes públicas, incluindo gists do GitHub, o repositório de hosts de StevenBlack e informações do ipinfo.io. A cobertura pode não ser exaustiva e pode exigir atualizações periódicas.

---

> **Fonte:** Dados coletados de fontes públicas (bgp.he.net, ipinfo.io, HaGeZi DNS Blocklists, StevenBlack Hosts, documentação oficial).
> Atualizado em: 2026-03-09
