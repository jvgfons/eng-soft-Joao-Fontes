# Semana 03 - O Labirinto de Boehm e Diagnóstico CMMI

## Parte 1: O Labirinto de Boehm

### Por que a Análise de Riscos teria evitado a queda dos drones?
Segundo Sommerville (Capítulo 2), o Modelo Espiral é caracterizado pela análise de riscos em cada volta da espiral.  
Se a Chaos-IT tivesse aplicado esse modelo, os riscos técnicos (como falhas de hardware, integração de software e segurança dos drones) teriam sido identificados e tratados antes da implementação final.  
A ausência desse processo levou ao fracasso do projeto, pois não houve antecipação dos problemas críticos.

### Ciclo da Espiral para o Projeto de IA Subaquática
Um ciclo da espiral aplicado ao projeto de IA subaquática poderia ser descrito assim:

1. **Definição de Objetivos (Quadrante 1)**  
   - Estabelecer requisitos iniciais: controle de drones subaquáticos, comunicação em ambientes hostis, segurança dos dados.  

2. **Análise de Riscos (Quadrante 2)**  
   - Avaliar riscos técnicos: falhas de sensores em profundidade, perda de sinal, consumo de energia.  
   - Planejar mitigação: redundância de sensores, protocolos de emergência.  

3. **Desenvolvimento e Validação (Quadrante 3)**  
   - Criar protótipos de software e simulações em ambiente controlado.  
   - Testar algoritmos de navegação e comunicação.  

4. **Planejamento da Próxima Iteração (Quadrante 4)**  
   - Revisar resultados dos testes.  
   - Ajustar cronograma e definir novos objetivos para a próxima volta da espiral.  

Esse ciclo se repete até que o sistema esteja maduro e confiável.

---

## Parte 2: Diagnóstico CMMI

### Situação Atual da Chaos-IT

- Cada desenvolvedor trabalha de forma independente.  
- Não há registro de erros passados.  
- Prazos são definidos sem base real.  
- O sucesso depende de esforço individual e horas extras.  

### Nível de Maturidade CMMI
A Chaos-IT se encontra no **Nível 1 - Inicial**.  
Esse nível é caracterizado pela ausência de processos padronizados, dependência de esforços individuais e resultados imprevisíveis.

### O que falta para chegar ao próximo nível
Para alcançar o nível 2 (Gerenciado), a empresa precisa:  
- Definir processos básicos de gerenciamento de projetos.  
- Estabelecer cronogramas realistas.  
- Documentar erros e lições aprendidas.  
- Criar padrões mínimos para desenvolvimento e controle de qualidade.  

---

## Conclusão
O Modelo Espiral é o mais adequado para projetos de alto risco, como o de IA subaquática, pois garante análise contínua de riscos e adaptação.  
Já no diagnóstico CMMI, a Chaos-IT precisa evoluir do nível inicial para o gerenciado, implementando processos básicos que reduzam a dependência de esforços individuais e aumentem a previsibilidade dos resultados.