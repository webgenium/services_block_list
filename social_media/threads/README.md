# Threads — Block List

Pasta de bloqueio para **Threads**, contendo domínios, IPs, URLs e ASNs para uso em firewalls.

## Resumo da coleta

| Arquivo | Entradas | Descrição |
|---|---|---|
| `domains.txt` | 4 | Domínios e subdomínios conhecidos |
| `ips.txt` | 150 | Blocos de IP / CIDRs |
| `urls.txt` | 4 | URLs específicas para bloqueio |
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

Os IPs e domínios foram coletados de fontes públicas como ScaniteX e um Gist do GitHub. A lista de URLs é baseada nos domínios principais da plataforma Threads, pois não foram encontradas URLs específicas para bloqueio em APIs ou CDNs nas pesquisas iniciais. Recomenda-se monitoramento contínuo para atualizações.

---

> **Fonte:** Dados coletados de fontes públicas (bgp.he.net, ipinfo.io, HaGeZi DNS Blocklists, StevenBlack Hosts, documentação oficial).
> Atualizado em: 2026-03-09
