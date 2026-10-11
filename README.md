# Ficha de Aventura — As Montanhas Shamutanti

Ficha digital interativa para o livro-jogo *As Montanhas Shamutanti*.

## Como usar
- **Versão publicada (recomendada):** abra o link da ficha no Claude. O progresso fica salvo na sua conta e funciona em qualquer aparelho.
- **Versão local:** dê dois cliques em `index.html`. O progresso fica salvo apenas no navegador deste computador.
- **Salvar jogo:** guarda o momento atual com um nome (até 30 jogos salvos) ou em um arquivo `.json`.
- **Carregar jogo:** volta a um jogo salvo ou abre um arquivo `.json`. Desfazer retorna à ficha anterior.
- **Limpar ficha:** zera todos os campos (pode manter o nome). Jogos salvos não são apagados.
- Para levar o jogo de um lugar para o outro: **Salvar jogo → Salvar em arquivo** e, no destino, **Carregar jogo → Abrir arquivo**.
- Guarde os arquivos `.json` na pasta `saves` deste projeto.

## Caminho no livro
Digite a página que está lendo e clique em **Adicionar** (ou Enter). A trilha aparece abaixo: `1 → 25 → 33 → …`.
A última página fica destacada e também vira a **Seção atual**. Páginas repetidas aparecem sublinhadas.
**Remover última** desfaz uma página adicionada por engano.

## Atributos
Cada atributo (Habilidade, Energia, Sorte) tem:
- **Inicial:** o valor que você rolou e anotou. Não muda com o jogo.
- **Atual:** resultado depois das alterações. Não é digitado: muda só pelas alterações.
- **Alteração (pontos):** digite quantos pontos e clique em **Reduzir** ou **Aumentar** (ou digite -2 e Enter). A Energia pode chegar a zero.
- **Histórico:** as alterações aparecem como marcas (−2, +4…). Passe o mouse para ver o motivo e a seção.
- Combate, testes de Sorte, refeições, feitiços e Libra registram suas alterações automaticamente.
- **Anotação:** linha livre para observações.

## Itens que aumentam o ataque
Ao adicionar um item à mochila, escolha o **tipo** (comum, arma, escudo/armadura, joia/amuleto) e informe o **bônus de ataque**.
O bônus soma à sua força de ataque nos combates. Só **uma arma** conta por vez (vale a de maior bônus); escudos, armaduras e joias somam.
O bônus de cada item pode ser corrigido direto na lista da mochila.

## Criaturas com regras especiais
Na caixa de encontro, clique em **Regras** para:
- mudar o dano do golpe da criatura ou do seu golpe;
- criar um **golpe especial**: quando a criatura fere você, rola-se 1 dado; a partir do valor escolhido o golpe causa um dano maior, que pode ser evitado com Teste de Sorte;
- anotar outras regras da seção.
O botão **Usar modelo: Mantícora** preenche o ferrão venenoso: com 5 ou 6 no dado, 6 de dano, a menos que você seja sortudo.

## Regras aplicadas pela ficha
- Criação: Guerreiro (Habilidade 1d6+6) ou Mago (1d6+4); Energia 2d6+12; Sorte 1d6+6. 20 peças de ouro, 2 provisões, espada e mochila.
- Valores atuais nunca passam dos iniciais, salvo quando marcado "passar do inicial".
- Combate: 2d6 + Habilidade de cada lado; o maior fere (−2 de Energia); empate ninguém fere.
- Testar a Sorte: 2d6 ≤ Sorte atual = sortudo; sempre −1 de Sorte. Efeitos próprios em combate.
- Libra: uma única ajuda por aventura (Revitalização, Fuga ou Remoção de maldições e doenças).
- Mago: feitiços por código de três letras, custo descontado da Energia. Grimório não pode ser consultado.

## Diário automático
Registra com o número da seção: encontros com criaturas, início e fim de combate (vitória, morte ou interrupção),
itens da mochila, bônus/penalidades/maldições/doenças, pistas, provisões, ouro, testes de sorte, feitiços e Libra.

## Arquivos
- `index.html` — a ficha (arquivo único, abre no navegador; também funciona pelo GitHub Pages).
- `LEIA-ME.md` — este guia.

## Aviso
Ferramenta de fã, sem vínculo com os autores ou editoras do livro. O livro e a ficha impressa pertencem aos seus detentores; este repositório contém apenas o código da ficha digital.
