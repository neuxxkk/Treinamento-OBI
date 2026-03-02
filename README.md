# 🏆 Treinamento OBI — Olimpíada Brasileira de Informática

Repositório de soluções e exercícios desenvolvidos durante o treinamento para a **OBI (Olimpíada Brasileira de Informática)**. As soluções estão organizadas por ano de edição e implementadas em **Python**.

---

## 📌 O que é a OBI?

A **Olimpíada Brasileira de Informática (OBI)** é uma competição nacional voltada para estudantes do ensino fundamental e médio, com o objetivo de estimular o interesse pela computação e pela resolução de problemas algorítmicos. Os participantes resolvem problemas de programação que envolvem lógica, estruturas de dados, algoritmos e matemática computacional.

Mais informações: [https://olimpiada.ic.unicamp.br/](https://olimpiada.ic.unicamp.br/)

---

## 📁 Estrutura do Repositório

```
Treinamento-OBI/
├── OBI-2019/
│   ├── c.py           # Problema da grade (WIP)
│   ├── chuva.py       # Problema da chuva
│   ├── idade.py       # Problema das idades
│   ├── soma.py        # Soma de subsequências (força bruta)
│   ├── somaFODA.py    # Soma de subsequências (abordagem alternativa)
│   └── test.py        # Testes e experimentos
├── OBI-2021/
│   ├── cifra.py       # Problema da cifra
│   ├── tempo.py       # Problema do tempo/registro de eventos
│   └── test.py        # Testes e experimentos
├── OBI-2023/
│   ├── contas.py      # Problema das contas
│   ├── estoque.py     # Problema do estoque
│   ├── exec.py        # Comparação de desempenho (timeit)
│   ├── leilao.py      # Problema do leilão
│   ├── toupeira.py    # Problema da toupeira (WIP)
│   └── test.py        # Testes e experimentos
└── README.md
```

---

## 🗂️ Problemas por Edição

### 📅 OBI 2019

| Arquivo        | Problema                        | Descrição                                                                                         |
|----------------|---------------------------------|---------------------------------------------------------------------------------------------------|
| `idade.py`     | Idades                          | Dado um valor `m` e duas idades, calcula a terceira e retorna a maior das três.                   |
| `soma.py`      | Soma de Subsequências           | Conta quantas subsequências contíguas de uma sequência somam exatamente `k` (força bruta O(n²)). |
| `somaFODA.py`  | Soma de Subsequências (Alt.)    | Abordagem alternativa para contagem de subsequências com soma igual a `k`.                        |
| `chuva.py`     | Chuva                           | Simulação de propagação em uma grade com regras de movimento baseadas em células vizinhas.        |
| `c.py`         | Grade (WIP)                     | Leitura de uma grade n×m; lógica de verificação de condições (em desenvolvimento).               |

---

### 📅 OBI 2021

| Arquivo     | Problema     | Descrição                                                                                                          |
|-------------|--------------|--------------------------------------------------------------------------------------------------------------------|
| `cifra.py`  | Cifra        | Implementa uma cifra de substituição: consoantes são substituídas por blocos de 3 letras baseados no alfabeto.    |
| `tempo.py`  | Tempo        | Gerencia registro de eventos (R = registrar, E = encerrar, T = avançar tempo) e imprime status final de cada item.|

---

### 📅 OBI 2023

| Arquivo       | Problema   | Descrição                                                                                                        |
|---------------|------------|------------------------------------------------------------------------------------------------------------------|
| `contas.py`   | Contas     | Dado um valor `v` e três contas, paga o máximo de contas possível em ordem crescente de valor.                  |
| `estoque.py`  | Estoque    | Gerencia pedidos em um estoque matricial; conta quantos pedidos foram atendidos com sucesso.                    |
| `leilao.py`   | Leilão     | Lê lances de um leilão e determina o vencedor com o maior lance.                                                |
| `toupeira.py` | Toupeira   | Problema em desenvolvimento.                                                                                    |
| `exec.py`     | Benchmark  | Compara o tempo de execução entre ordenação de listas e dicionários usando `timeit`.                            |

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Paradigma:** Programação imperativa / algoritmos e estruturas de dados
- **Ferramentas:** Python padrão (sem bibliotecas externas, exceto `timeit` em `exec.py`)

---

## ▶️ Como Executar

Certifique-se de ter o **Python 3** instalado em sua máquina.

```bash
# Clone o repositório
git clone https://github.com/neuxxkk/Treinamento-OBI.git
cd Treinamento-OBI

# Execute um arquivo específico (exemplo)
python3 OBI-2023/contas.py
```

A maioria dos programas lê dados via entrada padrão (`stdin`). Você pode fornecer a entrada diretamente no terminal ou redirecionar um arquivo de entrada:

```bash
# Exemplo com redirecionamento de arquivo
echo "100\n30\n40" | python3 OBI-2023/contas.py

# Ou usando um arquivo de entrada
python3 OBI-2023/contas.py < entrada.txt
```

---

## 👤 Autor

Desenvolvido por **[neuxxkk](https://github.com/neuxxkk)** como material de estudo e prática para a Olimpíada Brasileira de Informática.

---

## 📄 Licença

Este repositório é de uso pessoal e educacional. Sinta-se à vontade para explorar e se inspirar nas soluções.
