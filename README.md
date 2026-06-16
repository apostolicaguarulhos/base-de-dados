# Sisteminha - Base de Dados Missão Guarulhos

Modelo visual alinhado à IDV usada no sistema de prestação de contas:
- Montserrat
- azul escuro institucional
- dourado
- cards de dashboard
- layout limpo de sistema
- logo Shalom como favicon e marca

## Onde mexer

### 1. Formulário Tally

No arquivo `index.html`, procure:

```html
data-tally-src="https://tally.so/embed/SEU_CODIGO_AQUI...
```

Substitua o iframe inteiro pelo iframe real do Tally.

No Tally:
`Share > Embed > Standard`

### 2. Logo

A logo já está em:

```txt
assets/logo.png
```

Também foi usada como favicon:

```txt
assets/favicon.png
```

### 3. Textos

Os textos principais ficam no arquivo:

```txt
index.html
```

Procure por:
- `Cadastro de Proximidade Missionária`
- `Base de dados - Missão Guarulhos`
- `Comunidade Católica Shalom`

### 4. Cores

As cores ficam no começo do arquivo:

```txt
style.css
```

Procure por:

```css
:root {
  --navy-950
  --navy-900
  --gold-500
}
```

## Publicação

Suba os arquivos para o GitHub Pages com `index.html` na raiz do repositório.
