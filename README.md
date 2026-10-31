# MARGEM — Seu caderno, do seu jeito

**Uma página de caderno digital feita para ser copiada no papel.**

O MARGEM é um site estático e independente. Não precisa de instalação, conta, servidor, banco de dados, biblioteca externa nem serviço pago. A versão inicial inclui:

- Editor de rotina com **manhã, tarde e noite**, hábitos com horários opcionais e tabela de segunda a domingo;
- Campos de objetivo, data, observações e assinatura;
- Folha pautada com margem vermelha e furos de caderno escolar;
- Dez ilustrações vetoriais: aranha, flor, estrela, chama, lua, galho, rabisco, personagem, vela e pentagrama;
- Ferramentas para arrastar, redimensionar, girar, mudar cor e remover desenhos;
- Modelos prontos, folha em branco, duplicação e exclusão;
- Salvamento local no navegador, sem rastreamento de realização de hábitos;
- Exportação de backup em JSON, importação de backup e cópia do texto;
- Exportação PDF via **Imprimir → Salvar como PDF**, com layout de caderno em uma página A4;
- Adaptação para celulares e computadores.

## Abrir localmente

Abra `index.html` em um navegador moderno, mesmo sem internet. A criação do PDF usa a ferramenta de impressão do próprio navegador.

## Publicar no GitHub Pages

1. Entre em https://github.com/new e crie um repositório público chamado `margem-caderno` (ou outro nome).
2. Abra o repositório e clique em **Add file → Upload files**.
3. Envie os arquivos `index.html` e `README.md` que estão dentro deste ZIP (não envie apenas o ZIP).
4. Faça o commit (Confirmar alterações).
5. Vá a **Settings → Pages → Build and deployment → Deploy from a branch**.
6. Selecione `main`, pasta `/ (root)` e clique **Save**.
7. Depois que o Pages terminar a publicação, o endereço será `https://SEU-USUARIO.github.io/margem-caderno/`, se esse for o nome escolhido.

## Privacidade e backup

Os modelos são salvos com `localStorage` no dispositivo e navegador utilizados. Não há sincronização entre aparelhos. Limpar os dados do navegador pode apagar seus modelos; por isso, exporte um backup `.json` de tempos em tempos. A importação de backup **substitui** os modelos existentes, após confirmação.

## Observação sobre PDF

A exportação usa `window.print()`. Na janela de impressão, escolha **Salvar como PDF** e, se houver a opção, **Gráficos de fundo** para manter as pautas coloridas. O tamanho externo é A4 por compatibilidade com leitores e impressoras; o design da página é de caderno escolar.

## Licença

Projeto pessoal. Você pode editar, publicar e adaptar o código livremente.