# Python Fluente Lab

Repositório de estudos e experimentos práticos inspirados em *Python Fluente*. O objetivo é reunir notebooks, exemplos, exercícios, desafios e pequenos projetos para explorar recursos idiomáticos da linguagem Python.

## Estrutura

```text
python-fluente-lab/
├── anotacoes/        # Anotações de estudo por capítulo ou tema
├── datasets/         # Dados usados nos exemplos e projetos
├── desafios/         # Desafios práticos
├── exemplo_livro/    # Implementações baseadas nos exemplos do livro
├── exercicios/       # Exercícios resolvidos ou em andamento
├── imagens/          # Imagens usadas na documentação e nos notebooks
├── notebooks/
│   └── capitulo_01.ipynb  # Experimentos com len() e o método especial __len__
├── projetos/         # Projetos maiores desenvolvidos durante o estudo
├── utils/            # Funções utilitárias reutilizáveis
├── hello.py          # Programa inicial que exibe uma saudação
└── requirements.txt  # Dependências do ambiente (ainda sem pacotes definidos)
```

As pastas de conteúdo, exceto `notebooks/`, estão preparadas para receber materiais à medida que os estudos avançarem.

## Conteúdo atual

- `hello.py` imprime `Olá, Python Fluente!`.
- `notebooks/capitulo_01.ipynb` demonstra o funcionamento de `len()` com listas e com classes que implementam `__len__`.

## Como usar

Requer Python 3.13 ou compatível.

```bash
python hello.py
```

Para abrir o notebook, instale o Jupyter no seu ambiente Python e execute:

```bash
jupyter notebook notebooks/capitulo_01.ipynb
```

Quando houver dependências externas, elas serão registradas em `requirements.txt` e poderão ser instaladas com:

```bash
pip install -r requirements.txt
```
