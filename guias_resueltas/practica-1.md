Práctica 1
==========

Funciones iniciales
-------------------
* n(x) = 0
* s(x) = x+1
* uⁿᵢ(x₁,⋯,xₙ) = xᵢ ∀1≤i≤n

Composición
-----------
Sean _f_: ℕᵏ→ℕ y _g₁,⋯,gₖ_: ℕⁿ→ℕ. Sea _h_: ℕⁿ→ℕ

_h_(x₁,⋯,xₙ) = _f_(_g_(x₁,⋯,xₙ), ⋯, _gₖ_(x₁, ⋯, xₙ))

_h_ es obtenida a partir de _f_ y _g_ por composición.

### Clase Cerrada por Composición
Una clase 𝒞 es cerrada por composición, si ∀_f,g₁,⋯,gₖ_ ∈ 𝒞, y _h_ obtenida por composición de ellas, ⟹ _h_ ∈ 𝒞.

Ejercicio 1
-----------

Sea 𝒞 una clase cerrada por composición que contiene las funciones iniciales. Ver que están en 𝒞:

1. uno: ℕ→ℕ, uno(x) = 1.
    
    uno(x) = s(n(x)) = s(0) = 1
2. id: ℕ→ℕ, id(x) = x.
    
    id(x) = u¹₁(x)
3. s₁: ℕ²→ℕ, s₁(x,y) = x+1.
    
    s₁(x,y) = s(u²₁(x,y)) = s(x) = x+1
4. f~: ℕ²→ℕ, f~(x,y) = f(y,x) sabiendo que f: ℕ²→ℕ ∈ 𝒞.
    
    f~(x,y) = f(u²₂(x,y), u²₁(x,y)) = f(y,x)
5. fₓₖ: ℕᵏ→ℕ, fₓₖ(x₁,⋯,xₖ) = f(x₁) sabiendo que f: ℕ→ℕ ∈ 𝒞.
    
    fₓₖ(x₁,⋯,xₖ) = f(uᵏ₁(x₁,⋯,xₖ)) = f(x₁)
6. f/ₖ: ℕ→ℕ, f/ₖ(x) = f(x,x,⋯,x) sabiendo que f: Nᵏ→ℕ ∈ 𝒞.
    
    f/ₖ(x) = f(u¹₁(x),u¹₁(x),⋯,u¹₁(x))
7. p(x): ℕ→ℕ, p(x) = x ∸ 1.
    
    No se puede. **Demostración en otro ejercicio**.