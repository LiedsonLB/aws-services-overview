# 📖 Guia Completo dos Serviços AWS

Por: [Liedson Barros LB](https://www.linkedin.com/in/liedsonlb/)

## 📊 Serviços de Análise
- **Amazon Redshift** → Data warehouse gerenciado para análise de dados usando SQL padrão.
- **Amazon Kinesis** → Streaming de dados em tempo real para coleta, processamento e análise.
- **AWS Glue** → Serviço ETL gerenciado para preparação e carregamento de dados.
- **Amazon QuickSight** → Serviço de BI (Business Intelligence) para visualização de dados interativa.
- **AWS Lake Formation** → Criação e gerenciamento de Data Lakes de forma segura e automatizada.

## 🔗 Serviços de Integração de Aplicações
- **Amazon SNS** → Serviço de notificações escalável e econômico.
- **Amazon SQS** → Fila de mensagens para desacoplar e escalar microsserviços.
- **Amazon EventBridge** → Barramento de eventos para conectar aplicações.
- **AWS Step Functions** → Orquestração de fluxos de trabalho para aplicações distribuídas.
- **Amazon API Gateway** → Serviço para criação, publicação e gerenciamento de APIs.

## 🛠 Serviços de Gerenciamento e Governança
- **AWS CloudFormation** → Modelagem e configuração de recursos da AWS.
- **AWS CloudTrail** → Auditoria de ações realizadas na conta AWS.
- **AWS Config** → Monitoramento da conformidade da configuração dos recursos.
- **AWS Trusted Advisor** → Recomendações para otimização de custo, desempenho e segurança.
- **AWS Organizations** → Gerenciamento de múltiplas contas AWS de forma centralizada.
- **AWS Service Catalog** → Gerenciamento de catálogos de serviços aprovados dentro da empresa.
- **AWS Control Tower** → Serviço para configurar e governar múltiplas contas AWS seguindo boas práticas.

## 💻 Serviços de Desenvolvimento e DevOps
- **AWS CodeCommit** → Repositório Git gerenciado na nuvem.
- **AWS CodePipeline** → Automação de pipelines de CI/CD.
- **AWS CodeBuild** → Integração contínua com compilação e testes automatizados.
- **AWS CodeDeploy** → Serviço para implantação automatizada de aplicações.
- **AWS X-Ray** → Rastreamento de requisições em aplicações distribuídas para identificar gargalos.

## 🔐 Serviços de Segurança, Identidade e Conformidade
- **AWS IAM** → Gerenciamento de acessos e permissões.
- **AWS KMS** → Gerenciamento de chaves de criptografia.
- **AWS Shield** → Proteção contra ataques DDoS.
- **AWS WAF** → Proteção contra ataques na camada de aplicação.
- **Amazon GuardDuty** → Detecção de ameaças para proteger contas e workloads da AWS.
- **AWS Security Hub** → Centralização e análise de alertas de segurança.
- **AWS Artifact** → Acesso a relatórios de conformidade e auditorias da AWS.
- **AWS Secrets Manager** → Gerenciamento seguro de credenciais e segredos de aplicações.
- **AWS Inspector** → Análise automatizada de vulnerabilidades de segurança.

## 🤖 Serviços de Inteligência Artificial e Machine Learning
- **Amazon SageMaker** → Criação, treinamento e implantação de modelos de ML.
- **Amazon Rekognition** → Análise de imagens e vídeos.
- **Amazon Comprehend** → Processamento de linguagem natural (NLP).
- **Amazon Lex** → Construção de chatbots e assistentes virtuais.
- **Amazon Polly** → Conversão de texto em fala com vozes realistas.
- **Amazon Transcribe** → Serviço de transcrição automática de áudio para texto.

## 📡 Serviços de IoT (Internet das Coisas)
- **AWS IoT Core** → Conexão segura de dispositivos IoT à nuvem.
- **AWS Greengrass** → Computação local e sincronização para dispositivos IoT.
- **AWS IoT Analytics** → Análise de dados gerados por IoT.
- **AWS IoT Device Defender** → Monitoramento da segurança de dispositivos IoT.

## 🔄 Serviços de Migração e Transferência
- **AWS DMS** → Migração de bancos de dados.
- **AWS Snowball** → Transferência de grandes volumes de dados com dispositivos físicos.
- **AWS Migration Hub** → Rastreamento centralizado de migrações.
- **AWS MGN** → Migração automatizada de servidores para a AWS.

## 🎥 Serviços de Mídia
- **AWS Elemental MediaConvert** → Transcodificação de vídeos sob demanda.
- **AWS Elemental MediaLive** → Processamento de vídeo ao vivo.
- **AWS Elemental MediaPackage** → Preparação e proteção de vídeos para entrega online.

## 🕶 Serviços de Realidade Aumentada e Virtual
- **Amazon Sumerian** → Criação de aplicações de AR, VR e 3D sem necessidade de programação avançada.

## 🏛 Well-Architected Framework
A AWS fornece um conjunto de boas práticas chamado AWS Well-Architected Framework, que se baseia em seis pilares:
- **Excelência Operacional** → Monitoramento, automação e melhoria contínua.
- **Segurança** → Proteção de informações e sistemas.
- **Confiabilidade** → Recuperação de falhas e escalabilidade.
- **Eficiência de Performance** → Uso eficiente dos recursos.
- **Otimização de Custos** → Minimização de desperdícios.
- **Sustentabilidade** → Redução do impacto ambiental da infraestrutura em nuvem.

## 💰 Planos de Suporte AWS
- **Basic** → Gratuito, inclui suporte a recursos da AWS e guias.
- **Developer** → Suporte técnico durante o horário comercial via e-mail.
- **Business** → Suporte 24/7 via chat, telefone e e-mail.
- **Enterprise** → Suporte 24/7 com gerente técnico de conta (TAM) e acesso direto a engenheiros da AWS.

## 📌 Modelos de Precificação da AWS
- **Pay-as-you-go** → Pague apenas pelo que usar, sem compromisso antecipado.
- **Savings Plans** → Planos de desconto para uso contínuo de serviços.
- **Reserved Instances** → Descontos para compromissos de longo prazo.
- **Spot Instances** → Instâncias de EC2 mais baratas, mas que podem ser interrompidas.
- **Free Tier** → Serviços gratuitos com limites específicos por 12 meses ou indefinidamente.

## 🌍 AWS Global Infrastructure
A AWS possui uma infraestrutura global altamente distribuída para oferecer baixa latência, alta disponibilidade e escalabilidade.

### 📍 Regiões e Zonas de Disponibilidade
- **Região** → Localização geográfica onde a AWS tem data centers (ex: `us-east-1` → Virgínia do Norte).
- **Zona de Disponibilidade (AZ)** → Conjunto de um ou mais data centers dentro de uma região.

### 📡 Edge Locations e AWS Global Accelerator
- **Edge Locations** → Pontos de presença (PoP) da AWS usados pelo CloudFront para entrega de conteúdo.
- **AWS Global Accelerator** → Melhora o desempenho do tráfego de rede.

## 🌐 Infraestrutura Híbrida e Edge Computing
- **AWS Outposts** → AWS entrega servidores físicos para rodar AWS on-premises.
- **AWS Wavelength** → AWS em redes 5G.
- **AWS Local Zones** → Data centers da AWS próximos de grandes cidades.

## 🏢 Ambientes On-Premises vs. Nuvem AWS
### 🔥 Diferenças
- **On-Premises** → Infraestrutura local gerenciada pelo cliente.
- **Hybrid Cloud** → Uso combinado de nuvem AWS e infraestrutura local.
- **Full Cloud** → Todas as aplicações e dados na AWS.

### 🛠 Serviços para Migração e Conectividade
- **AWS Direct Connect** → Conexão privada entre data center local e AWS.
- **AWS VPN** → Conexão segura via internet.
- **AWS Snowball** → Transferência física de grandes volumes de dados.
- **AWS Storage Gateway** → Acesso a armazenamento AWS a partir de data centers locais.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias e novas funcionalidades.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).

## Contato

Se tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato através de:

- **Email**: [liedson.b9@gmail.com](mailto:liedson.b9@gmail.com)
- **LinkedIn**: [liedsonlb](https://linkedin.com/in/liedsonlb)
- **Instagram**: [liedson.vue](https://www.instagram.com/liedson.vue)
- **Github**: [LiedsonLB](https://github.com/LiedsonLB)
- **Portfólio**: [Liedson Barros](https://liedsonbarros.vercel.app)