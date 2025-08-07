# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 07/08/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Ever Johsue Ruiz Serrano 

---

## Introdução
Este relatório apresenta o processo de implementação de serviços na empresa **Abstergo Industries**, realizado por **Ever Johsue Ruiz Serrano**.  
O objetivo principal foi selecionar e configurar três serviços da AWS que pudessem gerar **redução imediata de custos operacionais**, mantendo a performance e segurança necessárias para as operações da empresa.

---

## Descrição do Projeto

### Etapa 1
- **Serviço:** Amazon EC2 com Auto Scaling  
- **Foco:** Otimização de custos com computação elástica  
- **Descrição do caso de uso:**  
  A empresa possuía servidores físicos subutilizados e com alto custo de manutenção. Foi implementado o **Amazon EC2** com grupos de **Auto Scaling**, permitindo aumentar ou reduzir a quantidade de instâncias conforme a demanda de tráfego. Assim, evitamos gastos com capacidade ociosa e garantimos disponibilidade em períodos de pico.

---

### Etapa 2
- **Serviço:** Amazon S3  
- **Foco:** Armazenamento seguro e econômico  
- **Descrição do caso de uso:**  
  Substituímos o armazenamento local de arquivos e backups por **Amazon S3** com política de **lifecycle** para migração automática para classes de armazenamento mais baratas, como **S3 Glacier**. Isso reduziu custos de hardware e aumentou a segurança e durabilidade dos dados (99,999999999%).

---

### Etapa 3
- **Serviço:** Amazon RDS (MySQL)  
- **Foco:** Banco de dados gerenciado e escalável  
- **Descrição do caso de uso:**  
  A infraestrutura anterior de banco de dados exigia manutenção manual e backups locais. Migramos para o **Amazon RDS** com instâncias otimizadas, backups automáticos e escalabilidade vertical/horizontal sob demanda. Isso reduziu a carga da equipe de TI e os custos com licenciamento e manutenção.

---

## Conclusão
A implementação desses serviços na **Abstergo Industries** trouxe benefícios como **redução de custos de até 35%**, aumento da **escalabilidade** e **resiliência** dos sistemas.  
Recomenda-se manter a utilização dos serviços implementados e avaliar novas integrações, como **AWS Lambda** e **Amazon CloudFront**, para potencializar ainda mais a performance e a economia.

---

**Assinatura:**  
Ever Johsue Ruiz Serrano