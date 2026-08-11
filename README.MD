# NM Assistência | Gestão Técnica

Sistema web para gestão de assistência técnica da **NM Assistência**, focado em orçamentos, ordens de serviço, histórico de atendimentos e controle financeiro.

O projeto foi desenvolvido para rodar como site estático no **GitHub Pages**, com interface responsiva e integração externa com Google Planilhas para persistência dos registros.

## Acesso

```text
https://assistecia.nathanmariotto.com.br
```

## Funcionalidades

- Cadastro de orçamentos e ordens de serviço
- Geração de mensagem pronta para envio ao cliente pelo WhatsApp
- Histórico com busca, filtros, edição, duplicação e exclusão
- Cálculo automático de valor bruto, gastos, lucro previsto e margem
- Controle de valores recebidos e valores em aberto
- Exportação dos registros em CSV
- Interface responsiva para desktop e mobile
- Integração com planilha externa já preparada para uso do sistema

## Tecnologias

- HTML5
- CSS3
- JavaScript vanilla
- Font Awesome
- Google Fonts
- GitHub Pages
- Google Planilhas via camada externa de integração

## Estrutura

```text
.
├── index.html
├── CNAME
├── .gitignore
└── midia.nmassistecia/
```

## Design

A interface usa a identidade visual da NM Assistência, com base em tons escuros, azul tecnológico, branco e elementos visuais da marca.

As principais decisões de UI foram:

- painel inicial direto e minimalista
- foco em ações rápidas de atendimento
- indicadores financeiros visíveis
- formulários organizados por fluxo de trabalho
- histórico pensado para consulta no dia a dia

## Segurança

Informações internas de integração, scripts locais, credenciais e arquivos sensíveis não fazem parte do repositório público.

## Autor

Projeto desenvolvido por **Nathan Mariotto** para uso operacional da **NM Assistência Técnica**.
