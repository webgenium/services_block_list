# Services Block List

Este repositório contém listas de bloqueio de serviços para uso em firewalls. Cada serviço é organizado por categoria e possui arquivos separados para diferentes tipos de bloqueio.

## Estrutura

```
<categoria>/
└── <serviço>/
    ├── domains.txt   # Domínios a serem bloqueados
    ├── urls.txt      # URLs específicas a serem bloqueadas
    └── ips.txt       # Endereços IP a serem bloqueados
```

Cada tipo de arquivo permite configurar o bloqueio em pontos distintos do firewall:

| Arquivo | Uso |
|---|---|
| `domains.txt` | Bloqueio por domínio (DNS/Layer 7) |
| `urls.txt` | Bloqueio por URL específica (proxy/Layer 7) |
| `ips.txt` | Bloqueio por endereço IP (Layer 3/4) |

## Categorias disponíveis

- `games/` — Jogos online
- `social_media/` — Redes sociais

## Serviços disponíveis

| Categoria | Serviço |
|---|---|
| `games` | `roblox` |
| `social_media` | `facebook` |