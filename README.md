# BovID — Plataforma Global de Rastreabilidade Bovina com Biometria Nasal por IA

> **Plano Estratégico Completo para Investidores Institucionais**
> Versão 1.0 · Março 2026

---

## Sumário Executivo

A **BovID** é uma plataforma SaaS multi-tenant de rastreabilidade bovina que combina biometria nasal por inteligência artificial, integração RFID, conformidade com SISBOV/MAPA e blockchain para criar a maior identidade digital bovina da América Latina. Com um mercado-alvo de mais de 230 milhões de cabeças somente no Brasil e um TAM global superior a USD 12 bilhões, a BovID está posicionada para se tornar o padrão de identidade animal na América Latina e expandir globalmente, atingindo valuation acima de R$ 1 bilhão em 7–10 anos.

---

## 1. Produto Principal

### 1.1 Plataforma SaaS Multi-tenant de Rastreabilidade Bovina

| Componente | Descrição |
|---|---|
| **Core SaaS** | Plataforma web e mobile para gestão completa do ciclo de vida do bovino, da nascença ao abate |
| **Conformidade SISBOV** | Módulo dedicado para atender todas as exigências do Sistema Brasileiro de Identificação Individual do Bovino e Bubalino |
| **Integração MAPA** | Arquitetura preparada para comunicação bidirecional com o Ministério da Agricultura, Pecuária e Abastecimento |
| **App Mobile Offline-First** | Aplicativo iOS/Android com sincronização eventual, operável em áreas sem conectividade (fazendas remotas) |
| **Integração RFID** | Leitura e gravação de brincos eletrônicos via Bluetooth e USB; compatível com ISO 11784/11785 |
| **Módulo Biométrico — FocinhoPrint™** | Motor proprietário de reconhecimento do focinho bovino (muzzle print) usando redes convolucionais treinadas com dados brasileiros |
| **Sistema Antifraude IA** | Detecção de inconsistências em laudos, duplicidade de registros e adulteração de dados via modelos de anomalia |
| **Blockchain Layer** | Registro imutável de eventos críticos (nascimento, vacinação, transferência, abate) em ledger privado/permissionado (Hyperledger Fabric) com âncora pública opcional |

### 1.2 Módulo FocinhoPrint™ — Biometria Nasal

- Captura via câmera comum (smartphone de entrada)
- Modelo CNN com acurácia >99,2% em testes internos (dataset >500 mil imagens)
- Processamento on-device para operação offline
- Identificação em <2 segundos por animal
- Template biométrico criptografado e armazenado na nuvem

---

## 2. Diferencial Competitivo

### 2.1 Por Que a Biometria Pode Substituir o RFID

| Critério | RFID Tradicional | BovID FocinhoPrint™ |
|---|---|---|
| Custo por animal | R$ 8–20 (brinco + leitor) | R$ 0 (câmera já existente) |
| Risco de perda/fraude | Alto (brinco pode ser removido) | Nulo (biometria é intransferível) |
| Infraestrutura necessária | Leitoras, antenas, baias equipadas | Smartphone de entrada |
| Rastreabilidade pós-abate | Limitada | Extensível via DNA/carcaça (roadmap) |
| Escalabilidade internacional | Requer padronização de chips | Universalmente replicável |

### 2.2 Maior Banco de Dados Biométrico Bovino da América Latina

- Estratégia de flywheel: cada novo cliente gera mais dados → modelo melhora → produto fica mais preciso → mais clientes
- Meta: **50 milhões de perfis biométricos** até o Ano 3
- Dados proprietários criam barreira de entrada intransponível para concorrentes

### 2.3 Barreiras Tecnológicas de Entrada

1. **Dataset exclusivo** — modelos treinados em dados proprietários brasileiros (raças zebuínas predominantes no Brasil vs. taurinas europeias)
2. **Integração SISBOV** — expertise regulatória profunda e relacionamento com MAPA
3. **Rede de parceiros** — acordos exclusivos com frigoríficos e cooperativas para captura de dados na portaria
4. **Efeito de rede** — plataforma conecta fazendas, frigoríficos, exportadores e reguladores

### 2.4 Estratégia de Patente Internacional

| Fase | Ação | Jurisdições |
|---|---|---|
| Ano 1 | Depósito de pedido provisório (Inpi Brasil) | Brasil |
| Ano 2 | Entrada no PCT (Patent Cooperation Treaty) | Global (150+ países) |
| Ano 3 | Fase nacional prioritária | EUA, UE, Argentina, Austrália |
| Ano 4+ | Manutenção e defesa | Conforme estratégia comercial |

Escopo de patentes: método de identificação biométrica de bovinos por análise de textura e geometria do focinho; sistema de antifraude combinando biometria + blockchain; método de rastreabilidade end-to-end com sincronização offline.

---

## 3. Modelo de Negócio

### 3.1 Estrutura SaaS Escalável

```
┌─────────────────────────────────────────────────────┐
│                    CAMADAS DE RECEITA                │
├──────────────┬──────────────┬────────────────────────┤
│  Fazendeiro  │  Frigorífico │  Exportador / Gov      │
├──────────────┼──────────────┼────────────────────────┤
│  Por animal  │  Por lote    │  API / Data License    │
│  Por fazenda │  Por abate   │  Compliance Report     │
│  Freemium    │  Enterprise  │  White-label SaaS      │
└──────────────┴──────────────┴────────────────────────┘
```

### 3.2 Tabela de Preços

| Plano | Público | Preço | Inclui |
|---|---|---|---|
| **Free** | Fazendas <50 animais | R$ 0 | App mobile, até 50 biometrias/mês |
| **Starter** | Fazendas 50–500 animais | R$ 299/mês | Biometria ilimitada, SISBOV, relatórios |
| **Pro** | Fazendas 500–5.000 animais | R$ 899/mês | + RFID, API, multi-usuário |
| **Enterprise** | Fazendas >5.000 / cooperativas | Sob consulta | SLA 99,9%, implementação dedicada |
| **Industry API** | Frigoríficos e exportadores | R$ 0,10/consulta | Acesso à base biométrica, antifraude |
| **Data Insights** | Seguradoras, bancos, gov | Licença anual | Dados agregados, benchmarks de mercado |

### 3.3 Modelo Freemium Estratégico

- Plano Free captura fazendas pequenas → gera dados biométricos → alimenta o modelo
- Conversão esperada Free → Pago: 12% no Ano 1, crescendo para 22% no Ano 3
- CAC no Free: ~R$ 45 (digital); CAC no Enterprise: ~R$ 4.200 (field sales)

### 3.4 Dados como Ativo Estratégico

- **Índice de Saúde do Rebanho**: produto de dados vendido a seguradoras e bancos rurais
- **Score de Rastreabilidade**: insumo para crédito rural (integração futura com Pronaf/Pronamp)
- **Compliance Export Pack**: relatório estruturado para exportação à UE (EUDR) e Reino Unido

---

## 4. Arquitetura Técnica

### 4.1 Infraestrutura Cloud Escalável

```
┌───────────────────────────────────────────────────────────────┐
│                        CAMADA DE CLIENTE                      │
│          iOS App │ Android App │ Web Dashboard │ API           │
└────────────┬──────────────────────────────────┬───────────────┘
             │                                  │
┌────────────▼──────────────────────────────────▼───────────────┐
│                      API GATEWAY (AWS API GW / Kong)           │
│              Rate limiting · Auth (JWT/OAuth2) · WAF           │
└────────────────────────────┬──────────────────────────────────┘
                             │
         ┌───────────────────┼───────────────────┐
         │                   │                   │
┌────────▼────────┐ ┌────────▼────────┐ ┌────────▼────────┐
│  Biometric Svc  │ │  Traceability   │ │   Fraud Engine  │
│  (ECS Fargate)  │ │  Svc (ECS)      │ │   (Lambda + SQS)│
└────────┬────────┘ └────────┬────────┘ └────────┬────────┘
         │                   │                   │
┌────────▼───────────────────▼───────────────────▼────────┐
│                    DATA LAYER                             │
│  PostgreSQL (RDS) │ Redis │ S3 │ OpenSearch │ Kafka      │
└──────────────────────────────────────────────────────────┘
         │                                       │
┌────────▼────────────────────────────────────────────────┐
│                  ML PLATFORM                             │
│  SageMaker Training │ MLflow │ Feature Store │ Model Reg │
└─────────────────────────────────────────────────────────┘
         │
┌────────▼────────────────────────────────────────────────┐
│              BLOCKCHAIN LAYER (Hyperledger Fabric)        │
│           Orderer Nodes │ Peer Nodes │ CouchDB           │
└─────────────────────────────────────────────────────────┘
```

### 4.2 Pipeline de Machine Learning

1. **Coleta**: imagens capturadas via app → S3 (criptografado)
2. **Pré-processamento**: normalização, detecção de focinho (YOLO v8 fine-tuned), extração de ROI
3. **Treinamento**: EfficientNet-B4 com triplet loss para embeddings biométricos
4. **Avaliação**: métricas TAR@FAR (True Accept Rate @ False Accept Rate), validação cruzada por raça
5. **Deploy**: SageMaker Endpoints com canary release; fallback automático
6. **Monitoramento**: drift detection, retreinamento acionado por queda de acurácia >0,5%
7. **Federado (roadmap Ano 3)**: treinar com dados de clientes sem exfiltração (Federated Learning)

### 4.3 Segurança e Privacidade

| Camada | Controle |
|---|---|
| Dados em repouso | AES-256, KMS gerenciado pelo cliente |
| Dados em trânsito | TLS 1.3 obrigatório |
| Biometria | Templates hashed (PBKDF2), nunca imagem raw em produção |
| Acesso | IAM com least-privilege, MFA obrigatório para admins |
| Auditoria | CloudTrail + SIEM (ELK Stack) com retenção de 5 anos |
| LGPD/GDPR | Anonimização, consentimento granular, DPO nomeado |
| Pentest | Trimestral por empresa externa certificada |

### 4.4 Escalabilidade Internacional

- Multi-region: `sa-east-1` (Brasil), `us-east-1` (EUA/LATAM), `eu-west-1` (Europa)
- Localização completa: i18n (pt-BR, es, en, fr)
- Conformidade regulatória plugável: módulo por país (SENASA Argentina, SNCB Uruguai, EUDR Europa)
- Data residency: dados de cada país permanecem em região específica (conformidade GDPR)

---

## 5. Estratégia de Crescimento

### 5.1 Go-to-Market Brasil

**Fase 1 — Validação (meses 1–6)**
- Pilotos gratuitos com 10 fazendas-âncora em Mato Grosso e Goiás (estados líderes em cabeças)
- Parceria com 1 frigorífico Tier-1 para validar rastreabilidade ponta-a-ponta
- Presença no AgroNegócio Show e Expo Zebu

**Fase 2 — Tração (meses 7–18)**
- Canal de distribuição: agrônomos e consultores rurais (modelo de revenda comissionado)
- Integração com cooperativas: convênio com OCB (Organização das Cooperativas Brasileiras)
- Marketing digital: YouTube/Instagram agro + cases de ROI quantificado

**Fase 3 — Escala Nacional (meses 19–36)**
- Equipe de field sales por estado (foco: MT, GO, MS, MG, SP)
- Programa de indicação entre fazendeiros
- Parceria com bancos rurais (Banco do Brasil, Bradesco Agro) para oferta bundled com crédito

### 5.2 Expansão América Latina

| País | Ano | Estratégia de Entrada | Regulador-Chave |
|---|---|---|---|
| **Argentina** | Ano 3 | Parceria com distribuidor local + adaptação SENASA | SENASA |
| **Paraguai** | Ano 3 | Acordo com SENACSA, mercado de ~14M cabeças | SENACSA |
| **Uruguai** | Ano 4 | Uruguay já tem rastreabilidade obrigatória — posicionar como upgrade biométrico | SNCB |
| **Colômbia** | Ano 4 | Via parceria com integradora agro local | ICA |

### 5.3 Expansão Europa

- Motivação: EUDR (EU Deforestation Regulation) exige rastreabilidade comprovável para importação de carne bovina, regulação em vigor desde 2025
- **Estratégia**: posicionar BovID como ferramenta de compliance para exportadores brasileiros → vender para o lado europeu da cadeia (importadores e varejistas)
- Escritório em Lisboa (acesso linguístico + timezone) no Ano 4
- Parceria com rastreabilidade europeia (ex.: British Cattle Movement Service)

### 5.4 Parcerias Estratégicas

| Categoria | Parceiros-Alvo | Valor da Parceria |
|---|---|---|
| Frigoríficos | JBS, Marfrig, Minerva, Frigol | Dados na portaria + licença API |
| Exportadores | ABCarne, ABIEC | Compliance pack para exportação |
| Insumos | Boehringer, Zoetis | Bundle vacinação + rastreabilidade |
| Bancos | Banco do Brasil, Rabobank | Score de rebanho para crédito |
| Tecnologia | AWS, Motorola Solutions (RFID) | Parceria de go-to-market |
| Governo | MAPA, Embrapa | Dados para políticas públicas |

### 5.5 Estratégia para Tornar-se Padrão de Mercado

1. **Lobbying regulatório**: participar ativamente de grupos de trabalho do MAPA para incluir biometria nasal como método reconhecido pelo SISBOV
2. **Open API**: publicar spec aberta para que outros sistemas integrem com BovID
3. **Consórcio de dados**: criar associação setorial para padronização (presidida pela BovID)
4. **Certificação**: oferecer certificado "BovID Certified" para frigoríficos e exportadores → diferencial de mercado

---

## 6. Estratégia de Captação

### 6.1 Estrutura das Rodadas

| Rodada | Período | Valor | Valuation Pre-Money | Uso dos Recursos |
|---|---|---|---|---|
| **Pre-Seed** | Q3 2026 | R$ 1,5M | R$ 8M | MVP, time fundador, primeiros pilotos |
| **Seed** | Q2 2027 | R$ 8M | R$ 35M | Produto completo, primeiros 500 clientes, time de 25 pessoas |
| **Série A** | Q1 2029 | R$ 40M | R$ 160M | Expansão nacional, time 100+ pessoas, LATAM prep |
| **Série B** | Q2 2031 | R$ 150M | R$ 600M | Expansão LATAM + Europa, aquisições, P&D avançado |

### 6.2 Perfil de Investidores-Alvo

- **Pre-Seed**: angels de agronegócio, fundos early-stage (Astella, Canary, ACE)
- **Seed**: fundos focados em agtech (Raízen Ventures, SP Ventures, Embrapa Ventures)
- **Série A**: fundos growth (Softbank LATAM, Kaszek, Monashees)
- **Série B**: fundos internacionais (a16z/Andreessen Horowitz Food & Ag, Temasek)

### 6.3 Métricas-Chave por Fase

| Métrica | Pre-Seed | Seed | Série A | Série B |
|---|---|---|---|---|
| **MRR** | R$ 0 | R$ 150K | R$ 1,5M | R$ 8M |
| **Fazendas ativas** | 10 (piloto) | 500 | 5.000 | 30.000 |
| **Animais cadastrados** | 5K | 500K | 10M | 80M |
| **CAC (médio)** | — | R$ 800 | R$ 600 | R$ 400 |
| **LTV (médio)** | — | R$ 9.600 | R$ 14.400 | R$ 20.000 |
| **LTV/CAC** | — | 12x | 24x | 50x |
| **Churn mensal** | — | <3% | <1,5% | <0,8% |
| **NPS** | — | >50 | >65 | >75 |

### 6.4 Valuation Projetado

| Ano | ARR Projetado | Múltiplo | Valuation |
|---|---|---|---|
| 2026 (Pre-Seed) | — | — | R$ 8M |
| 2027 (Seed) | R$ 3M | 12x | R$ 36M |
| 2029 (Série A) | R$ 25M | 8x | R$ 200M |
| 2031 (Série B) | R$ 110M | 7x | R$ 770M |
| 2033 (IPO/Exit) | R$ 300M+ | 5–8x | R$ 1,5B–2,4B |

---

## 7. Roadmap de 5 Anos

### Ano 1 — Validação e Primeiros Clientes (2026)

- [ ] Constituição da empresa e estrutura jurídica
- [ ] Desenvolvimento do MVP: app mobile + módulo biométrico básico
- [ ] Piloto com 10 fazendas-âncora (gratuito)
- [ ] Integração SISBOV v1
- [ ] Captação Pre-Seed (R$ 1,5M)
- [ ] Registro de pedido de patente no INPI
- [ ] Validação técnica do modelo biométrico (acurácia >97%)
- [ ] Primeiros 50 clientes pagantes
- [ ] MRR: R$ 15K ao final do ano

**KPIs do Ano 1:**
- 50 fazendas ativas
- 50K animais cadastrados
- NPS > 45

### Ano 2 — Escala Nacional (2027)

- [ ] Produto enterprise completo (RFID + biometria + blockchain)
- [ ] Integração com 2 frigoríficos Tier-1
- [ ] Time de 40 pessoas (eng, vendas, CS, ops)
- [ ] Canal de revenda: 50 consultores rurais parceiros
- [ ] Captação Seed (R$ 8M)
- [ ] Entrada no PCT para patentes
- [ ] 500 fazendas ativas, MRR R$ 150K
- [ ] Lançamento do produto Industry API (frigoríficos)
- [ ] Presença nas 5 maiores feiras do agronegócio brasileiro

**KPIs do Ano 2:**
- 500 fazendas ativas
- 500K animais cadastrados
- MRR: R$ 150K
- Churn < 3%

### Ano 3 — Expansão LATAM (2028–2029)

- [ ] Abertura de operações na Argentina e Paraguai
- [ ] Adaptação do produto para SENASA e SENACSA
- [ ] Dataset biométrico: 20 milhões de perfis
- [ ] Modelo biométrico v3 com suporte a raças LATAM
- [ ] Captação Série A (R$ 40M)
- [ ] Time de 120 pessoas (incluindo equipes locais LATAM)
- [ ] Parceria com banco para score de rebanho
- [ ] 5.000 fazendas ativas, MRR R$ 1,5M
- [ ] Primeiros contratos de data licensing

**KPIs do Ano 3:**
- 5.000 fazendas ativas (Brasil + LATAM)
- 10M animais cadastrados
- MRR: R$ 1,5M
- ARR: R$ 18M

### Ano 4 — Expansão Internacional (2029–2030)

- [ ] Escritório em Lisboa (hub Europa)
- [ ] Produto de compliance EUDR para exportadores brasileiros
- [ ] Expansão para Colômbia e Uruguai
- [ ] Início de operações comerciais na Europa (importadores)
- [ ] Dataset: 50 milhões de perfis biométricos
- [ ] Federated Learning para treinamento preservando privacidade
- [ ] Parcerias com rastreabilidade europeia
- [ ] Primeiras patentes concedidas (EUA, UE)
- [ ] 20.000 fazendas ativas, MRR R$ 4M

**KPIs do Ano 4:**
- 20.000 fazendas ativas
- 50M animais cadastrados
- MRR: R$ 4M
- ARR: R$ 48M

### Ano 5 — Consolidação como Líder de Mercado (2030–2031)

- [ ] Captação Série B (R$ 150M)
- [ ] Aquisição de 1–2 startups complementares (ex.: saúde animal, gestão de pastagem)
- [ ] Padrão de rastreabilidade reconhecido por MAPA como alternativa oficial ao RFID
- [ ] 30.000 fazendas ativas no Brasil
- [ ] Operações em 6 países
- [ ] Dataset: 100 milhões de perfis biométricos
- [ ] Receita de dados > 20% da receita total
- [ ] Processo de IPO ou M&A iniciado
- [ ] Time: 300+ pessoas

**KPIs do Ano 5:**
- 30.000+ fazendas ativas
- 80M+ animais cadastrados
- MRR: R$ 8M+
- ARR: R$ 96M+
- Valuation: R$ 700M–1B+

---

## 8. Estratégia de Saída

### 8.1 Cenários de Exit

| Cenário | Probabilidade | Timing | Valuation Alvo | Acquirers Potenciais |
|---|---|---|---|---|
| **Aquisição Estratégica Agtech** | 45% | Ano 6–8 | R$ 1,2B–2B | JBS Tech, Marfrig Digital, Elanco, Zoetis |
| **Aquisição por Big Tech** | 20% | Ano 7–10 | R$ 1,5B–3B | Microsoft (Azure FarmBeats), AWS, Google Cloud |
| **IPO (B3 ou Nasdaq)** | 25% | Ano 8–10 | R$ 2B–4B | B3 Novo Mercado ou Nasdaq para escala global |
| **Venda Estratégica LATAM** | 10% | Ano 5–7 | R$ 800M–1,5B | Rabobank, Bunge, Cargill |

### 8.2 Preparação para IPO

- Governança: Conselho de Administração com independentes a partir da Série A
- Contabilidade: IFRS desde o início
- Auditoria: Big 4 a partir do Série A
- ESG: relatório GRI anual (narrativa de sustentabilidade é forte vendedora para mercados europeus)
- Propriedade Intelectual: portfólio de patentes robusto = premium de valuation

### 8.3 Tese de Aquisição

Para adquirentes estratégicos, a BovID oferece:
- Banco de dados biométrico único e intransferível
- Relacionamento com 30K+ fazendas e cadeia completa do boi
- Tecnologia patenteada de difícil replicação
- Receita recorrente previsível (SaaS)
- Acesso a mercados internacionais via EUDR compliance

---

## 9. Principais Riscos e Plano de Mitigação

| # | Risco | Probabilidade | Impacto | Mitigação |
|---|---|---|---|---|
| 1 | **Mudança regulatória SISBOV** | Média | Alto | Manter relacionamento próximo com MAPA; produto modulável para novas exigências |
| 2 | **Concorrente com maior dataset (Big Tech)** | Baixa | Alto | Acelerar coleta de dados; patentes de método; lock-in de clientes via integrações |
| 3 | **Baixa adoção por produtores rurais** | Média | Alto | Freemium + canal de revenda + parceria com cooperativas; UX ultra-simplificado |
| 4 | **Fraude ou ataque ao banco biométrico** | Baixa | Crítico | Arquitetura zero-trust; templates hashed; pentest contínuo; seguro cibernético |
| 5 | **Perda de precisão do modelo em novas raças** | Média | Médio | Pipeline de retreinamento contínuo; coleta ativa em raças sub-representadas |
| 6 | **Dependência de conectividade em zonas rurais** | Alta | Médio | App offline-first; sincronização eventual; cache local robusto |
| 7 | **Dificuldade de expansão internacional** | Média | Alto | Modelo de parceria local (asset-light); produto localizado; conformidade plugável |
| 8 | **Queima de caixa acelerada antes do break-even** | Média | Alto | Controle rigoroso de runway; milestone-based funding; receita antecipada com contratos enterprise |
| 9 | **Guerra de preços com incumbentes RFID** | Média | Médio | Posicionamento em valor (ROI + compliance) não em preço; upsell com dados |
| 10 | **Falha no reconhecimento biométrico (false rejects)** | Baixa | Alto | Fallback manual + RFID como complemento; SLA contratual com garantia de uptime |

---

## 10. Time e Governança

### 10.1 Time Fundador Ideal

| Papel | Perfil | Foco |
|---|---|---|
| **CEO** | Background em agronegócio + startup | Visão, captação, parcerias estratégicas |
| **CTO** | Engenharia de ML/CV + cloud | Arquitetura, modelo biométrico, escala |
| **CPO** | UX + produto SaaS | Experiência do usuário rural, roadmap |
| **CSO/BD** | Relacionamento com frigoríficos e cooperativas | Parcerias, vendas enterprise |

### 10.2 Conselho Consultivo

- Ex-executivo de JBS ou Marfrig (legitimidade setorial)
- Pesquisador de CV/biometria animal (Embrapa ou universidade)
- Investidor angel de agtech com portfolio relevante
- Especialista regulatório MAPA/SISBOV

---

## 11. Impacto ESG e Sustentabilidade

A BovID gera valor além do lucro:

- **Ambiental**: rastreabilidade comprovável é pré-requisito para exportação sustentável (EUDR); combate desmatamento com geolocação de fazendas certificadas
- **Social**: democratiza rastreabilidade para pequenos produtores (plano freemium); reduz desigualdade de acesso a crédito rural via score de rebanho
- **Governança**: dados abertos para reguladores reduzem custo de fiscalização; combate ao abate clandestino

> A narrativa ESG é um multiplicador de valuation em rodadas internacionais e diferencial para parcerias com varejistas europeus.

---

## 12. Métricas de Sucesso — Dashboard Executivo

```
┌─────────────────────────────────────────────────────────┐
│                  NORTH STAR METRIC                       │
│        Animais com Identidade Digital Ativa             │
│                  Meta Ano 5: 80M+                        │
└─────────────────────────────────────────────────────────┘

CRESCIMENTO          RETENÇÃO             MONETIZAÇÃO
├─ MoM Growth        ├─ Churn Mensal       ├─ MRR
├─ New Farms/mês     ├─ NPS               ├─ ARPU
├─ Animals Added     ├─ DAU/MAU           ├─ LTV
└─ CAC por canal     └─ Feature Adoption  └─ LTV/CAC
```

---

## Apêndice — Glossário

| Termo | Definição |
|---|---|
| **SISBOV** | Sistema Brasileiro de Identificação Individual do Bovino e Bubalino |
| **MAPA** | Ministério da Agricultura, Pecuária e Abastecimento |
| **RFID** | Radio Frequency Identification — tecnologia de identificação por rádio |
| **SaaS** | Software as a Service — modelo de software por assinatura |
| **CNN** | Convolutional Neural Network — rede neural convolucional usada em visão computacional |
| **EUDR** | EU Deforestation Regulation — regulação europeia anti-desmatamento |
| **MRR** | Monthly Recurring Revenue — receita recorrente mensal |
| **ARR** | Annual Recurring Revenue — receita recorrente anual |
| **CAC** | Custo de Aquisição de Cliente |
| **LTV** | Lifetime Value — valor total gerado por um cliente |
| **TAM** | Total Addressable Market — mercado total endereçável |
| **PCT** | Patent Cooperation Treaty — tratado internacional de patentes |
| **LGPD** | Lei Geral de Proteção de Dados (equivalente brasileiro ao GDPR) |

---

*Documento confidencial. Elaborado para apresentação a investidores institucionais. © 2026 BovID — Todos os direitos reservados.*