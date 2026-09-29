# Clause Creator Studio

<p align="center">
  <strong>Crie, personalize e gerencie contratos em um só lugar.</strong><br/>
  Uma plataforma web para organizar modelos, montar documentos jurídicos e acompanhar contratos com uma experiência simples e intuitiva.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-18-149eca?logo=react&logoColor=white" alt="React 18" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178c6?logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-5-646cff?logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-3-06b6d4?logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/shadcn%2Fui-components-000000?logo=shadcnui&logoColor=white" alt="shadcn/ui" />
</p>

---

## Sobre o projeto

O **Clause Creator Studio** é uma aplicação voltada à criação e gestão de contratos. O sistema reúne ferramentas para elaborar documentos a partir de modelos, personalizar cláusulas, revisar informações e acompanhar contratos em um ambiente centralizado.

A aplicação também oferece recursos de conta de usuário, área administrativa e organização de modelos e cláusulas.

## Funcionalidades

* **Editor de contratos:** criação e edição de documentos com campos personalizáveis.
* **Modelos prontos:** galeria de modelos para iniciar documentos com mais agilidade.
* **Biblioteca de cláusulas:** consulta e organização de cláusulas reutilizáveis.
* **Pré-visualização e revisão:** confira o conteúdo do contrato antes de finalizar.
* **Exportação em PDF:** gere uma versão do documento para compartilhamento ou armazenamento.
* **Histórico de contratos:** acompanhe documentos criados anteriormente.
* **Assinatura desenhada:** componente de assinatura para inserir uma representação manuscrita no documento.
* **Autenticação:** telas de cadastro, login e recuperação de senha.
* **Perfil e painel administrativo:** áreas dedicadas à conta e à administração.
* **Interface responsiva:** componentes construídos com React, Tailwind CSS e shadcn/ui.

> **Observação:** a ferramenta auxilia na elaboração e organização de documentos, mas não substitui a análise de um profissional jurídico. Revise o conteúdo e a adequação legal de cada contrato antes de utilizá-lo.

## Tecnologias

| Tecnologia            | Utilização                          |
| --------------------- | ----------------------------------- |
| React 18              | Construção da interface             |
| TypeScript            | Tipagem estática                    |
| Vite                  | Servidor de desenvolvimento e build |
| Tailwind CSS          | Estilização                         |
| shadcn/ui e Radix UI  | Componentes de interface            |
| React Router          | Navegação entre páginas             |
| React Hook Form e Zod | Formulários e validação             |
| Tiptap                | Edição de conteúdo                  |
| jsPDF e html2canvas   | Geração de documentos PDF           |
| Framer Motion         | Animações                           |
| TanStack Query        | Gerenciamento de estado assíncrono  |

## Requisitos

* Node.js (versão LTS recomendada)
* npm ou Bun
* Acesso à API configurada para o ambiente, quando aplicável

## Instalação e execução

Clone o repositório:

```bash
git clone https://github.com/brenodev2007/clause-creator-studio.git
cd clause-creator-studio
```

Instale as dependências:

```bash
npm install
```

Configure as variáveis de ambiente, se necessário. Para produção, utilize o arquivo de exemplo:

```bash
cp .env.production.example .env.production
```

Edite os valores de acordo com seu ambiente:

```env
VITE_API_URL=https://api.seudominio.com
VITE_APP_NAME=ContrateMe
VITE_ENV=production
```

Inicie o servidor local:

```bash
npm run dev
```

O Vite exibirá no terminal o endereço local para acessar a aplicação.

## Scripts disponíveis

| Comando             | Descrição                                     |
| ------------------- | --------------------------------------------- |
| `npm run dev`       | Inicia o servidor de desenvolvimento          |
| `npm run build`     | Gera a versão de produção                     |
| `npm run build:dev` | Gera o build usando o modo de desenvolvimento |
| `npm run preview`   | Executa uma prévia local do build             |
| `npm run lint`      | Analisa o código com ESLint                   |

## Build de produção

Para gerar os arquivos otimizados:

```bash
npm run build
```

Os arquivos gerados ficam no diretório `dist/` e podem ser publicados em um serviço de hospedagem estática compatível com aplicações Vite. Configure as variáveis de ambiente e o redirecionamento de rotas conforme a infraestrutura utilizada.

## Estrutura do projeto

```text
src/
├── components/       # Componentes reutilizáveis e interface
├── context/          # Contextos de autenticação e tokens
├── data/             # Modelos e conteúdos de referência
├── hooks/            # Hooks personalizados
├── lib/              # Utilitários
├── pages/            # Páginas e fluxos da aplicação
└── types/            # Tipos TypeScript
```

## Autor

**Breno Soriani**

* GitHub: [@brenodev2007](https://github.com/brenodev2007)

---

<p align="center">
  Desenvolvido para tornar a criação e a organização de contratos mais prática.
</p>
