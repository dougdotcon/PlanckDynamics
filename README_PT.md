# PlanckDynamics: O Framework do Universo Reativo

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18090702.svg)](https://doi.org/10.5281/zenodo.18090702)
[![Status: Production](https://img.shields.io/badge/Status-Validated-green.svg)]()
[![Physics: Entropic](https://img.shields.io/badge/Physics-Entropic%20Gravity-purple.svg)]()

## Resumo Executivo

O projeto **PlanckDynamics** (v1.0.0-reactive) representa uma mudança de paradigma na modelagem cosmológica. Ao congelar a constante de acoplamento entrópico ($\alpha = 0,47$) e o fator de compressão métrica ($\Gamma = 117,038$), verificamos computacionalmente um universo onde o "Setor Escuro" (Matéria Escura e Energia Escura) não é composto por partículas invisíveis, mas é uma resposta termodinâmica emergente do próprio vácuo.

Este framework resolve com sucesso as três grandes tensões da cosmologia moderna:
1.  **A Tensão de Hubble:** Reconciliada via história de expansão reativa.
2.  **Os Picos Acústicos do CMB:** O 3º pico é regenerado por poços de potencial entrópico.
3.  **Informação de Buraco Negro:** A evaporação unitária é preservada por uma área de Planck reativa.

## Framework Teórico: Os Parâmetros Congelados

O sistema opera com duas constantes fundamentais derivadas de inferência Bayesiana e testes de estabilidade termodinâmica (Congelados em `config/constants.json`):

| Parâmetro | Símbolo | Valor | Significado Físico |
|-----------|:------:|:-----:|--------------------|
| **Acoplamento Entrópico** | $\alpha$ | **0,470** | Força do acoplamento entre o Horizonte de Hubble e a dinâmica do bulk local. |
| **Compressão Métrica** | $\Gamma$ | **117,038** | O fator TARDIS; razão de densidade de informação entre os referenciais conforme e físico. |

## Fase 1: Reconciliação da Expansão (A Solução H0)

Modelos bariônicos padrão falham em explicar a expansão acelerada do universo sem Energia Escura ad-hoc. Introduzimos um termo de **Matéria Escura Reativa** $\Omega_{app}(z) \propto \sqrt{H(z)}$, postulando que a massa aparente escala com a tensão do horizonte cósmico.

Nossa análise MCMC (Markov Chain Monte Carlo) confirma que $\alpha = 0,47$ fornece um ajuste estatisticamente superior aos Cronômetros Cósmicos e Supernovas Tipo Ia, alinhando a constante de Hubble local ($H_0 \approx 67,4$ km/s/Mpc) com as observações do satélite Planck.

![Distribuição Posterior de Alpha](docs/images/posterior_corner.png)
*Fig 1. Distribuição posterior da constante de acoplamento alpha, mostrando forte convergência.*

![Comparação do Ajuste Hubble](docs/images/hubble_fit_comparison.png)
*Fig 2. O Modelo Reativo (Vermelho) preenche a lacuna entre bárions puros e os dados observacionais, eliminando a necessidade de Matéria Escura Fria.*

## Fase 2: Fundo Cósmico de Micro-ondas (O 3º Pico)

A falha histórica das teorias de Gravidade Modificada tem sido a incapacidade de reproduzir o 3º Pico Acústico no Espectro de Potência do CMB, o que implica a existência de poços de potencial gravitacional profundos antes da recombinação.

Nosso Kernel de Flutuação Linear (`experimental/cmb_engine.py`) demonstra que a Força Entrópica atua como um poço de potencial persistente ($\Phi_{eff}$), forçando a compressão do fluido Fóton-Bárion. Este potencial reativo regenera com sucesso a amplitude do 3º pico sem necessitar de WIMPs (Weakly Interacting Massive Particles).

![Espectro de Potência CMB](docs/images/cmb_power_spectrum.png)
*Fig 3. Recuperação do 3º Pico Acústico. O modelo Reativo (Vermelho) corresponde à topologia multipolar dos dados do Planck 2018, enquanto o modelo de bárions puros (Verde) suprime o pico.*

## Fase 3: Termodinâmica do Horizonte Reativo

Sob a compressão métrica de $\Gamma \approx 117$, uma área de Planck estática violaria o Limite de Bekenstein (Limite de Retenção de Informação). Postulamos uma **Área de Planck Reativa** ($l_p^2(eff) \propto \Gamma$) para preservar a unitariedade.

A simulação revela um universo auto-limpante:
- **Aumento de Temperatura:** Buracos negros são significativamente mais quentes ($T_{reac} = \Gamma T_{std}$).
- **Redução de Entropia:** A densidade de informação é diluída ($S_{reac} = S_{std} / \Gamma$).
- **Evaporação Acelerada:** O tempo de vida é reduzido por um fator de $\Gamma^4 \approx 10^8$.

![Termodinâmica de Buraco Negro](docs/images/black_hole_thermo.png)
*Fig 4. Perfil termodinâmico mostrando o aumento de temperatura e redução de entropia, garantindo a validade do Limite de Bekenstein.*

## Direções Futuras: A Hipótese do Remanescente

Com a Base de Código agora em produção, a pesquisa futura deve focar nos pontos finais da evaporação:

1.  **O Remanescente de Informação:** A evaporação acelerada deixa para trás um condensado estável na escala de Planck?
2.  **Espectroscopia de Ondas Gravitacionais:** Calcular as assinaturas de "Eco" da métrica TARDIS em fusões binárias de buracos negros.

## Autor e Citação

**DOUGLAS H. M. FULBER**  
Engenheiro de Software Sênior | Pesquisador em Física Computacional  
CTO @asimovtechsystems | Arquitetando Gêmeos Digitais Matemáticos  
Pesquisador Independente | Code-First Physics & Gravidade Entrópica

**Trabalho Mais Recente:**  
*The Reactive Universe: A Computational Solution to the Dark Sector*  
DOI: [10.5281/zenodo.18090702](https://doi.org/10.5281/zenodo.18090702)

**Perfis:**  
[GitHub](https://github.com/dougdotcon) | [LinkedIn](https://linkedin.com/in/douglasfulber) | [ORCID](https://orcid.org)