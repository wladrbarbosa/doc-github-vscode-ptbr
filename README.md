# Dicas e fluxo de trabalho do vscode com Git

Repositório para exibir algumas dicas e demonstrar meu workflow na integração do vscode com o Git e outras utilidades sobre isso.

![Untitled Diagram drawio](https://user-images.githubusercontent.com/10834873/159021088-cbdb6945-782c-4c29-b365-195827348dc7.png)

## 1

A branch que se encontra o reposotório em questão. Nesse caso, a master.

## 2

Botão para sincronizar as alterações do repositório em questão, ou seja, git pull e em seguida, git push.

## 3

Botão para confirmar criação do commit no repositório em questão. Para isso, é necessário ter alterações pendentes no repositório.

## 4

Botão para criar pull requests no repositório em questão.

## 5

Botão para atualizar repositório em questão, ou seja um git pull.

## 6

Botão para abrir o Git Graph, uma extensão do vscode para uma visualização mais ampla dos commits, branches e tags.

## 7

Local para digitação da mensagem de commit. É recomendável que essa mensagem tenha um título e que seja menor que 50 caracteres para facilitar a visualização em alguns casos. Segue um exemplo de como eu costumo fazer:

```
Correção da tela de login

- Feito com que seja exibido um feedback de carregamento ao tocar no botão logar
- Correção da comunicação com a API
```

Logo no início, um título, descrevendo a principal alteração. Em seguinda, uma linha em branco e então outras alterações iniciando com "-".

## 8

Área de alterações preparadas (staged) para confirmar.

## 9

Área de alterações não preparadas (unstaged).

## 10

Área destinada a outros repositórios dentro do diretório analisado pelo vscode.

## 11

Botão para enviar todas as alterações da área para a área de stash. Stash é um espaço reservado para guardar alterações quando, por exemplo, se precisa trocar de branch sem fazer commit ou outros motivos.

## 12

Botão para descartar todas as alterações da área.

## 13

Botão para preparar todas as alterações, ou seja, enviar todas as alterações para a área de preparação.

## 14

Indicador de arquivo deletado.

## 15

Indicador de arquivo modificado.

## 16

Indicador de arquivo adicionado.

## 17

Indicador de alteração na linha. Ao tocar na marca é possível ver como estava antes e como ficou.

## 18

Indicador de linha adicionada. Ao tocar na marca é possível ver como estava antes e como ficou.

## 19

Indicador de linha excluída. Ao tocar na marca é possível ver como estava antes e como ficou.

## 20

Outras formas de visualização de informações do Git, como: lista de commits, alterações no arquivo selecionado, lista de branches no repositório, lista de remotes, lista de alterações em stash, lista de tags...

## 21

Aba do Controle do Código-Fonte.

## 22

Branch atual do repositório selecionado.

## 23

Botão para sincronizar alterações do repositório selecionado. Aqui também pode ser possível ver setas para baixo e para cima com um número em cada uma. A seta para cima com o número indica quantos commits novos existem a serem enviados para a remote, já a seta para baixo com o número indica quantos commits novos existem para serem trazidos da remote.
