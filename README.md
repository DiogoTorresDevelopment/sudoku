# 🧩 Sudoku Game - Projeto em Java

## 📜 **Descrição do Projeto**

Este projeto consiste em um jogo de **Sudoku** desenvolvido em **Java**, jogado via terminal. O jogo permite ao usuário interagir com o tabuleiro, inserindo e removendo números, validando jogadas e acompanhando o status do jogo.

O projeto aborda conceitos fundamentais de programação orientada a objetos (POO) e boas práticas como:

- Modularização do código
- Tratamento de exceções
- Uso de collections do Java (`List`, `Map`, `Stream`)
- Validação de dados de entrada
- Interface interativa via terminal

---

## 🎯 **Funcionalidades**

- ✅ Iniciar um novo jogo com configurações pré-definidas
- 🔢 Inserir e remover números do tabuleiro
- 🔍 Visualizar o estado atual do jogo
- 🛡️ Verificar se o tabuleiro contém erros
- 🧹 Resetar o jogo para o estado inicial
- 🏆 Validar a conclusão correta do Sudoku
- 🚫 Impedir alterações em células fixas (pré-definidas)

---

## 🏗️ **Tecnologias Utilizadas**

- ☕ **Java 17+**
- 💡 **Paradigma Orientado a Objetos (POO)**
- 🧪 **JUnit** *(opcional para testes)*
- 📜 **Streams e Lambdas (Java 8+)**
- 🔄 **Collections Framework**

---

## 🚀 **Como Executar o Projeto**

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/DiogoTorresDevelopment/sudoku
   cd sudoku
   ```

2. **Compile o projeto:**
   ```bash
   javac Main.java
   ```

3. **Execute o projeto com os argumentos de configuração:**
   ```bash
   java Main "0,0;4,false" "1,0;7,false" "2,0;9,true" "3,0;5,false" "4,0;8,true" \
   "5,0;6,true" "6,0;2,true" "7,0;3,false" "8,0;1,false"
   ```

> 🔗 **Obs.:** Os argumentos representam a configuração inicial do tabuleiro no formato:
> ```
> linha,coluna;valor,fixed
> ```
> - `linha,coluna`: posição da célula
> - `valor`: número inserido na célula
> - `fixed`: `true` se o valor é fixo (não pode ser alterado), `false` caso contrário

---

## 🎮 **Menu de Opções**

Ao executar o jogo, você verá o seguinte menu:

```
Selecione uma das opções a seguir:
1 - Iniciar um novo Jogo
2 - Colocar um novo número
3 - Remover um número
4 - Visualizar jogo atual
5 - Verificar status do jogo
6 - Limpar jogo
7 - Finalizar jogo
8 - Sair
```

---

## 🏆 **Objetivo do Jogo**
Complete o tabuleiro 9x9 sem repetir números nas linhas, colunas e subgrids 3x3. O jogo validará automaticamente as jogadas e informará se há erros ou se o Sudoku foi resolvido corretamente.

---

## 💡 **Possíveis Melhorias Futuras**
- 🌐 Interface gráfica usando **JavaFX**
- 💾 Salvamento e carregamento de partidas
- 🎛️ Diferentes níveis de dificuldade
- 🧠 Resolução automática utilizando **backtracking**
- 🌟 Validação em tempo real das jogadas

---

## 📝 **Licença**
Este projeto é licenciado sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.

