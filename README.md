# MARGEM 5.0 — Meu caderno, minha rotina

Um caderno digital para transformar planos, ideias e cuidados em folhas bonitas que podem ser copiadas manualmente no papel.

## Novidade: Minha rotina pessoal

A tela inicial ganhou uma área **Minha rotina, do meu jeito**, com duas folhas editáveis e prontas para exportação:

- **Meu ritmo diário** — A4 horizontal, três colunas (manhã, tarde e noite), caixas para os dias da semana, escola, curso, cuidados, alimentação, água, leitura, estudo, descanso, horários e observações.
- **Meus cuidados da semana** — A4 vertical, tabela semanal para quarto, roupas de cama, cuidados pessoais, mochila, notas, faltas, prazos e tempo para si.

As duas folhas também podem ser abertas pelo menu do Editor ou criadas em **Modelos**. O editor permite adicionar, excluir, reorganizar ou reescrever hábitos, escolher desenhos e exportar a folha como PDF pela impressão do navegador.

Os modelos são adicionados **uma única vez** ao navegador na primeira abertura da atualização, sem apagar os documentos existentes. Continuamos utilizando a chave `margem.caderno.v1`; a configuração de instalação é `margem.personal-sheets.v1`. Se o usuário apagar as folhas, elas não serão recriadas automaticamente; ele pode criar outra em Modelos. Faça backups em JSON.

## Recursos existentes

- Editor de rotinas tradicionais em orientação vertical ou horizontal.
- Mapas mentais com tema central e ramos editáveis.
- Biblioteca de desenhos artísticos, simples e de cotidiano noturno, com importação de imagens autorizadas.
- Salvamento local sem contas, com exportação/importação de backup.
- PDF de uma página A4 pela opção **Gerar PDF → Salvar como PDF** (habilite gráficos de fundo para preservar o papel creme).

## Arquivos

- `index.html` — Aplicativo e biblioteca de ilustrações originais à tinta integradas.
- `urban-art.js` — 28 desenhos de cotidiano noturno, usados no editor e nos novos modelos.

Mantenha os arquivos lado a lado na raiz do repositório; o projeto é estático e funciona no GitHub Pages.

## Saúde e planejamento

A rotina é uma proposta **editável**, não uma prescrição médica. O fio dental foi colocado à noite. Enxágue bucal, se usado, aparece como opcional, em horário separado da escovação. Não foi incluído limão. As quantidades de água são lembretes ajustáveis e não uma meta universal de saúde. Horários de escola e curso são referências para dias letivos; não há obrigação de marcar tarefas escolares aos fins de semana.

## Publicação

Ative em **Settings → Pages → Deploy from a branch → main → /(root)**.

https://meurepertorio.github.io/margem-caderno/
