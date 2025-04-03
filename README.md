# Modelagem Trajetória de Voo

Este projeto implementa a modelagem alternativa de um foguete utilizando Python. A modelagem é dividida em três fases: propulsada, balística e sustentada. A aplicação utiliza as bibliotecas `sympy`, `scipy`, `numpy` e `matplotlib` para a resolução das equações diferenciais e visualização dos resultados.

## Funcionalidades

### Fase Propulsada

- **Modelagem da Fase Propulsada**: Implementa a modelagem da fase propulsada do foguete, considerando a variação da massa e o empuxo.
- **Equações Diferenciais**: Resolução das equações diferenciais utilizando o método `odeint` da biblioteca `scipy`.
- **Visualização**: Geração de gráficos para a altura e velocidade durante a fase propulsada.

### Fase Balística

- **Modelagem da Fase Balística**: Implementa a modelagem da fase balística do foguete, considerando a massa constante e a ausência de empuxo.
- **Equações Diferenciais**: Resolução das equações diferenciais utilizando o método `odeint` da biblioteca `scipy`.
- **Visualização**: Geração de gráficos para a altura e velocidade durante a fase balística.

### Fase Sustentada

- **Modelagem da Fase Sustentada**: Implementa a modelagem da fase sustentada do foguete, considerando o coeficiente de arrasto e a área de referência do paraquedas.
- **Equações Diferenciais**: Resolução das equações diferenciais utilizando o método `odeint` da biblioteca `scipy`.
- **Visualização**: Geração de gráficos para a altura e velocidade durante a fase sustentada.

### Trajetória Completa

- **Juntando Todas as Fases**: Combina as três fases (propulsada, balística e sustentada) para obter a trajetória completa do foguete.
- **Visualização**: Geração de gráficos para a trajetória completa do voo do foguete.

## Estrutura do Código

### Fase Propulsada

- **Símbolos**: Definição dos símbolos e variáveis utilizadas na modelagem.
- **Equações**: Implementação das equações diferenciais para a fase propulsada.
- **Resolução**: Resolução das equações utilizando `odeint`.
- **Visualização**: Geração de gráficos para a altura e velocidade.

### Fase Balística

- **Símbolos**: Definição dos símbolos e variáveis utilizadas na modelagem.
- **Equações**: Implementação das equações diferenciais para a fase balística.
- **Resolução**: Resolução das equações utilizando `odeint`.
- **Visualização**: Geração de gráficos para a altura e velocidade.

### Fase Sustentada

- **Símbolos**: Definição dos símbolos e variáveis utilizadas na modelagem.
- **Equações**: Implementação das equações diferenciais para a fase sustentada.
- **Resolução**: Resolução das equações utilizando `odeint`.
- **Visualização**: Geração de gráficos para a altura e velocidade.

### Trajetória Completa

- **Combinação das Fases**: Combinação das três fases para obter a trajetória completa.
- **Visualização**: Geração de gráficos para a trajetória completa do voo.

## Requisitos

- Python 3.7+
- Bibliotecas:
  - `sympy`
  - `scipy`
  - `numpy`
  - `matplotlib`
