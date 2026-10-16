# Missão Código - Revisão de Lógica de Programação

Atividade online **autocorrigível** para revisão das aulas 01 a 10, desenvolvida com HTML, CSS e JavaScript. O site é estático, funciona no GitHub Pages e não precisa de banco de dados ou bibliotecas externas.

## Conteúdos

1. Algoritmos, entrada-processamento-saída e fluxogramas
2. Variáveis, tipos, operadores e conversão de entrada
3. Condicionais, operadores relacionais e lógica booleana
4. `while`, `for`, `range` e contadores
5. Vetores, matrizes e índices
6. Funções, retorno e recursividade
7. Filas e FIFO
8. Bubble Sort, Merge Sort e mesclagem
9. Python, `input`, `random` e jogos simples
10. Git, GitHub, Fork, Commit, README, Pull Request e introdução às APIs

São **40 desafios em 10 missões**, misturando múltipla escolha, associação, organização de blocos e preenchimento de código. Cada desafio vale até 25 XP. Associação e ordem permitem pontuação parcial.

## Publicar no GitHub Pages

1. Crie um repositório **público**, por exemplo `missao-codigo-revisao`.
2. Envie o arquivo **`index.html` para a raiz do repositório**, junto deste `README.md`.
3. Abra **Settings > Pages**.
4. Em **Build and deployment > Source**, selecione **Deploy from a branch**.
5. Escolha o branch **main** e a pasta **/(root)** e clique em **Save**.
6. Aguarde a publicação e use **Visit site** na seção Pages para abrir a atividade.

O endereço costuma seguir o formato `https://USUARIO.github.io/NOME-DO-REPOSITORIO/`, desde que a publicação esteja configurada corretamente.

## Instruções para estudantes fazerem Fork

1. Acesse o repositório do professor e clique em **Fork**.
2. Confirme a criação do repositório na sua conta.
3. Abra `index.html` pelo Pages configurado na sua cópia, **ou** acesse o link do Pages do professor para responder, sem a necessidade de republicar.
4. Ao terminar, clique em **Copiar comprovante** ou **Baixar resultado .TXT** e envie o comprovante na plataforma indicada pelo professor.
5. Para praticar alterações no GitHub, edite **uma frase do cabeçalho ou da descrição** do `index.html` no seu Fork e salve com um Commit. O botão **Preview** do GitHub não executa necessariamente o site; confira no Pages ou abra o HTML no navegador.

**Importante:** um Fork não ativa automaticamente o Pages em todos os casos. Cada aluno que quiser hospedar seu próprio site pode precisar entrar em Settings > Pages no Fork. Se o objetivo é apenas responder, todos podem utilizar a mesma URL publicada pelo professor.

## Sobre o ranking final

A comparação usa uma **turma fictícia de 32 notas pré-definidas** no JavaScript, somente como brincadeira motivacional. A média e a posição **não representam resultados reais** dos colegas. Essa informação aparece tanto na abertura quanto nos resultados e no comprovante.

**Não existe painel do professor, coleta remota de notas ou classificação real.** O progresso é armazenado localmente no navegador (`localStorage`), no próprio aparelho do aluno. Limpar os dados do navegador elimina esse progresso. Respostas são corrigidas localmente e podem ser consultadas no código-fonte, portanto a atividade é formativa, não uma prova segura.

## Personalizar

- Altere o título e o texto de abertura no `index.html`.
- Mude as perguntas no vetor `QUESTION_BANK` no bloco `<script>` ao final do arquivo.
- Cada pergunta usa `stage` de 0 a 9 e `type` (`choice`, `fill`, `match`, `order`).
- O código atual espera **40 questões e quatro por missão**. Para alterar essa quantidade, ajuste a validação e, se mudar a distribuição, também a navegação de missões.
- Se você modificar a estrutura das perguntas, altere também a constante `KEY` para evitar conflito com progresso previamente salvo.
- Altere `MOCK_CLASS` se desejar outra distribuição de *notas fictícias*. Deixe claro que se trata de simulação.

## Execução local

Abra `index.html` em um navegador moderno. Não precisa instalar Node.js, Python, npm nem qualquer pacote.

Desenvolvido como material didático para a Aula 10 de Lógica de Programação.
