# Infraestrutura Docker — homeserver

Repositório de infraestrutura Docker do servidor `homeserver`.

## Princípios
- Infra como código
- Containers isolados
- Dados persistentes fora do Git
- Host mínimo (SSH + Tailscale)

## Estrutura
- `proxy/` → reverse proxy
- `monitoring/` → monitoramento
- `apps/` → aplicações

## Dados
Dados persistentes vivem em `/data`.

## Backups
Backups vivem em `/backups`.
