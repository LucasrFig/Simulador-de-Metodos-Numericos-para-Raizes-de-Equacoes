# Simulador de Métodos Numéricos para Raízes de Equações

Este projeto consiste em uma aplicação desenvolvida em Python para resolver equações algébricas e transcendentes por meio de quatro métodos numéricos clássicos: **Bissecção**, **Falsa Posição**, **Newton-Raphson** e **Secante**. 

O programa conta com uma interface gráfica interativa que permite ao usuário inserir funções matemáticas, ajustar parâmetros de execução, visualizar o comportamento da função e comparar o desempenho dos algoritmos em termos de iterações, tempo de execução e resíduo final.
---

## 👤 Integrantes:
* Andrei Luiz da Silva Rodrigues
* Lucas Ricardo de Lima Figueiredo
* Luis Fellype Magalhães Cruz

---

## 🛠️ Tecnologias e Dependências

 O projeto utiliza Python 3 e as seguintes bibliotecas:

* **Tkinter**: Interface gráfica do usuário.
* **SymPy**: Interpretação de expressões matemáticas e cálculo de derivadas.
* **NumPy**: Construção de vetores e geração dos pontos da curva.
* **Matplotlib**: Plotagem dos gráficos das funções e das comparações entre os métodos.

---

## 🚀 Como Executar o Programa

### 1. Pré-requisitos
Certifique-se de ter o **Python 3** instalado em sua máquina.

### 2. Instalação das Bibliotecas
Abra o terminal e instale as dependências executando:

```bash
pip install sympy numpy matplotlib
```

> **Nota:** O `tkinter` costuma vir pré-instalado com o Python no Windows. Em sistemas Linux, se necessário, ele pode ser instalado via gerenciador de pacotes (ex: `sudo apt-get install python3-tk`).

### 3. Estrutura dos Arquivos
Mantenha os dois arquivos do código na mesma pasta:
* `interface.py` (código da interface gráfica)
* `metodos.py` (implementação dos métodos numéricos)

### 4. Executando a Aplicação
No terminal, dentro do diretório dos arquivos, execute:

```bash
python interface.py
```

---

## 💡 Como Usar

1. Insira a função **f(x)** na caixa de texto utilizando a sintaxe matemática do Python/SymPy.
   * Exemplo 1: `90*exp(-0.15*x) - 30`
   * Exemplo 2: `1.2 - 5*exp(-x)`
2. Configure os parâmetros desejados:
   * Intervalo **[a, b]** (para Bissecção e Falsa Posição).
   * Chutes/Estimativas iniciais **x_0** e **x_1** (para Newton-Raphson e Secante).
   * Tolerância e limite máximo de iterações.
3. Clique em **"Executar análise"**.
4. Use os botões de navegação para alternar entre o gráfico da função com as raízes encontradas e os gráficos comparativos (Iterações, Tempo e Resíduo).
