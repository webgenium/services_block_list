# Pinterest — Block List

Pasta de bloqueio para **Pinterest**, contendo domínios, IPs, URLs e ASNs para uso em firewalls.

## Resumo da coleta

| Arquivo | Entradas | Descrição |
|---|---|---|
| `domains.txt` | 436 | Domínios e subdomínios conhecidos |
| `ips.txt` | 7 | Blocos de IP / CIDRs |
| `urls.txt` | 0 | URLs específicas para bloqueio |
| `asn.txt` | 1 | Números de Sistema Autônomo (ASN) |

**Data da coleta:** 2026-03-09

## ASNs

| ASN |
|---|
| `AS53620` |

## Uso no firewall

| Arquivo | Camada | Aplicação |
|---|---|---|
| `domains.txt` | DNS / Layer 7 | Bloqueio por domínio via DNS ou proxy |
| `ips.txt` | Layer 3/4 | Bloqueio por endereço IP ou CIDR |
| `urls.txt` | Layer 7 | Bloqueio por URL específica via proxy |
| `asn.txt` | Layer 3 | Bloqueio de todo o bloco de roteamento do AS |

## Observações

Os domínios e IPs foram coletados de Netify.ai e de uma blocklist do GitHub (daylamtayari/Pi-Hole-Blocklist). A lista de domínios pode incluir subdomínios de CDNs e serviços de terceiros usados pelo Pinterest. A cobertura pode não ser exaustiva e pode exigir atualizações periódicas. URLs específicas para bloqueio não foram identificadas de forma distinta nas fontes consultadas, portanto, o campo está vazio.

---

> **Fonte:** Dados coletados de fontes públicas (bgp.he.net, ipinfo.io, HaGeZi DNS Blocklists, StevenBlack Hosts, documentação oficial).
> Atualizado em: 2026-03-09
