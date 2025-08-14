# nMethod - Método da Ness (BMAD-Compatible)

Este repositório contém a implementação do método da Ness em formato compatível com o **BMAD-METHOD** (Breakthrough Method for Agile AI-Driven Development).

## 🚀 Sobre o nMethod

O **nMethod** é a implementação customizada do método da Ness, adaptando o framework BMAD para as verticais e papéis específicos da empresa. Ele integra:

- **Agentes especializados** por função e vertical
- **Equipes (bundles)** organizadas por área de atuação
- **Workflows** específicos para cada processo
- **Templates** e **checklists** de governança
- **Integração com IDEs** (Cursor, VSCode, etc.)

## 📁 Estrutura BMAD

```
nMethod/
├── README.md
├── LICENSE
└── .bmad-core/
    ├── agents/           # Agentes por cargo/função
    ├── agent-teams/      # Bundles por vertical da Ness
    ├── tasks/            # Tarefas executáveis
    ├── templates/        # Templates YAML
    ├── workflows/        # Fluxos de trabalho
    ├── checklists/       # Listas de verificação
    ├── data/             # Dados de referência
    ├── utils/            # Utilitários
    └── bmad-core/        # Core BMAD
```

## 🎯 Verticais Implementadas

### Operacionais
- **n.secops** 🛡️ - Segurança Operacional
- **n.cirt** 🚨 - Resposta a Incidentes
- **n.devarch** 🏗️ - Desenvolvimento e Arquitetura
- **n.autoops** ⚙️ - Automação e Orquestração
- **n.infraops** 🖥️ - Infraestrutura e Operações

### Empresas Internas
- **trustness.** 🏛️ - Assessment e Compliance
- **forense.io** 🧪 - Forense Digital

### Backoffice
- **backoffice** 📊 - Administrativo
- **escritório-projetos** 📋 - Gestão de Projetos
- **comercial** 💼 - Vendas e Marketing
- **jurídico** ⚖️ - Assessoria Jurídica
- **branding** 🎨 - Identidade Visual
- **facilities** 🏢 - Segurança Física

## 🔧 Como Usar

### 1. Seleção de Equipe
Escolha o agent-team da vertical desejada:

```bash
# Exemplos de equipes disponíveis
team-n-secops.yaml      # Segurança Operacional
team-n-cirt.yaml        # Resposta a Incidentes
team-n-devarch.yaml     # Desenvolvimento
team-trustness.yaml     # Assessment
team-forense-io.yaml    # Forense Digital
team-nmethod-complete.yaml  # Equipe completa
```

### 2. Ativação de Agentes
Cada equipe inclui agentes especializados com:
- **Comandos específicos** por função
- **Workflows** adaptados ao processo
- **Templates** e **checklists** de governança

### 3. Integração com IDE
O nMethod inclui regras para:
- **Cursor** (configurado automaticamente)
- **VSCode** (configurável)
- **Outros IDEs** (extensível)

## 🌟 Funcionalidades Principais

### Agentes Especializados
- **Ícones específicos** por função
- **Comandos especializados** por área
- **Dependências** de tasks e checklists
- **Integração** com workflows

### Workflows por Área
- **n.secops**: incident-response, vulnerability-mgmt
- **n.cirt**: incident-intake, post-incident-review
- **n.devarch**: greenfield-fullstack, brownfield-fullstack
- **trustness.**: security-assessment, privacy-implementation
- **forense.io**: forensic-chain-of-custody, forensic-case-lifecycle

### Templates e Checklists
- **PRD** (Product Requirements Document)
- **Arquitetura** (geral, fullstack, frontend)
- **Project Brief**
- **PM/PO/Arch** checklists
- **Story DoD** (Definition of Done)
- **Change Management**

## 🎨 Personalização

O nMethod é facilmente customizável:

1. **Modificar agentes** em `.bmad-core/agents/`
2. **Ajustar equipes** em `.bmad-core/agent-teams/`
3. **Adicionar workflows** em `.bmad-core/workflows/`
4. **Criar templates** em `.bmad-core/templates/`

## 📖 Documentação

- **User Guide**: `.bmad-core/user-guide.md`
- **Core Architecture**: `.bmad-core/core-config.yaml`
- **Install Manifest**: `.bmad-core/install-manifest.yaml`

## 🔄 Atualizações

Para atualizar o nMethod:

```bash
# Atualizar BMAD core
npx bmad-method install

# Regenerar agentes específicos da Ness
python3 generate_nmethod.py
```

## 🤝 Contribuição

Para contribuir com o nMethod:

1. Modifique os agentes/equipes conforme necessário
2. Teste a integração com BMAD
3. Documente mudanças
4. Siga os padrões BMAD

## 📄 Licença

MIT License - veja arquivo LICENSE.

---

**nMethod** - Método da Ness integrado ao **BMAD-METHOD**  
**Gerado com ❤️ para a Ness**
