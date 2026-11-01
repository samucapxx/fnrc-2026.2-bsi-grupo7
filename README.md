# Projeto FNRC 2026.2 — BSI | Grupo 7

Repositório destinado à documentação das atividades práticas da disciplina de
**Fundamentos de Redes de Computadores (FNRC)**, do curso de **Bacharelado em
Sistemas de Informação (BSI)**, semestre 2026.2.

O projeto envolve a criação, configuração e validação de máquinas virtuais,
com foco em endereçamento IP, configuração de interfaces de rede, resolução
de nomes e comunicação entre as máquinas.

## 👥 Integrantes

- Leonardo Silva
- Samuel Lima de Souza
- David Emiliano de Oliveira
- Maxwell Barbosa de Carvalho Santo

## 📁 Estrutura do Repositório

```text
fnrc-2026.2-bsi-grupo7/
├── README.md
├── 01-planejamento.md
├── 02-criacao-das-vms.md
├── 03-usuarios.md
├── 04-rede-netplan.md
├── 05-hostname-e-hosts.md
├── 06-testes.md
├── configs/
│   ├── hosts/
│   ├── netplan/
│   └── validacao/
└── imagens/
```

## 📚 Documentação do Projeto

| Etapa | Descrição | Arquivo |
|---|---|---|
| 01 | Planejamento, endereçamento IP, nomes, usuários e topologia | [01-planejamento.md](01-planejamento.md) |
| 02 | Criação das VMs e instalação do Ubuntu Server | [02-criacao-das-vms.md](02-criacao-das-vms.md) |
| 03 | Criação dos usuários dos integrantes | [03-usuarios.md](03-usuarios.md) |
| 04 | Configuração da rede em modo Ponte e IP estático via Netplan | [04-rede-netplan.md](04-rede-netplan.md) |
| 05 | Configuração dos hostnames e do arquivo `/etc/hosts` | [05-hostname-e-hosts.md](05-hostname-e-hosts.md) |
| 06 | Testes de conectividade, SSH e resolução de nomes | [06-testes.md](06-testes.md) |

## 🌐 Configurações da Rede

| Item | Configuração |
|---|---|
| IP da sub-rede | `192.168.26.112` |
| IP de broadcast | `192.168.26.127` |
| Interface WAN | `enp0s3` |
| Interface LAN | `enp0s8` |
| Domínio | `grupo7.bsi-26-2.maceio.lab` |

As interfaces de rede utilizadas nas VMs são:

- `enp0s3`: interface WAN;
- `enp0s8`: interface LAN.

## 🖥️ Identificação das Máquinas Virtuais

| VM | Nome |
|---|---|
| Gateway | `G7-PC1-GW` |
| VM 1 | `G7-PC1-VM1` |
| VM 2 | `G7-PC1-VM2` |
| VM 3 | `G7-PC2-VM1` |
| VM 4 | `G7-PC2-VM2` |
| VM 5 | `G7-PC3-VM1` |
| VM 6 | `G7-PC3-VM2` |
| VM 7 | `G7-PC4-VM1` |
| VM 8 | `G7-PC4-VM2` |

## ⚙️ Arquivos de Configuração

- **Arquivo hosts** — configuração da resolução de nomes utilizada nas VMs.
- **Configurações Netplan** — arquivos YAML responsáveis pela configuração
  das interfaces de rede.
- **Validações** — saídas dos scripts de validação executados nas máquinas
  virtuais.
- **Imagens** — capturas de tela utilizadas como evidência das configurações
  e dos testes.

## 🔗 Link do Projeto

[Repositório do Grupo 7](https://github.com/samucapxx/fnrc-2026.2-bsi-grupo7)
