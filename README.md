<div align="center">

# 🏆 Treinamento OBI

*Soluções e exercícios para a Olimpíada Brasileira de Informática*

[![Language](https://img.shields.io/badge/Language-Python%203-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![OBI](https://img.shields.io/badge/Competição-OBI-00d4aa?style=flat-square)](https://olimpiada.ic.unicamp.br/)
[![Edições](https://img.shields.io/badge/Edições-2019%20·%202021%20·%202023-FF6B6B?style=flat-square)]()

</div>

---

Repositório de soluções desenvolvidas durante o treinamento para a **OBI (Olimpíada Brasileira de Informática)**, organizadas por edição e implementadas em **Python 3**.

> A OBI é uma competição nacional para estudantes do ensino fundamental e médio, com foco em lógica, estruturas de dados, algoritmos e matemática computacional. Mais informações em [olimpiada.ic.unicamp.br](https://olimpiada.ic.unicamp.br/).

---

## 📂 Estrutura do Repositório

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
└── OBI-2023/
    ├── contas.py      # Problema das contas
    ├── estoque.py     # Problema do estoque
    ├── exec.py        # Comparação de desempenho (timeit)
    ├── leilao.py      # Problema do leilão
    ├── toupeira.py    # Problema da toupeira (WIP)
    └── test.py        # Testes e experimentos
```

---

## 🗂️ Problemas por Edição

### 📅 OBI 2019

| Arquivo | Problema | Descrição |
|---------|----------|-----------|
| `idade.py` | Idades | Dado `m` e duas idades, calcula a terceira e retorna a maior das três |
| `soma.py` | Soma de Subsequências | Conta subsequências contíguas com soma igual a `k` — força bruta O(n²) |
| `somaFODA.py` | Soma de Subsequências (Alt.) | Abordagem alternativa para o mesmo problema |
| `chuva.py` | Chuva | Simulação de propagação em grade com regras de movimento por células vizinhas |
| `c.py` | Grade *(WIP)* | Leitura de grade n×m com verificação de condições — em desenvolvimento |

---

### 📅 OBI 2021

| Arquivo | Problema | Descrição |
|---------|----------|-----------|
| `cifra.py` | Cifra | Cifra de substituição: consoantes viram blocos de 3 letras baseados no alfabeto |
| `tempo.py` | Tempo | Gerencia eventos (`R` registrar, `E` encerrar, `T` avançar tempo) e imprime status final |

---

### 📅 OBI 2023

| Arquivo | Problema | Descrição |
|---------|----------|-----------|
| `contas.py` | Contas | Dado `v` e três contas, paga o máximo possível em ordem crescente de valor |
| `estoque.py` | Estoque | Gerencia pedidos em estoque matricial e conta quantos foram atendidos |
| `leilao.py` | Leilão | Lê lances e determina o vencedor com o maior lance |
| `toupeira.py` | Toupeira *(WIP)* | Em desenvolvimento |
| `exec.py` | Benchmark | Compara tempo de execução entre ordenação de listas e dicionários via `timeit` |

---

## 🚀 Como Executar

```bash
git clone https://github.com/neuxxkk/Treinamento-OBI.git
cd Treinamento-OBI
python3 OBI-2023/contas.py
```

A maioria dos programas lê via `stdin`. Você pode fornecer a entrada diretamente ou redirecionar um arquivo:

```bash
# Entrada direta
echo "100\n30\n40" | python3 OBI-2023/contas.py

# Via arquivo
python3 OBI-2023/contas.py < entrada.txt
```

> Nenhuma biblioteca externa é necessária — apenas Python 3 padrão (exceto `timeit` em `exec.py`, que já vem na stdlib).

---

<div align="center">
<sub>Desenvolvido por <a href="https://github.com/neuxxkk">neuxxkk</a> como material de estudo para a OBI · uso pessoal e educacional</sub>
</div>
