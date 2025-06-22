# A/B Testing: Music Impact on Road Safety Video Effectiveness

## Project Description
This repository contains a project developed for the **Business Statistics: Method and Application** course.  
The project focuses on analyzing the impact of different **background music types** (Dark & Ominous vs Happy & Bright) on viewers' perception of **road safety videos** effectiveness.  
It includes both **Frequentist** and **Bayesian approaches** for comprehensive statistical analysis and comparison of methodologies.

## Objectives
- Determine which **music type** (Dark & Ominous or Happy & Bright) should accompany road safety videos
- Investigate whether **background music** significantly affects respondents' perception of video effectiveness
- Evaluate the **optimal duration** for A/B testing and assess whether a two-year testing period was excessive
- Compare **Frequentist vs Bayesian** statistical approaches for A/B testing scenarios

## Methodology
### Frequentist Approach
- **Hypothesis Testing** with null hypothesis: Music does not affect respondent perception
- **Two-proportion Z-test** for comparing Dark vs Happy music effectiveness
- Analysis of both **Road Safety** and **Railway Safety** videos
- Statistical significance evaluation using critical values (α = 0.05)

### Bayesian Approach
- **Prior distribution** definition using Beta distributions
- **Posterior distribution** calculation and evolution tracking
- **Credible intervals** computation for both music types
- **Stopping criteria** implementation with adaptive probability thresholds
- Probability assessment of one music type winning over the other

## Key Findings
### Frequentist Results
- **Road Safety Video**: Test statistic = 1.823 (< Critical value 1.96)
- **Railway Safety Video**: Test statistic = 0.979 (< Critical value 1.96)
- **Conclusion**: No statistically significant difference between music types

### Bayesian Results
- **Credible Interval for Dark Music**: (0.3561, 0.4251)
- **Credible Interval for Happy Music**: (0.3127, 0.3800)
- **Probability of Dark > Happy**: 96.42%
- **Conclusion**: Significant evidence that Dark music has stronger impact on accident perception

## Data Analysis
The project analyzes **synthetic experimental data** simulating A/B testing scenarios, including:
- **Respondent perceptions** of accident likelihood in safety videos
- **Music type assignments** (Dark & Ominous vs Happy & Bright)
- **Video categories** (Road Safety and Railway Safety)
- **Sequential data collection** over extended testing periods

## Team Members
- **Botticelli Tommaso**
- **Cesari Jacopo**  
- **Soncini Samuel**
- **Zecchini Giovanni**

---

# A/B Testing: Impatto della Musica sull'Efficacia dei Video di Sicurezza Stradale

## Descrizione del Progetto
Questo repository contiene un progetto sviluppato per il corso di **Business Statistics: Method and Application**.  
Il progetto si concentra sull'analisi dell'impatto di diversi **tipi di musica di sottofondo** (Cupa e Minacciosa vs Allegra e Brillante) sulla percezione dell'efficacia dei **video di sicurezza stradale** da parte degli spettatori.  
Include approcci **Frequentisti** e **Bayesiani** per un'analisi statistica completa e il confronto delle metodologie.

## Obiettivi
- Determinare quale **tipo di musica** (Cupa e Minacciosa o Allegra e Brillante) dovrebbe accompagnare i video di sicurezza stradale
- Investigare se la **musica di sottofondo** influisce significativamente sulla percezione dell'efficacia del video
- Valutare la **durata ottimale** per i test A/B e verificare se un periodo di test di due anni sia stato eccessivo
- Confrontare gli approcci statistici **Frequentista vs Bayesiano** per scenari di A/B testing

## Metodologia
### Approccio Frequentista
- **Test delle Ipotesi** con ipotesi nulla: La musica non influisce sulla percezione del rispondente
- **Test Z per due proporzioni** per confrontare l'efficacia della musica Cupa vs Allegra
- Analisi di video di **Sicurezza Stradale** e **Sicurezza Ferroviaria**
- Valutazione della significatività statistica usando valori critici (α = 0.05)

### Approccio Bayesiano
- Definizione delle **distribuzioni a priori** usando distribuzioni Beta
- Calcolo delle **distribuzioni a posteriori** e monitoraggio della loro evoluzione
- Calcolo degli **intervalli di credibilità** per entrambi i tipi di musica
- Implementazione di **criteri di arresto** con soglie di probabilità adattive
- Valutazione della probabilità che un tipo di musica vinca sull'altro

## Risultati Principali
### Risultati Frequentisti
- **Video Sicurezza Stradale**: Statistica test = 1.823 (< Valore critico 1.96)
- **Video Sicurezza Ferroviaria**: Statistica test = 0.979 (< Valore critico 1.96)
- **Conclusione**: Nessuna differenza statisticamente significativa tra i tipi di musica

### Risultati Bayesiani
- **Intervallo di Credibilità per Musica Cupa**: (0.3561, 0.4251)
- **Intervallo di Credibilità per Musica Allegra**: (0.3127, 0.3800)
- **Probabilità che Cupa > Allegra**: 96.42%
- **Conclusione**: Evidenza significativa che la musica cupa ha un impatto maggiore sulla percezione degli incidenti

## Analisi dei Dati
Il progetto analizza **dati sperimentali sintetici** che simulano scenari di A/B testing, inclusi:
- **Percezioni dei rispondenti** sulla probabilità di incidenti nei video di sicurezza
- **Assegnazioni dei tipi di musica** (Cupa e Minacciosa vs Allegra e Brillante)
- **Categorie di video** (Sicurezza Stradale e Sicurezza Ferroviaria)
- **Raccolta dati sequenziale** su periodi di test estesi

## Membri del Team
- **Botticelli Tommaso**
- **Cesari Jacopo**  
- **Soncini Samuel**
- **Zecchini Giovanni**
