---
layout: post
title: "Energía Electroestática"
date: 2016-09-28
excerpt: "Primera clase"
tags: [física]
comments: false
---

# Campo Electroestático

## Culombio

```
qe == e = 1.6 * 10^-19 C
```

- Dos polaridades.
- Carga neta constante.
- Naturaleza discreta o cuantizada.

| - | partícula | carga | masa |
|---|---|---|---|
| nucleo | neutrón | x |  |
| nucleo | protón | 1.6 * 10^-19 C |  |
| corteza | electrón | -1.6 * 10^-19 C | 9.11 * 10^-31 kg |

## Dipolo eléctrico

Dos cargas eléctricas de igual magnitud pero de signos opuestos.

### Vector bipolar

```
p_v = q * l_v

q_v > carga
l_v > distancia
```

Existen moléculas polares y apolares.

## Carga total, neta y libre

- __Total__: carga total que existe en un material.
- __Neta__: suma (con signo) de la carga total positiva y la total negativa que contiene dicho cuerpo: `q neta = q(+) + q(-)`. Un cuerpo es neutro cuando la carga neta es cero.
- __Libre__: tiene suficiente libertad para moverse por el interior del material. También se les llama portadores móviles de carga. Una partícula cargada se denomina carga ligada si no tiene libertad para moverse por el material.
    - _Conductores_: los electrones se mueven libremente de átomo a otro.
    - _Aislantes_: los electrones están ligados a los átomos.
    - _Semiconductores_: comportamiento intermedio, aunque mayormente aislante. Pueden cambiar de estado (conductor <-> aislante).

## Concentración de carga eléctrica en un material

```
# concentración de átomos de un material puro
n_atomos / m^3 = (rho_m / M_at) * N_avog

# número de avogadro (átomos por mol)
N_avog > 6.023 * 10^23 mol^-1

# concentración de electrones libres en un conductor
n = (valencia) (rho_m / M_at) * N_avog

# explicación
n = (electrones_libres / m^3) = (electrones_libres / átomo) * (moles / m^3) * (atomos / mol)
                                 valencia                      rho_m / M_at    N_avog
```

--------

> Letras griegas
> 
> - __alpha, beta, gamma, theta__ => ángulos (`rad`)
> - __omega__ => frecuencia angular (`rad / s == rad / s^-1`)
> - __nu__ => frecuencia (`Hz == s^-1`)
> - __rho__ => densidad de masa por volumen (`rho_m`), densidad de carga por volumen (`rho_q`) o resistividad (inversa de conductividad -> `1 / sigma`)
> - __sigma__ => densidad de masa por superficie (`sigma_m`), densidad de carga por superficie (`sigma_q`) o conductividad (inversa de resistividad -> `1 / rho`)
> - __lambda__ => longitud de onda

--------

## Ley de Coulomb

Describe la atracción o repulsión entre __cargas puntuales__.

```
# fuerza de partícula 1 sobre partícula 2
F_12v = K * ((q_1 * q_2) / r_12^2) * u_12v

# vector unitario de partícula 1 a partícula 2
u_12v = r_12v / r_12

# constante de coulomb
K > 8.99 * 10^9 N m^2 C^-2
```

### Principio de superposición

Si una carga q\_0 interacciona con varias cargas simultáneamente, la fuerza resultante que actúa sobre q\_0

--------

> Magnitudes
> 
> - `u_1v * u_2v = cos(angle(u_1v, u_2v))`
> - `F = m * a` - `1N = 1 kg * m / s^2`
> - `Work o Energy => 1J = 1 kg * m^2 / s^2`
> - `Work = Fuerza * distancia`
> - `P (potencia) = Work / tiempo` - `1W = 1 kg * m^2 / s^3 = N * m / s = J / s`

--------

> `Epsilon_0 = 8.85 * 10^-12 Faradios / metros`

--------

## Campo electroestático

El campo electroestático creado por una carga Q en un punto P es la fuerza que ejercería la carga Q sobre una carga de 1C situada en ese punto.

```
E_v = (1 / 4 * pi * epsilon_0) * (Q / r^2) * u_QPv

r > distancia entre la carga Q y el punto P
u_QPv > vector unitario que apunta desde la carga hasta el punto P
```
