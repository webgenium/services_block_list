# Services Block List

Este repositório contém listas de bloqueio de serviços para uso em firewalls. Cada serviço é organizado por categoria e possui arquivos separados para diferentes tipos de bloqueio.

## Estrutura

```
<categoria>/
└── <serviço>/
    ├── README.md     # Informações sobre a coleta e uso
    ├── domains.txt   # Domínios e subdomínios a serem bloqueados
    ├── urls.txt      # URLs específicas a serem bloqueadas
    ├── ips.txt       # Endereços IP / CIDRs a serem bloqueados
    └── asn.txt       # Números de Sistema Autônomo (ASN)
```

Cada tipo de arquivo permite configurar o bloqueio em pontos distintos do firewall:

| Arquivo | Camada | Uso |
|---|---|---|
| `domains.txt` | DNS / Layer 7 | Bloqueio por domínio via DNS ou proxy |
| `urls.txt` | Layer 7 | Bloqueio por URL específica via proxy |
| `ips.txt` | Layer 3/4 | Bloqueio por endereço IP ou bloco CIDR |
| `asn.txt` | Layer 3 | Bloqueio de todo o bloco de roteamento do AS |

## Categorias disponíveis

- `games/` — Jogos online
- `social_media/` — Redes sociais

## Serviços disponíveis

| Categoria | Serviço | Domínios | IPs | URLs | ASN |
|---|---|---|---|---|---|
| `games` | `roblox` | 1 | — | — | — |
| `social_media` | `facebook` | 13 | 8 | 7 | 1 |
| `social_media` | `instagram` | 14 | 122 | — | 1 |
| `social_media` | `whatsapp` | 388 | 244 | 13 | 3 |
| `social_media` | `tiktok` | 37 | 10 | 5 | 1 |
| `social_media` | `telegram` | 12 | 15 | — | 2 |
| `social_media` | `linkedin` | 17 | 8 | — | 1 |
| `social_media` | `snapchat` | 24 | 8 | — | 1 |
| `social_media` | `reddit` | 27 | 9 | — | 1 |
| `social_media` | `pinterest` | 436 | 7 | — | 1 |
| `social_media` | `x_twitter` | 25 | 13 | — | 1 |
| `social_media` | `threads` | 4 | 150 | 4 | 1 |

## Fontes

Os dados foram coletados de fontes públicas e projetos opensource de segurança de rede:

- [HaGeZi DNS Blocklists](https://github.com/hagezi/dns-blocklists)
- [StevenBlack Hosts](https://github.com/StevenBlack/hosts)
- [bgp.he.net](https://bgp.he.net) — consulta de ASNs e CIDRs
- [ipinfo.io](https://ipinfo.io) — informações de IP e ASN
- Documentação oficial de cada plataforma
