# Protocolo Neon

Jogo de Python **avançado**. Em Neo-São Paulo, 2087, você opera a VESPA, um drone de invasão, e o seu código é a arma. São 18 missões em 6 distritos:

- **Funções de primeira classe:** closures com `nonlocal`, decoradores com `functools.wraps`, decoradores com argumentos.
- **Modelo de dados:** sobrecarga de operadores, containers com `__getitem__`/`__contains__`/`__iter__`, gerenciadores de contexto.
- **Iteradores e geradores:** protocolo de iterador, pipelines preguiçosos e corrotinas com `send()`.
- **Metaprogramação:** descritores, `__init_subclass__` e proxies com `__getattr__`.
- **Texto:** expressões regulares, dataclasses, analisador descendente recursivo e um compilador de linguagem própria.
- **Algoritmos:** Dijkstra com `heapq`, programação dinâmica com bitmask e `lru_cache`, busca no espaço (posição, tempo).

Roda o Python 3.12 de verdade no navegador (Pyodide). Na primeira vez baixa cerca de 13 MB; depois funciona offline.

## Instalar no celular

- **Android (Chrome):** menu ⋮ → **Instalar app**.
- **iPhone (Safari):** **Compartilhar** → **Adicionar à Tela de Início**.

## Atualizar

Envie os arquivos novos e mude `neon-v1` para `neon-v2` no `sw.js`.
