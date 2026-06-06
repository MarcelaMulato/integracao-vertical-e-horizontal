# Aula 06 — Sistemas ERP na Integração Industrial  

---

## Capítulo 1 — Contextualização do ERP

### 1.1 O ERP dentro da Integração de Sistemas

Ao longo da disciplina, foram abordados progressivamente:
- Redes industriais — comunicação  
- SDCD/CLP — controle  
- SCADA — supervisão  
- MES — execução  

Neste ponto, alcançamos o **nível mais elevado da pirâmide**: o **ERP (Enterprise Resource Planning)**.

O ERP é responsável por **integrar e administrar a organização como um todo**, conectando:
- Produção  
- Logística  
- Financeiro  
- Compras  
- Vendas  
- Recursos humanos  
- Demais áreas de negócio  

Sua função central é converter dados operacionais em **decisões de caráter estratégico**.

---

### 1.2 Papel do ERP na Indústria

O ERP não opera diretamente no chão de fábrica.  
Ele atua nos níveis **estratégico e gerencial**, sendo responsável por:
- Planejar a produção  
- Administrar recursos  
- Promover a integração entre setores  
- Subsidiar a tomada de decisão  

Na prática, ele responde questões como:
- O que produzir?  
- Quando produzir?  
- Quanto produzir?  
- Qual será o custo envolvido?  

---

## Capítulo 2 — Conceito de ERP

### 2.1 Definição

O **ERP (Enterprise Resource Planning)** é um sistema integrado de gestão que centraliza informações e processos de toda a organização em uma plataforma unificada.

---

### 2.2 Características principais

Um ERP apresenta:
- Base de dados centralizada  
- Módulos interligados  
- Atualização em tempo real  
- Padronização de processos  

Isso previne:
- Retrabalho  
- Inconsistência de informações  
- Falhas na comunicação entre setores  

---

### 2.3 ERP como sistema integrador

Sem ERP:
- Departamentos isolados  
- Planilhas desconectadas  
- Decisões baseadas em dados incompletos  

Com ERP:
- Visão unificada da empresa  
- Dados consistentes e atualizados  
- Decisões mais ágeis e fundamentadas  

---

## Capítulo 3 — Módulos de um ERP

### 3.1 Principais módulos

#### Financeiro
- Contas a pagar/receber  
- Fluxo de caixa  
- Faturamento  

---

#### Compras
- Gestão de fornecedores  
- Pedidos de compra  
- Controle de suprimentos  

---

#### Estoque
- Controle de materiais  
- Registro de entradas e saídas  
- Inventário  

---

#### Produção (PCP)
- Planejamento da produção  
- Ordens de produção  
- Controle de capacidade  

---

#### Vendas
- Pedidos de clientes  
- Faturamento  
- Histórico comercial  

---

#### Recursos Humanos
- Folha de pagamento  
- Gestão de colaboradores  
- Avaliação de desempenho  

---

### 3.2 Integração entre módulos

O diferencial de um ERP reside na **integração automática entre seus módulos**, de modo que uma ação realizada em determinado setor gera reflexos imediatos nos demais.

Isso elimina retrabalho, minimiza erros e assegura a coerência dos dados em toda a organização.

---

### Exemplos de Integração

- Venda efetuada — atualiza financeiro, estoque e faturamento  
- Produção iniciada — consome matéria-prima do estoque  
- Estoque abaixo do mínimo — gera solicitação de compra  
- Compra concluída — atualiza contas a pagar  
- Produto expedido — gera faturamento automático  
- Colaborador alocado — impacta custo de produção  
- Ordem de produção encerrada — atualiza estoque de produto acabado  
- Atraso na produção — afeta prazo de entrega ao cliente  

---

### Tabela de Integração entre Módulos

| Evento | Módulo de Origem | Módulos Impactados | Resultado |
|--------|-----------------|-------------------|-----------|
| Venda realizada | Vendas | Financeiro, Estoque | Geração de receita e baixa no estoque |
| Emissão de nota fiscal | Vendas | Financeiro | Registro de contas a receber |
| Produção iniciada | Produção (PCP) | Estoque | Consumo de matéria-prima |
| Produção finalizada | Produção | Estoque, Vendas | Entrada de produto acabado disponível |
| Estoque mínimo atingido | Estoque | Compras | Geração automática de pedido de compra |
| Pedido de compra aprovado | Compras | Financeiro | Geração de contas a pagar |
| Recebimento de material | Compras | Estoque | Atualização do inventário |
| Pagamento a fornecedor | Financeiro | Compras | Baixa de obrigação financeira |
| Contratação de funcionário | RH | Financeiro | Impacto na folha de pagamento |
| Alocação de operador na produção | RH | Produção | Atualização de custo operacional |
| Atraso na produção | Produção | Vendas, Logística | Reprogramação de entrega |
| Devolução de produto | Vendas | Estoque, Financeiro | Ajuste de estoque e estorno financeiro |

---

### Interpretação

Observa-se que:
- Nenhum módulo opera de forma isolada  
- Um único evento pode repercutir em diversos setores simultaneamente  
- A informação transita automaticamente pela organização  

---

### Síntese da Integração

A integração entre módulos posiciona o ERP como um **sistema nervoso da organização**, onde:
- informações circulam em tempo real  
- decisões se apoiam em dados confiáveis  
- processos ocorrem de maneira sincronizada  

É isso que viabiliza uma gestão contemporânea, eficiente e orientada por dados.

---

## Capítulo 4 — Exemplo Prático

### Fábrica de bebidas

#### 1. Pedido
Cliente solicita 10.000 unidades  
ERP:
- Registra a venda  
- Calcula o custo  
- Verifica disponibilidade em estoque  

---

#### 2. Planejamento
ERP:
- Gera ordem de produção  
- Transmite ao MES  

---

#### 3. Execução
MES:
- Distribui a produção  
- Planeja a utilização das máquinas  

---

#### 4. Produção
CLP + sensores:
- Executam o processo produtivo  

---

#### 5. Monitoramento
SCADA:
- Exibe dados em tempo real  

---

#### 6. Retorno
ERP recebe:
- Volume produzido  
- Custos apurados  
- Tempo de execução  
- Demais indicadores  

---

## Conclusão

O ERP consolida a integração empresarial ao transformar dados operacionais em **informação gerencial de valor**.

Seu principal diferencial não reside apenas no controle, mas na capacidade de:
- alinhar planejamento e execução  
- oferecer visibilidade do negócio como um todo  
- possibilitar respostas rápidas diante de mudanças  

Na prática, ele assegura que o planejado seja efetivamente executado — e que ajustes possam ser feitos com base em dados concretos.

Dessa forma, o ERP encerra o ciclo da integração vertical, estabelecendo uma conexão contínua entre operação e estratégia.
