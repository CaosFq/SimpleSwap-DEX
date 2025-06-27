# SimpleSwap-DEX
A simplified Decentralized Exchange (DEX) for ERC-20 token swaps on Sepolia testnet.
# 🚀 SimpleSwap - Trabajo Final Módulo 3

## 🎯 Objetivo
Crear un contrato inteligente llamado **SimpleSwap** que permita:

- ➕ Agregar liquidez  
- ➖ Remover liquidez  
- 🔄 Intercambiar tokens  
- 💰 Obtener precios  
- 📊 Calcular cantidades a recibir  

Replicando funcionalidades básicas de Uniswap sin depender de su protocolo.

---

## 📢 Requerimientos

### 1️⃣ Agregar Liquidez (`addLiquidity`)
- Permite a los usuarios aportar tokens a un pool ERC-20.
- Emite tokens de liquidez (LP) al usuario.
- Incluye protección contra slippage.
- 📥 Transfiere tokens del usuario al contrato.
- 🔢 Calcula la liquidez emitida según reservas.

---

### 2️⃣ Remover Liquidez (`removeLiquidity`)
- Permite retirar tokens aportados quemando LP tokens.
- Devuelve cantidades proporcionales de los tokens del pool.
- Incluye protección contra slippage.

---

### 3️⃣ Intercambiar Tokens (`swapExactTokensForTokens`)
- Permite intercambiar una cantidad exacta de tokens por otro.
- Utiliza fórmula matemática para mantener la liquidez.
- Aplica comisión del 0.3%.
- Protege contra slippage.

---

### 4️⃣ Obtener Precio (`getPrice`)
- Devuelve el precio de un token en términos del otro.
- Basado en reservas actuales del pool.

---

### 5️⃣ Calcular Cantidad a Recibir (`getAmountOut`)
- Calcula la cantidad de tokens que se recibirán en un swap.
- Incluye comisión del 0.3%.

---

## ✅ Entregables

- Contrato inteligente `SimpleSwap.sol` con las funciones descritas.
- Código comentado que explica la lógica.
- Repositorio GitHub con el archivo `.sol` y este `README.md`.

---

## 📌 Nota

Este contrato está pensado para un solo par de tokens ERC-20 y replica las funcionalidades básicas de un AMM (Automated Market Maker) como Uniswap V2.

---

## 🛠️ Tecnologías

- Solidity 0.8.x  
- OpenZeppelin Contracts (IERC20, SafeERC20)  

---

## 🎓 Curso

Este proyecto forma parte del curso **Ethereum Developer Pack** impartido por **Talento Tech CABA**.

---

¡Gracias por revisar! 🙌

---

> **Autor:** Romero Hugo Andrés  
> **Fecha:** 2025  
> **Curso:** Módulo 3 - Blockchain y Smart Contracts - Ethereum Developer Pack - Talento Tech CABA
