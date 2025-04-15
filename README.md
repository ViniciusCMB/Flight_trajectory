# Modelagem Trajetória de Voo

Este projeto implementa a modelagem da trajetória de voo de um foguete utilizando Python. A modelagem é dividida em três fases: propulsada, balística e sustentada. A aplicação utiliza as bibliotecas `sympy`, `scipy`, `numpy` e `matplotlib` para a resolução das equações diferenciais e visualização dos resultados.

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
<<<<<<< HEAD

## Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/SeuUsuario/ModelagemAlternativa.git
cd ModelagemAlternativa
pip install -r requirements.txt
```

## Uso

1. Execute o notebook `ModelagemAlternativa.ipynb` para iniciar a modelagem do foguete.
2. Siga as instruções no notebook para visualizar os gráficos e resultados das diferentes fases do voo.

## Estrutura do Projeto

- `ModelagemAlternativa.ipynb`: Notebook contendo a modelagem completa do foguete.
- `README.md`: Documentação do projeto.

## Contribuição

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.
=======
>>>>>>> 6f5e72f12f40c60af26591518b7e2b88cbe60547
