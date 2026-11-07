# 28 exemplos de A-Frame

Seleção de 28 componentes do A-Frame Registry para experimentar no computador. Cada ficheiro HTML mostra um efeito e uma instrução curta.

## Abrir

1. Abre a pasta A-FRAME no VS Code.
2. Abre um Terminal e executa estes comandos.

```sh
cd /Users/beatrizfonsecaabrantes/Documents/A-FRAME
python3 -m http.server 8000 --bind 127.0.0.1
```

3. Abre [os exemplos](http://localhost:8000/registry/).
4. Escolhe um nome na lista. Para regressar, clica em **Voltar aos exemplos**.

Se o servidor já estiver ligado, abre diretamente o endereço do passo 3.

## Ficheiros

- `index.html` contém a lista dos 28 exemplos.
- `exemplos/` contém um HTML por componente.
- `lib/` contém as bibliotecas.
- `assets/` contém imagens, modelos e a fonte do texto.

A descrição de cada exemplo aparece no índice e no próprio HTML. Em cenas com navegação, arrasta o rato para olhar à volta e usa W, A, S e D para te deslocares.

Esta seleção cobre 28 das 42 entradas do catálogo. O enunciado original pede exemplos de todos os componentes.

## Publicar no GitHub

Depois de experimentar as cenas, executa no Terminal da pasta A-FRAME.

```sh
git add -- registry
git commit -m "Adicionar 28 exemplos de A-Frame"
git push origin main
```

As versões e os créditos estão em [FONTES.md](FONTES.md).
