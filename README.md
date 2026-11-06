# Grupo de Estudos em Macroeconometria

**Departamento de Economia · FEA-USP**

O Grupo de Estudos em Macroeconometria reúne estudantes de mestrado e doutorado interessados nos métodos empíricos da macroeconomia e das finanças e em suas aplicações à pesquisa econômica. Nossos encontros são dedicados à leitura e discussão de artigos, à apresentação de pesquisas em andamento e ao intercâmbio de ideias entre estudantes, professores e demais interessados.

Este repositório reúne o **site do grupo**, as apresentações realizadas nos encontros e materiais de apoio às atividades acadêmicas.

**[Acessar o site](https://granches.github.io/GE_Macroeconometria_FEA/)** · **[Consultar o acervo](./materiais/)** · **[Ver a programação](https://granches.github.io/GE_Macroeconometria_FEA/#eventos)**

## Encontros e participação

- **Quando:** quintas-feiras, às 10h.
- **Onde:** Sala Delfim Netto, FEA-USP, Cidade Universitária, São Paulo.
- **Participação:** aberta a estudantes, docentes, pesquisadores e profissionais interessados no tema.

A programação, os textos de cada reunião e eventuais alterações de horário ou local são divulgados no [site do grupo](https://granches.github.io/GE_Macroeconometria_FEA/). Para participar ou apresentar um trabalho, entre em contato pelo e-mail [granches@usp.br](mailto:granches@usp.br).

O grupo também prevê uma **conferência em abril de 2027**. Datas, programação e chamada de trabalhos serão anunciadas no site, conforme confirmadas.

## Acervo acadêmico

O acervo é organizado por ano e encontro. Sempre que disponíveis e autorizados para divulgação, reunimos os slides e outros materiais elaborados pelos apresentadores, além de referências para os textos discutidos.

**Apresentações disponíveis:**

| Data | Texto discutido | Apresentador | Material |
| --- | --- | --- | --- |
| 29/10/2026 | Stock e Watson (2017), *Twenty Years of Time Series Econometrics in Ten Pictures* | Giosvaldo Júnior | [Slides (PDF)](./materiais/2026/2026-10-29-stock-watson/slides.pdf) |
| 05/11/2026 | Nakamura e Steinsson (2018), *Identification in Macroeconomics* | Lucas Oliveira | [Slides (PDF)](./materiais/2026/2026-11-05-nakamura-steinsson/slides.pdf) |

Também está disponível o [cronograma de leituras (XLSX)](./materiais/cronograma-de-leituras.xlsx), com bibliografia e planejamento de estudo. Os encontros e materiais mais recentes podem ser consultados no site.

## Organização do repositório

```text
GE_Macroeconometria_FEA/
├── index.html              # Página pública do grupo
├── .pages.yml              # Configuração do painel de edição
├── content/                # Dados do site em JSON
│   ├── site.json           # Informações gerais e conferência
│   ├── members.json        # Membros
│   ├── publications.json   # Pesquisas e publicações
│   └── events.json         # Encontros e eventos
├── materiais/              # Apresentações e documentos do grupo
│   ├── 2026/
│   ├── 2027/
│   └── cronograma-de-leituras.xlsx
└── media/                  # Arquivos de mídia do site
```

## Como atualizar o site e contribuir

O site é publicado gratuitamente pelo **GitHub Pages**. A edição de textos e registros é feita pelo **[Pages CMS](https://app.pagescms.org/)**, conectado à branch `main` deste repositório.

**Para atualizar a programação, membros ou publicações:**

1. Entre no Pages CMS com uma conta autorizada no repositório.
2. Escolha a seção correspondente e edite os campos no formulário.
3. Salve as alterações. Elas serão registradas no GitHub e publicadas no site.
4. A lista pública de eventos passados é atualizada automaticamente de acordo com a data e o horário do encontro. Para novos eventos, preencha **Data e hora do encontro (para destaque automático)**.

**Para acrescentar slides ou notas de um encontro:**

1. Crie uma pasta `materiais/AAAA/AAAA-MM-DD-tema/` no repositório local.
2. Adicione os arquivos próprios do grupo (por exemplo, `slides.pdf` e `notas.md`).
3. Envie as alterações ao GitHub, por exemplo pelo GitHub Desktop (**Commit** e **Push origin**).
4. No Pages CMS, informe o caminho do arquivo no campo **Slides (PDF)** do respectivo evento, por exemplo `./materiais/2026/2026-11-05-nakamura-steinsson/slides.pdf`.

Para contribuir, é necessário ter permissão de edição no repositório. Quem não tiver acesso pode encaminhar materiais ou sugestões pelo e-mail do grupo.

## Uso dos materiais

Este é um repositório público, destinado à divulgação das atividades acadêmicas do grupo. A autoria dos slides, notas e demais trabalhos deve ser preservada. A disponibilização de um arquivo **não implica autorização irrestrita para sua reprodução ou redistribuição**.

Artigos e livros de terceiros são preferencialmente referenciados por DOI, páginas dos periódicos ou outras fontes autorizadas, sem reprodução de cópias protegidas por direitos autorais.

---

**Grupo de Estudos em Macroeconometria · FEA-USP**  
[Site](https://granches.github.io/GE_Macroeconometria_FEA/) · [Contato](mailto:granches@usp.br)
