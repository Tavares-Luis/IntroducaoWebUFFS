# ConectaPesquisa

O **ConectaPesquisa** é uma aplicação web desenvolvida para centralizar e divulgar oportunidades de Iniciação Científica (IC) e projetos de pesquisa acadêmica. O sistema visa combater a fragmentação de informações nas universidades, facilitando a conexão entre estudantes e professores orientadores.

**ODS 4 - Educação de Qualidade:** O projeto atua diretamente na meta de aumentar o número de jovens com habilidades relevantes para o mercado e área de pesquisa, garantindo o acesso democrático à Iniciação Científica e auxiliando na retenção de alunos no ensino superior.

## Tecnologias que vamos utilizar:
* **Estruturação:** HTML
* **Estilização:** CSS e Tailwind
* **Interatividade:** JavaScript (Verificar se vamos ainda)
* **Prototipação:** Figma

## Funcionalidades e Telas
* **Landing Page:** Apresentação do projeto e direcionamento de perfis (Aluno/Professor).
* **Feed de Vagas:** Listagem estática de oportunidades de pesquisa.
* **Filtros e Buscas:** Simulação de filtros (via JavaScript) por área de conhecimento e tipo de bolsa. (Se conseguimos)
* **Contato Simplificado:** Formulário interativo para simular o envio de interesse ao professor. (Se conseguimos)

## Paleta de cores
As cores ficam no arquivo `src/input.css`, dentro do `@theme`.

| Cor | Hexadecimal | Onde usamos |
|---|---|---|
| Fundo | `#F5F5F0` | Fundo das páginas |
| Cinza claro | `#E8E8E3` | Fundo da seção de oportunidades |
| Branco | `#FFFFFF` | Fundo dos cards e formulários |
| Cinza | `#CCCCCC` | Bordas |
| Escuro | `#222222` | Textos principais e botões |
| Cinza do texto | `#4A5565` | Textos secundários (datas, universidade) |

**Por que essas cores:** o site é para alunos e professores de universidade, então escolhemos uma paleta séria, neutra e limpa, só com tons de cinza. O fundo quase branco e os cinzas deixam a leitura confortável e não cansam a vista, já que as vagas têm bastante texto. Os botões ficam no cinza bem escuro, um preto praticamente, que se destaca no fundo claro e mostra rápido onde clicar. Sem cores fortes, a atenção fica no conteúdo, que são os projetos de pesquisa.

**Padrão de contraste:** aqui foi pesquisado padrões de contraste e segundo a WCAG (Web Content Accessibility Guidelines ou Diretrizes de Acessibilidade para Conteúdo Web) o mínimo seria de 4,5:1.
O 4,5:1 mede o quanto o texto se destaca do fundo. É uma razão de contraste: compara o brilho da cor do texto com o brilho da cor do fundo.

Como ler o número:
* **1:1** é contraste nenhum, por exemplo texto branco em fundo branco, que é invisível.
* **21:1** é o máximo possível, texto preto em fundo branco.
* Quanto maior o primeiro número, mais fácil de ler.

**Contraste (texto x fundo):** conferimos o contraste das combinações principais. Todas passam do mínimo de 4,5:1 recomendado para leitura.
* Texto escuro `#222222` no fundo `#F5F5F0`: 14,5:1
* Texto escuro `#222222` no branco `#FFFFFF`: 15,9:1
* Texto branco `#FFFFFF` no botão escuro `#222222`: 15,9:1
* Texto secundário `#4A5565` no fundo `#F5F5F0`: 6,9:1

## Cronograma
* **Sprint 1:** Concepção estrutural, wireframes de baixa fidelidade e levantamento de requisitos. (Concluído)
* **Sprint 2:** Criação dos arquivos HTML e estilização de todas as telas utilizando Tailwind CSS. (Realizando)
* **Sprint 3:** Adição de scripts em JavaScript para simular filtros, abrir modais e validar o formulário de contato. (A iniciar)


(O Felipe não entrou no git ainda por que eu esqueci de fazer antes , mas ele ajudou a fazer a parte do documento do projeto, elaborar a ideia, etc.)
