# Claude Code Avançado — Aula

Repositório de apoio ao curso **Claude Code Avançado**, cobrindo técnicas, configurações e fluxos de trabalho para uso profissional do Claude Code CLI.

## Conteúdo

- Configurações avançadas do Claude Code (`.claude/settings.json`)
- Uso de hooks (PreToolUse, PostToolUse, Stop)
- MCP Servers — instalação e configuração
- Subagentes e fluxos paralelos
- Context Mode e gerenciamento de janela de contexto
- Skills personalizadas
- Automação com Cron e Schedule
- Integração com GitHub, IDEs e ferramentas externas

## Pré-requisitos

- [Node.js](https://nodejs.org/) 18+
- [Claude Code CLI](https://claude.ai/code) instalado globalmente

```bash
npm install -g @anthropic-ai/claude-code
```

- Conta Anthropic com acesso à API

## Instalação

```bash
# Clone o repositório
git clone https://github.com/josediaspro/Claude-Code-Avancado-Aula.git
cd Claude-Code-Avancado-Aula

# Instale dependências (se houver)
npm install
```

Consulte o arquivo `arq. de instalações.txt` para instruções específicas de ferramentas e pacotes utilizados nas aulas.

## Como usar

Abra o diretório no terminal e inicie o Claude Code:

```bash
claude
```

Cada módulo do curso possui exemplos prontos para rodar diretamente no REPL do Claude Code.

## Estrutura do Projeto

```
.
├── README.md
├── arq. de instalações.txt   # Dependências e ferramentas das aulas
└── .claude/
    └── settings.json         # Configurações do Claude Code (criado nas aulas)
```

## Licença

MIT © [josediaspro](https://github.com/josediaspro)
