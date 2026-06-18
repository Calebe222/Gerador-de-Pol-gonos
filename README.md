# Gerador de Polígonos

Aplicativo GUI em Python para gerar e visualizar permutações de polígonos regulares.

## Descrição

Este projeto usa `tkinter` para criar uma interface gráfica onde o usuário pode:
- inserir a quantidade de polígonos a gerar;
- escolher o número de lados de cada polígono;
- definir quantos polígonos são exibidos por página;
- navegar entre as páginas de polígonos;
- salvar as imagens geradas em PNG.

As figuras são desenhadas usando `matplotlib` e exibidas dentro da janela do Tkinter.

## Requisitos

- Python 3.10+ (ou compatível)
- bibliotecas:
  - `tkinter` (geralmente já incluída no Python)
  - `matplotlib`
  - `numpy`

## Instalação

1. Crie e ative um ambiente virtual (opcional, mas recomendado):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Instale as dependências:

```powershell
pip install matplotlib numpy
```

## Uso

1. Execute o programa:

```powershell
python main.py
```

2. Na janela do aplicativo:
- informe a quantidade de polígonos;
- informe o número de lados (mínimo 3);
- escolha quantos polígonos quer mostrar por página;
- clique em `Gerar`.

3. Use os botões `Voltar` e `Avançar` para navegar entre as páginas.
4. Para salvar as imagens, clique em `Salvar Imagens`.

## Observações

- O número máximo de polígonos é limitado pelo total de permutações possíveis para o número de lados informado.
- Alguns valores altos de lados podem afetar o desempenho, por isso o projeto define limite para entrada.

## Estrutura do projeto

- `main.py` - código principal do aplicativo.
- `.venv/` - ambiente virtual (não subir no GitHub se não for necessário).
