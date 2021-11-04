# PTCC - Planejamento de Trabalho de Conclusão de Curso

Este irá contemplar o gerenciamento dos trabalhos dos Grupos formados para o TCC.
Iremos utilizar Metodologias Ágeis para o planejamento e para o desenolvimento do trabalho; para tal nada mais natutal que iniciarmos as tarefas de planejamento utilizando os ritos e artefatos do Scrum desde já!

## Requisitos

Para podermos trabalhar de forma mais efetiva, precisamos nos certificar que alguns requisitos estejam em conformidade para que não hajam impedimentos ao desenvolder das tarefas, mesmo que neste ponto ainda não hajam grupos completamente formados, para que possamos usar Metodologias Ágeis e desenvolver mesmo que individualmente, os requisitos devem ser preenchidos:

* Possuir conta [BitBucket](https://bitbucket.org), vamos usar esta conta para integrar ao Jira(software de gestão de projetos);

* Possuir noções de utilização de versionamento utilizando Git (criação de commits, controle de branches, atualização de código com pulls e pushes);

* Bom ânimo e empenho nas atividades individuais e em nome do time;

### Tutorial Primeira Entrega no Jira

#### Criar conta no GitHub

Criar conta no GitHub com email institucional através do convite recebido;

#### Obter o código base para iniciar a Tarefa

Clonar o repositório [Repositório da Tarefa](https://github.com/e104SysDev/tcc-ds); voce cloná-lo com o GitDesktop, GitKraken, pela sua IDE preferida ou por linha de comando executando este comando no interpretador de comados do Windows `git clone https://github.com/e104SysDev/tcc-ds.git`. 

#### Criar uma Branch (Ramificação) para a tarefa do Time

Voce deverá criar uma branch com o identificador de sua Tarefa no Jira, por exemplo TDS-100; a branch deverá ter o nome da tarefa para que o Jira possa identificar as alterações e o andamento das atividades relacionadas.

Para criar a branch voce deve utilizar o comando abaixo, onde `X` é o número de sua tarefa.

```shell
git checkout -b TDS-X
```

Agora voce tem uma versão só sua da tarefa original e pode fazer todas as inclusões e modificações necessárias sem modificar o conteúdo original.

#### Criar o documento formatado para o pré-projeto

1. No diretório de sua branch, crie e salve o documento pelo `Microsoft Word`
2. Insira as formatações conforme as normas `ABNT` e o modelo anexo na tarefa;
3. Voce pode compartilhar o arquivo pelo OneDrive, Google Drive, etc; mas lembre-se de ao fazer a entrega utilizar o Git.


#### Concluindo a entrega

Para concluir a entrega você deverá criar uma versão consolidada, ou seja criar um commit com todas as alterações realizadas e enviar estas alterações para o GitHub.

Siga os passos a seguir para enviar sua tarefa, lembre-se que o `X` é o número do seu Time e o `Y` é o número da sua tarefa:

1. Enviar os produtos gerados.

```shell
git add .
git commit -am "TDS-X - Entrega Time Y"
git push -u origin TDX-X
```

2. Alterar o status da Tarefa de `Pendente` para `Validação`

#### Parabéns, tarefa concluida

### Pull Request

A última etapa do processo é a junção de todas as tarefas na branch principal; mas esta etapa realizaremos presencialmente na próxima aula!



