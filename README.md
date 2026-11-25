# ConectaPesquisa

O **ConectaPesquisa** é um protótipo de site para aproximar estudantes de oportunidades de Iniciação Científica e projetos acadêmicos. A proposta é centralizar a divulgação dessas oportunidades e facilitar o contato entre estudantes e professores orientadores.

## Entrega da Sprint 2

Esta versão parcial apresenta páginas HTML semânticas, estilizadas com Tailwind CSS e conectadas por navegação entre páginas:

- **Início (`index.html`):** apresentação do projeto e oportunidades em destaque.
- **Oportunidades (`oportunidades.html`):** listagem de projetos com campos de busca e filtros demonstrativos.
- **Contato (`contato.html`):** formulário demonstrativo de contato.

Os links entre as páginas funcionam. A busca, os filtros e o envio do formulário ainda são apenas elementos visuais nesta etapa; a interatividade e a integração do formulário estão previstas para a Sprint 3.

## Tecnologias

- HTML5 semântico
- Tailwind CSS v4
- npm para compilar o CSS

Não há JavaScript nesta entrega.

## Identidade visual e paleta

| Cor | Código | Uso |
| --- | --- | --- |
| Azul-marinho | `#0F172A` | Títulos, textos de destaque e botões |
| Azul | `#1D4ED8` | Links, categorias e elementos de ênfase |
| Cinza-escuro | `#475569` | Texto secundário |
| Cinza-claro | `#E2E8F0` | Bordas e divisórias |
| Branco | `#FFFFFF` | Fundo de cartões e áreas de conteúdo |
| Fundo claro | `#F8FAFC` | Fundo geral das páginas |

O azul e o azul-marinho reforçam confiança e conhecimento, associados à pesquisa acadêmica. Fundos claros e texto escuro mantêm a leitura confortável; o azul é reservado para destaques e links. As combinações foram escolhidas para manter contraste entre texto e fundo.

## Executar localmente

Instale as dependências e compile o CSS:

```bash
npm install
npm run build
```

Depois, abra `index.html` no navegador ou inicie um servidor estático na raiz do projeto. Durante o desenvolvimento, use `npm run watch` para recompilar o CSS após alterações.

## Próximas etapas

- Implementar busca e filtros com JavaScript.
- Conectar o formulário de contato a um serviço de envio.
- Substituir os dados de exemplo por oportunidades reais.

## Objetivo social

O projeto relaciona-se ao **ODS 4 — Educação de Qualidade**, ao facilitar o acesso de estudantes a oportunidades de iniciação científica e pesquisa acadêmica.
