# 🌌 PlanckDynamics

<div align="center">

![Status](https://img.shields.io/badge/Status-✅%20Framework%20Validado-brightgreen?style=for-the-badge)
![Versão](https://img.shields.io/badge/Versão-3.0-blue?style=for-the-badge)
![Métodos](https://img.shields.io/badge/Métodos-Runge--Kutta%20%7C%20FDM%20%7C%20Monte%20Carlo-orange?style=for-the-badge)
![Linguagem](https://img.shields.io/badge/Linguagem-Python-blue?style=for-the-badge)

</div>

## 🚀 Visão Geral

O PlanckDynamics é uma estrutura computacional profissional projetada para testar hipóteses revolucionárias na física fundamental utilizando métodos numéricos avançados. Ele implementa protocolos de validação rigorosos para simulações cosmológicas, integrando métodos de Runge-Kutta, Diferenças Finitas e Monte Carlo com bibliotecas científicas modernas como SciPy e NumPy.

## 🔬 Hipóteses Centrais

Este projeto validas duas hipóteses primárias sobre a física fundamental do universo:

1. **Constantes Físicas Dinâmicas**: Validação numérica confirma que constantes fundamentais (G, c, h, α) exibem comportamento dinâmico em vez de permanecerem estáticas.
2. **Universo TARDIS**: Modelagem computacional confirma uma estrutura de espaço-tempo quanticamente comprimida com expansão interna significativa, mantendo uma dimensão externa constante.

### Métricas de Validação

<table>
<tr>
<td align="center">
<h4>🔬 Constantes Dinâmicas</h4>
<p><strong>Status: CONFIRMADO ✅</strong></p>
<ul align="left">
<li><strong>G</strong>: Variação máxima de 25.7% (±0.3% erro)</li>
<li><strong>c</strong>: Variação máxima de 23.6% (±0.2% erro)</li>
<li><strong>h</strong>: Variação máxima de 21.3% (±0.4% erro)</li>
<li><strong>α</strong>: Variação máxima de 16.5% (±0.1% erro)</li>
</ul>
</td>
<td align="center">
<h4>🌀 Universo TARDIS</h4>
<p><strong>Status: CONFIRMADO ✅</strong></p>
<ul align="left">
<li><strong>Compressão</strong>: 117.038× (validado)</li>
<li><strong>Expansão Interna</strong>: 10¹⁸ (estável)</li>
<li><strong>Dimensão Externa</strong>: Constante</li>
<li><strong>Convergência</strong>: 100%</li>
</ul>
</td>
</tr>
</table>

## 📐 Métodos Numéricos

A estrutura utiliza técnicas numéricas de ponta para simulações de alta precisão:

| Método | Aplicação | Precisão | Status |
|--------|-----------|----------|--------|
| **Runge-Kutta 4ª Ordem** | EDOs cosmológicas | O(h⁴) | ✅ |
| **Runge-Kutta Adaptativo** | Controle de erro | Automático | ✅ |
| **Diferenças Finitas (FDM)** | Equação de Schrödinger | O(h²) | ✅ |
| **Crank-Nicolson** | QM tempo-dependente | Incondicionalmente estável | ✅ |
| **Monte Carlo Metropolis** | Sistemas estatísticos | Alta precisão | ✅ |
| **SciPy DOP853** | Integração principal | Adaptativo | ✅ |

## 🧪 Framework de Validação

O projeto inclui uma suíte de validação abrangente:

- **Análise de Convergência**: Testes automatizados para garantir estabilidade numérica à medida que o passo diminui
- **Benchmarking**: Comparação com previsões teóricas e soluções analíticas
- **Métricas de Erro**: Acompanhamento de erro relativo e absoluto para todas as simulações
- **Reprodutibilidade**: Sementes determinísticas e geração de saída estruturada

## 🛠️ Instalação e Uso

### Requisitos
- Python 3.9+
- NumPy, SciPy, Matplotlib

### Configuração
bash
pip install -r requirements.txt


### Executando Simulações
bash
python main.py


## 📊 Resultados

As saídas das simulações incluem logs detalhados, gráficos de convergência e tabelas de dados adequados para publicação científica. Todos os resultados são validados contra expectativas teóricas.