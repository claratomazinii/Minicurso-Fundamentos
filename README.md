# Minicurso-Fundamentos
Atividades realizadas no minicurso de fundamentos de análise de dados - LabRI

## AULA O1 (08/02/2024): Preparação do ambiente de trabalho

### Versionamento

- GITHUB e GITLAB: rede social para compatilhar código
- GIT: versionar o código
- [OhShitGit](https://ohshitgit.com/pt_br/swears/)

#### Versionando o código
  
  ```
  git add .
  ```

  ```
  git commit -m "inserir mensagem aqui"
  ```

#### Sincronizar o repositório local com o remoto

  ```
  git pull orign main
  ```

  ```
  git push orign main
  ```

### Comandos básicos linux

```
ls
cd
cd..
mkdir
history
cat
touch
rm -r caminho/do arquivos
cp caminho_origem caminho_destino
mv caminho_origem caminho_destino

```

### Editor de Código

- `VScode`
- Google Colab

## Ambiente Virtual

- Software utilizado para a gestão do ambiente: `conda`

```
conda env create -f environment.yml 
```

```
conda activate nome_ambiente
```

```
conda env update
```

## AULA O2 (08/02/2024): 
## FUNÇÕES NATIVAS

### `print()`
- Função responsável por nos mostrar os resultados.
- isso facilita para verificar se o que estamos fazendo está correto.
- Não executa nada de fato, apenas nos mostra (visualmente) os resultados.

### `type()`
- Função responsável por indicar o tipo da função (ex: string, lista, etc.)
- é interessante usar essa função dentro do print, pois vai nos mostrar certinho 

### `len()`
- Função responsável por indicar quantidade de caracteres
- mais usado em listas e strings
- lista é tudo que está entre [colchetes]

### `input()`
- Responsável por passar ao programa algum tipo de dado; é uma forma de interação com o código
- Então podemos considerar a entrada de informações
- O retorno/resposta vai depender do que você indicar 

### `dir()`
- Função responsável por apresentar todos os atributos e funções/métodos disponíveis para determinado tipo de dado ou variável
- Podemos dizer que são funções "pré-prontas" que podemos usar
- útil para explorar a estrutura de um objeto e descobrir quais operações podem ser realizadas com ele

## MÉTODOS DE STRING

### upper()
### title()
### strip()
### split()
### f string

## ESTRUTURA DE REPETIÇÃO (LOOP)

### For
- Responsável por percorrer um bloco de código indicado pelo usuário

### While
- Responsável por

## ESTRUTURA DO CÓDIGO
### `Def`
- O que define o início de uma função é o comando `def`
- É recomendado que o script contenha vários blocos de funções separados, sendo cada um responsável por realizar uma parte do processo que estamos construindo

### `return`
- comando que indica o valor que a função deve retornar quando chamada
- bastante confundido com o print, mas diferente desse, o return de fato executa algo e não apenas mostra o resultado
- o return apresenta um resultado da função que você criou
