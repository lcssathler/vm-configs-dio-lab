# **Projeto de Configuração e Dimensionamento de Máquinas Virtuais no Microsoft Azure**

## **📌 Descrição do Projeto**  
Este projeto demonstra como configurar e dimensionar Máquinas Virtuais (VMs) no Microsoft Azure, abordando:  
- Seleção de tipos de instância (CPU, memória, armazenamento).  
- Escalabilidade vertical (*scale-up*) e horizontal (*scale-out*).  
- Otimização de custos e desempenho.  

## **🎯 Objetivos**  
- Configurar recursos de VMs (vCPU, RAM, disco).  
- Implementar autoescala com **VM Scale Sets**.  
- Monitorar desempenho com **Azure Monitor**.  
- Analisar custos via **Azure Cost Management**.  

## **🛠️ Tecnologias Utilizadas**  
| Ferramenta | Uso |  
|------------|-----|  
| **Portal Azure** | Interface gráfica para gerenciamento |  
| **Azure CLI** | Automação de comandos |  
| **VM Scale Sets** | Escalabilidade horizontal |  
| **Azure Monitor** | Métricas de desempenho |  

## **📋 Passos do Projeto**  
1. **Criação da VM**  
   - Escolha do SO (Windows/Linux) e tipo de instância (ex: série B, D).  
   - Configuração de rede (NSG, IP público).
   - ![image](https://github.com/user-attachments/assets/15fe54d6-b7e5-40a1-93c1-e84f8e693c0f)


2. **Dimensionamento**  
   - Ajuste de vCPUs/memória (*scale-up*).  
   - Adição de discos (SSD Premium/HDD Standard).  
   - Configuração de autoescala (*scale-out*).
   - ![image](https://github.com/user-attachments/assets/9afdcbc2-1b22-45b5-9cf5-b5a733cc8313)


3. **Otimização**  
   - Uso do **Azure Monitor** para métricas.  
   - Políticas de desligamento automático.  
   - Relatório de custos.
   - ![image](https://github.com/user-attachments/assets/60fa8fac-c785-4435-8d4a-8718986cb24e)
   
## **🔗 Referências**  
- [Documentação Oficial Azure VMs](https://docs.microsoft.com/pt-br/azure/virtual-machines/)  
- [Calculadora de Custos Azure](https://azure.microsoft.com/pt-br/pricing/calculator/)  
