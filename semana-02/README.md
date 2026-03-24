# Proposta de Intervenção Técnica e Ética
**Curso:** Tecnologia em Sistemas para Internet  
**Módulo:** 3  
**Data:** 03/03/2026  
**Componente Curricular:** Engenharia de Software  
**Professor:** Gaio B. Oliveira  

---

## Cenário
A startup está desenvolvendo um software de inteligência artificial para triagem de currículos. Durante os testes, foi identificado que o algoritmo reproduz e amplia vieses históricos, discriminando grupos minoritários. Apesar da pressão dos investidores para lançar rapidamente, existem riscos éticos e legais que precisam ser considerados.

---

## Código de Ética ACM/IEEE
- **Cláusula 1.03**: “Evitar o dano aos outros.”  
  Aplicação: lançar o software enviesado causaria prejuízos a candidatos rejeitados injustamente.  
- **Cláusula 3.01**: “Garantir que os produtos atendam aos padrões profissionais mais elevados.”  
  Aplicação: é necessário assegurar qualidade técnica e ética, mesmo que isso implique atrasos.

---

## Opções Técnicas

### Human-in-the-loop
O sistema apenas ranqueia e um recrutador humano revisa os 20% inferiores.

| Prós | Contras |
|------|---------|
| Reduz risco de descarte injusto | Aumenta custo operacional |
| Cumpre parcialmente a LGPD | Não elimina o viés |
| Implementação rápida | Escalabilidade limitada |

---

### Toolkit de Explicabilidade (XAI)
Explica por que o candidato foi rejeitado.

| Prós | Contras |
|------|---------|
| Aumenta transparência | Exposição da lógica interna |
| Cumpre LGPD | Não corrige o viés |
| Diferencial competitivo | Implementação complexa |

---

### Auditoria de Dados
Limpeza estatística dos dados de treinamento, atraso de 4 semanas.

| Prós | Contras |
|------|---------|
| Reduz o viés estrutural | Atraso no lançamento |
| Cumpre padrões éticos e legais | Custo adicional |
| Evita processos judiciais | Pressão dos investidores |

---

## Impacto Financeiro
Um processo judicial baseado na LGPD pode gerar multas milionárias e danos à reputação da empresa. O atraso de 4 semanas representa apenas adiamento de receita e custos extras com a equipe de dados. Comparando os cenários, o atraso é menos oneroso e mais seguro do que enfrentar ações judiciais em massa.

---

## Conclusão
A alternativa mais responsável é realizar a **Auditoria de Dados** antes do lançamento. Além disso, recomenda-se implementar **XAI** para aumentar a transparência e considerar o **Human-in-the-loop** como medida complementar. Essa combinação garante conformidade com a LGPD, atende ao Código de Ética da ACM/IEEE e protege a sustentabilidade financeira e reputacional da startup.