# Estudo do Atrator de Lorenz 🌀

Edward Norton Lorenz foi um pioneiro na meteorologia, famoso por desenvolver o modelo de convecção atmosférica conhecido como **Atrator de Lorenz**, introduzido no artigo _Deterministic Nonperiodic Flow_ (1963).

## Modelo de Lorenz 📐

O modelo consiste em três equações diferenciais ordinárias:

```math
dx/dt = σ(y-x)
```

```math
dy/dt = x(ρ - z) - y
```

```math
dz/dt = xy - βz
```

Estas equações descrevem comportamentos caóticos e são fundamentais para nosso estudo.

## Objetivos 🎯

1. **Simulações Numéricas**: Utilizaremos o método de Runge-Kutta para resolver as equações e splines cúbicas para representação gráfica.

2. **Análise de Sensibilidade**: Aplicaremos o Método dos Mínimos Quadrados para estudar a sensibilidade do modelo.

## Metodologia 🛠️

1. **Resolução das Equações**: Método de Runge-Kutta.
2. **Visualização**: Splines cúbicas.
3. **Sensibilidade**: Método dos Mínimos Quadrados.

Este projeto aplica técnicas matemáticas e computacionais aprendidas em sala para explorar o Atrator de Lorenz.

## Nota de Responsabilidade 📜

Este projeto foi desenvolvido com base em técnicas e metodologias estudadas ao longo do curso. No entanto, o uso deste material é de responsabilidade do usuário. Não me responsabilizo por qualquer caso de plágio ou uso indevido deste conteúdo. Recomendo que o trabalho seja utilizado como referência e que o código seja adaptado às suas necessidades específicas.
