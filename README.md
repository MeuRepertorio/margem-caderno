# MARGEM 4.0 — Caderno, desenhos e mapa mental

**Um caderno digital feito para transformar planos, ideias e cuidados em folhas que podem ser copiadas à mão.**

## Novidades desta versão

- **Cotidiano noturno:** nova coleção de 28 desenhos individuais, extraídos e preparados a partir de composições artísticas originais aprovadas na conversa: fones de ouvido, café, livros, meias, cama, janela à noite, skyline, gato, fotografias, estrelas, e outros objetos e cenas. Ficam disponíveis em **Desenhos → Cotidiano noturno** para inserir, arrastar, girar e redimensionar.
- **Orientação da folha:** escolha vertical/retrato ou horizontal/paisagem, tanto para rotina quanto para mapa mental; a exportação usa o formato A4 adequado.
- **Mapa mental:** em **Folha → Modelo de organização → Mapa mental**, escreva o tema, edite ramos e sub-ramos, arraste os nós diretamente na folha e exporte o desenho completo em PDF. Crie um mapa novo a partir de **Modelos → Mapa mental**.
- **Preserva seus modelos:** a chave de armazenamento segue como `margem.caderno.v1`, mantendo os documentos salvos neste mesmo dispositivo/navegador. Novos campos são opcionais e recebem valores padrão quando modelos antigos são carregados.

## Arquivos do site

- `index.html`: aplicativo e biblioteca artística anterior incorporada.
- `urban-art.js`: nova coleção de 28 ilustrações processadas, pronta para funcionar offline, sem depender de imagens externas.

**Os dois arquivos precisam ficar lado a lado na raiz do repositório.** O MARGEM é hospedável diretamente no GitHub Pages e não exige build, banco de dados, conta ou biblioteca externa.

## Publicação no GitHub Pages

Em **Settings → Pages**, selecione **Deploy from a branch**, `main`, `/ (root)`.

URL do projeto: https://meurepertorio.github.io/margem-caderno/

## Como criar o PDF

Em **Gerar PDF**, escolha **Salvar como PDF** na janela de impressão. A orientação acompanha a escolha na folha e o tamanho é A4. Habilite **Gráficos de fundo** para preservar a cor do papel e os desenhos.

## Privacidade e backups

Os dados continuam armazenados no próprio navegador com `localStorage`; não há sincronização automática. Faça backup JSON regularmente, especialmente antes de limpar o navegador.

## Direitos e referências

As novas imagens são recortes processados de ilustrações originais geradas para esta coleção, não cópias de obras obtidas do Pinterest. É possível importar desenhos próprios ou que você tenha permissão de usar.