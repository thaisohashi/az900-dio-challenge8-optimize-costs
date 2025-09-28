# 💰 Desafio 8: Otimizando Custos no Azure – Bootcamp Microsoft Azure AZ-900  

Este repositório contém meu **oitavo desafio** do bootcamp **Microsoft Azure AZ-900**, oferecido pela **DIO em parceria com a Microsoft**.  

O objetivo deste desafio foi conhecer e praticar o uso das **ferramentas de cálculo de custos do Azure**, fundamentais para avaliar cenários de migração e planejar orçamentos.  

## Calculadora de TCO (Custo Total de Propriedade)  
🔗 [Acesse aqui](https://azure.microsoft.com/pt-br/pricing/tco/calculator)  

A Calculadora de **TCO** ajuda a **comparar os custos de manter uma infraestrutura local (on-premises)** com os custos de migrar para o Azure.  

### Etapas principais:  
1. **Definir cargas de trabalho**  
   - Servidores  
   - Bancos de dados  
   - Armazenamento  
   - Rede  

2. **Ajustar suposições**  
   - Exemplo: ativar a **cobertura do Software Assurance**, que permite usar o **Benefício Híbrido do Azure** e reduzir custos de licenciamento.  

3. **Exibir relatório**  
   - O Azure gera uma estimativa mostrando o comparativo entre manter a infraestrutura local e migrar para a nuvem.  

**Exemplo prático**:  
Uma empresa que mantém **10 servidores físicos** e precisa atualizar hardware em breve pode usar a TCO para verificar se migrar para o Azure é mais barato a longo prazo, considerando custos de energia, manutenção e licenciamento.  

## Calculadora de Preço  
🔗 [Acesse aqui](https://azure.microsoft.com/pt-br/pricing/calculator/)  

A Calculadora de **Preço** é usada para **estimar o custo mensal** de serviços específicos do Azure, considerando configurações personalizadas.  

### Etapas principais:  
1. **Selecionar produtos**  
   - Máquinas Virtuais  
   - Banco de Dados SQL  
   - Contas de Armazenamento  
   - Rede Virtual, etc.  

2. **Configurar os detalhes do produto**  
   - Região  
   - Tamanho  
   - Tipo de armazenamento  
   - Opções de redundância  

**Exemplo prático**:  
Se eu quero criar uma **máquina virtual B1s** no Azure, posso adicionar esse item na calculadora, escolher a região **East US**, disco **SSD Standard** e ver o custo mensal estimado.  

## Diferença entre as duas ferramentas  
- **TCO (Total Cost of Ownership)**: visão **estratégica** e de **longo prazo**, útil para empresas que estão avaliando migrar do ambiente local para a nuvem.  
- **Calculadora de Preço**: visão **tática e operacional**, usada para estimar quanto custará **um serviço específico** já dentro do Azure.  
