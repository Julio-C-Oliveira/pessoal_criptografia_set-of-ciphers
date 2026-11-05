# pessoal_criptografia_set-of-ciphers

Suíte de algoritmos de **criptografia clássica e cifragem simétrica**, desenvolvida em Python e espelhada em Kotlin.

---

## 🔐 Algoritmos Implementados

1. **Cifra de César Polialfabética Ponderada (`CesarCipher.py`):**
   - Variação estendida da Cifra de César onde o deslocamento não é fixo, mas determinado pelo valor numérico posicional de uma palavra secundária (`secondaryWord`).
   - Preserva rigorosamente máscaras de maiúsculas, minúsculas, números e pontuações (`Formatting.py`), operando translações módulo 26.
2. **Cifra de Substituição 3x4 (Teclado Numérico ITU-T - `Replacement3x4.py`):**
   - Mapeia caracteres para as teclas correspondentes dos teclados de aparelhos celulares clássicos (ex: A/B/C $\to$ 2, D/E/F $\to$ 3, ..., W/X/Y/Z $\to$ 9), viabilizando codificação leve e esteganografia.
3. **Cifra Matricial de Embaralhamento (`MatrixShurffleCipher.py`):**
   - Disposição dos caracteres em blocos de matrizes bidimensionais com permutação posicional de linhas e colunas.

---

## 🛠️ Tecnologias

- **Python 3.9+**
- **Kotlin 1.9+** (versão em `kotlin_version/`)

---

## 📦 Como Executar

```bash
python3 main.py
```

---

## 📄 Licença
Distribuído sob a licença MIT. Veja `LICENSE` para mais detalhes.
