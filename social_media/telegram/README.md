# Telegram — Block List

Pasta de bloqueio para **Telegram**, contendo domínios, IPs, URLs e ASNs para uso em firewalls.

## Resumo da coleta

| Arquivo | Entradas | Descrição |
|---|---|---|
| `domains.txt` | 12 | Domínios e subdomínios conhecidos |
| `ips.txt` | 15 | Blocos de IP / CIDRs |
| `urls.txt` | 0 | URLs específicas para bloqueio |
| `asn.txt` | 2 | Números de Sistema Autônomo (ASN) |

**Data da coleta:** 2026-03-09

## ASNs

| ASN |
|---|
| `AS211157` |
| `AS62041` |

## Uso no firewall

| Arquivo | Camada | Aplicação |
|---|---|---|
| `domains.txt` | DNS / Layer 7 | Bloqueio por domínio via DNS ou proxy |
| `ips.txt` | Layer 3/4 | Bloqueio por endereço IP ou CIDR |
| `urls.txt` | Layer 7 | Bloqueio por URL específica via proxy |
| `asn.txt` | Layer 3 | Bloqueio de todo o bloco de roteamento do AS |

## Observações

Os dados foram coletados de Netify.ai e do arquivo CIDR oficial do Telegram (core.telegram.org/resources/cidr.txt). Não foram identificadas URLs específicas para bloqueio além dos domínios principais. As listas de bloqueio do HaGeZi e StevenBlack não continham informações específicas sobre o Telegram além dos domínios já identificados.

---

> **Fonte:** Dados coletados de fontes públicas (bgp.he.net, ipinfo.io, HaGeZi DNS Blocklists, StevenBlack Hosts, documentação oficial).
> Atualizado em: 2026-03-09
