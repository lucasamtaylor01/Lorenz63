# Estudo do Atrator de Lorenz 🌀

Este repositório explora o comportamento dinâmico do **Atrator de Lorenz**, um modelo de convecção atmosférica desenvolvido por Edward Norton Lorenz e apresentado em _Deterministic Nonperiodic Flow_ (1963).

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
3. **Sensibilidade**: Método dos Mínimos Quadrados
