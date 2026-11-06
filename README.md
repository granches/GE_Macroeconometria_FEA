# Site do Grupo de Estudos em Macroeconometria

Versão preparada para **GitHub Pages + Pages CMS**, a partir do HTML fornecido. O visual, os textos e as seções originais foram mantidos; o conteúdo editável está nos arquivos JSON da pasta `content/`.

## 1 — Publicar no GitHub Pages (sem pagar)

1. Crie uma conta em https://github.com/ (caso ainda não tenha).
2. No GitHub, clique em **New repository**. Nome sugerido: `GE_Macroeconometria_FEA`. Escolha **Public** (plano gratuito).
3. Extraia o arquivo ZIP. No repositório, escolha **Add file → Upload files**, e envie **todos os arquivos e pastas de dentro da pasta extraída**, mantendo `index.html`, `.pages.yml` e `content/` na raiz. Não envie o ZIP fechado e não crie uma segunda subpasta dentro do repositório.
   - Se o Windows ocultar os arquivos iniciados com ponto, certifique-se de incluir especificamente `.pages.yml` (é obrigatório para o painel) e, se possível, `.nojekyll` (recomendado).
4. Confirme as alterações pelo botão **Commit changes**.
5. Em **Settings → Pages → Build and deployment**, defina **Source: Deploy from a branch**; **Branch: main** e **Folder: / (root)**, depois **Save**.
6. O endereço será `https://SEUUSUARIO.github.io/GE_Macroeconometria_FEA/` (substitua `SEUUSUARIO` pelo nome da conta; se mudar o nome do repositório, mude o final da URL).
7. Verifique a publicação nas configurações Pages. Propagação inicial pode levar alguns minutos.

## 2 — Ativar o painel Pages CMS

1. Acesse https://app.pagescms.org/ e entre com a mesma conta do GitHub.
2. Autorize/instale o aplicativo Pages CMS para o repositório `GE_Macroeconometria_FEA` (prefira conceder acesso somente a esse repositório).
3. Selecione o repositório e a branch `main`.
4. As opções no painel serão **Informações gerais e conferência**, **Membros**, **Pesquisas e publicações** e **Eventos — próximos e passados**.
5. Altere uma informação, salve e confira o site público. A gravação modifica os arquivos JSON no GitHub, e o GitHub Pages publica a atualização automaticamente.

## 3 — Como atualizar o site normalmente

- **Eventos:** acesse `Eventos — próximos e passados`, inclua ou edite um registro. Preencha `Exibir em` com `Eventos próximos` ou `Eventos passados`; quando a reunião acabar, altere o mesmo registro para `Eventos passados`. Informe uma `Data para ordenar` quando disponível; `TBA` pode ficar sem data. O site ordena os próximos crescentemente e os passados decrescentemente.
- **Membros:** abra `Membros`; escolha a categoria Professor, Doutorado ou Mestrado. O campo Lattes só vira link no site quando receber uma URL HTTPS válida.
- **Pesquisas:** abra `Pesquisas e publicações` e adicione ano, autores, tipo e, se houver, o link.
- **Conferência / horários / contato:** abra `Informações gerais e conferência`.
- **Rascunho:** o aviso de rascunho segue inicialmente ativo, porque o HTML original tem campos `[Nome]`, `[tema de pesquisa]` e `TBA`. Depois de completar os dados, desative `Mostrar aviso de rascunho`.

## Estrutura dos arquivos

```text
index.html                Site público; layout original, com atualização automática a partir dos JSON
.pages.yml                Configuração dos formulários do Pages CMS
.nojekyll                 Desativa transformação por Jekyll no GitHub Pages
content/site.json         Sobre, conferência, horários e contato
content/members.json      Membros
content/publications.json Publicações
content/events.json       Eventos próximos e passados
media/                    Pasta opcional para futuros arquivos
```

## Observações importantes

- Não é necessário contratar hospedagem, domínio, banco de dados ou pagar o Pages CMS para este uso.
- Os arquivos de conteúdo são públicos, pois fazem parte do repositório público; não coloque dados privados nele.
- **O HTML pode ser aberto diretamente no computador**, mas os navegadores geralmente bloqueiam a leitura dos arquivos JSON via `file://`. Nesse caso, aparece a versão original de reserva, não necessariamente as edições recentes. Para testar a edição, use a URL pública do GitHub Pages ou rode um servidor local, por exemplo `python -m http.server 8000`, dentro da pasta, e entre em `http://localhost:8000/`.
- Sem JavaScript, o site exibe o conteúdo original incorporado no HTML. Com JavaScript habilitado, os JSON editados passam a fornecer o conteúdo atualizado.
- Arquivos de código e aparência só precisam ser editados quando você decidir mudar a estrutura ou o visual.

## Documentação oficial

- GitHub Pages: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Pages CMS: https://pagescms.org/docs/quick-start/
- Configuração Pages CMS: https://pagescms.org/docs/configuration/

## 4 — Acervo acadêmico do grupo

A pasta `materiais/` é destinada a slides, notas e outros documentos do grupo. Há subpastas `2026/` e `2027/`, cada uma com um `.gitkeep` para que apareça no GitHub mesmo vazia. Consulte `materiais/README.md` para o padrão de organização e instruções de upload.

**Atenção:** publicar arquivos dentro de `materiais/` os torna acessíveis publicamente pelo repositório. A inclusão de links para esses arquivos nas páginas do site pode ser configurada posteriormente.
