# ETC - Cloud Computing

Materiais sobre a palestra de Cloud Computing.


## CONCEITOS DE CLOUD COMPUTING

### O que é uma nuvem pública?
As nuvens públicas são a maneira mais comum de implantar a computação em nuvem. Os recursos de nuvem (como servidores e armazenamento) pertencem a um provedor de serviço de nuvem terceirizado, são operados por ele e entregues pela Internet. O Microsoft Azure é um exemplo de nuvem pública. Com uma nuvem pública, todo o hardware, software e outras infraestruturas de suporte são de propriedade e gerenciadas pelo provedor de nuvem. Em uma nuvem pública, você compartilha os mesmos dispositivos de hardware, de armazenamento e de rede com outras organizações ou “locatários” da nuvem. Você acessa serviços e gerencia sua conta usando um navegador da Web. As implantações de nuvem pública geralmente são usadas para fornecer email baseado na Web, aplicativos de escritório online, armazenamento e ambientes de desenvolvimento e teste.

**Vantagens das nuvens públicas:**
- Redução de custos – não há necessidade de comprar hardware ou software e você paga somente pelos serviços que usa.
- Sem manutenção – seu provedor de serviços fornece a manutenção.
- Escalabilidade quase ilimitada – recursos sob demanda estão disponíveis para atender às suas necessidades de negócios.
- Alta confiabilidade – uma ampla rede de servidores assegura contra falhas.

### O que é nuvem privada?
Uma nuvem privada consiste em recursos de computação usados exclusivamente por uma única empresa ou organização. A nuvem privada pode estar localizada fisicamente no datacenter local da sua organização ou pode ser hospedada por um provedor de serviços terceirizado. Mas em uma nuvem privada, os serviços e a infraestrutura são sempre mantidos na rede privada e o hardware e o software são dedicados unicamente à sua organização. Dessa forma, com a nuvem privada é mais fácil para que a organização personalize seus recursos a fim de atender a requisitos de TI específicos. As nuvens privadas geralmente são usadas por órgãos governamentais, instituições financeiras e outras organizações de grande porte com operações críticas para os negócios, que buscam melhorar o controle sobre seu ambiente.

**Vantagens das nuvens privadas:**
- Maior flexibilidade – sua organização pode personalizar seu ambiente de nuvem para atender a necessidades de negócios específicas.
- Segurança aprimorada – os recursos não são compartilhados com outros usuários, portanto, é possível um nível maior de controle e segurança.
- Alta escalabilidade – as nuvens privadas também proporcionam a escalabilidade e a eficiência de uma nuvem pública.

### O que é uma nuvem híbrida?
Geralmente chamadas de “o melhor dos dois mundos”, as nuvens híbridas combinam a infraestrutura local, ou seja, as nuvens privadas, com as nuvens públicas, permitindo que as organizações aproveitem as vantagens de ambas as opções. Em uma nuvem híbrida, dados e aplicativos podem ser movidos entre as nuvens públicas e privadas, o que oferece maior flexibilidade e mais opções de implantação. Por exemplo, você pode usar a nuvem pública para necessidades de volume grande e segurança mais baixa, como email baseado na Web, e a nuvem privada (ou outra infraestrutura local) para operações confidenciais críticas, como relatórios financeiros. Em uma nuvem híbrida, o “cloud bursting” também é uma opção. “Cloud bursting” ocorre quando um aplicativo ou recurso é executado na nuvem privada até que haja um pico de demanda (por exemplo, um evento sazonal como compras online ou envio de impostos) e, nesse ponto, a organização pode “estourar” para a nuvem pública para fazer uso de recursos de computação adicionais.

**Vantagens das nuvens híbridas:**
- Controle – sua organização pode manter uma infraestrutura privada para ativos confidenciais.
- Flexibilidade – você poderá usufruir de recursos adicionais na nuvem pública sempre que precisar deles.
- Custo-benefício – com a capacidade de escalar para a nuvem pública, você paga por potência de computação adicional somente quando necessário.
- Facilidade – a transição para a nuvem não precisa ser turbulenta porque você pode migrar gradualmente, passando as cargas de trabalho ao longo do tempo.

## PPT para Download
- [Download PPT da apresentação]()
## Links

### Links da apresentação

### Cloud Providers
- [Amazon AWS]()
- [Microsoft Azure]()
- [Google Cloud Platform - GCP]()
- [Oracle Cloud - OCI]()
- [Alibaba Cloud]()
- [IBM Cloud]()

### Free Accounts

**Google Cloud Platform**

- App Engine - 28 frontend instance hours per day, 9 backend instance hours per day
- Cloud Firestore - 1GB storage, 50,000 reads, 20,000 writes, 20,000 deletes per day
- Compute Engine - 1 non-preemptible f1-micro, 30GB HDD, 5GB snapshot storage (restricted to certain regions)
- Cloud Storage - 5GB, 1GB network egress
- Cloud Shell - Web-based Linux shell/basic IDE with 5GB of persistent storage. 60 hours limit per week
- Cloud Pub/Sub - 10GB of messages per month
- Cloud Functions - 2 million invocations per month (includes both background and HTTP invocations)
- Cloud Run - 2 million requests per month, 360,000 GB-seconds memory, 180,000 vCPU-seconds of compute time, 1 GB network egress from North America per month
- Google Kubernetes Engine - No cluster management fee for clusters of all sizes. Each user node is charged at standard Compute Engine pricing
- BigQuery - 1 TB of querying per month, 10 GB of storage each month
- Cloud Build - 120 build-minutes per day
- Cloud Source Repositories - Up to 5 Users, 50 GB Storage, 50 GB Egress
Full, detailed list - https://cloud.google.com/free/docs/gcp-free-tier#always-free-usage-limits

**Amazon Web Services**

Amazon DynamoDB - 25GB NoSQL DB
Amazon Lambda - 1 Million requests per month
Amazon SNS - 1 million publishes per month
Amazon Cloudwatch - 10 custom metrics and 10 alarms
Amazon Glacier - 10GB long-term object storage
Amazon SQS - 1 million messaging queue requests
Amazon CodeBuild - 100min of build time per month
Amazon Code Commit - 5 active users per month
Amazon Code Pipeline - 1 active pipeline per month
Full, detailed list - https://aws.amazon.com/free/?awsf.Free%20Tier%20Types=categories%23alwaysfree
Microsoft Azure

App service - 10 web, mobile or API apps
Functions - 1 million requests per month
DevTest Labs - Enable fast, easy, and lean dev-test environments
Active Directory - 500,000 objects
Active Directory B2C - 50,000 monthly stored users
Azure DevOps - 5 active users
Microsoft IoT Hub - 8,000 messages per day
Load Balancer - 1 free public load balanced IP (VIP)
Notification Hubs - 1 million push notifications
Bandwidth - 5GB egress per month
Azure Cosmos DB - 5GB storage and 400 RUs of provisioned throughput for 1 year
Full, detailed list - https://azure.microsoft.com/en-us/free/
Oracle Cloud

Compute - 2 VM.Standard.E2.1.Micro 1GB RAM
Block Volume - 2 volumes, 100 GB total (used for compute)
Object Storage - 10 GB
Load balancer - 1 instance with 10 Mbps
Databases - 2 DBs, 20 GB each
Monitoring - 500 million ingestion datapoints, 1 billion retrieval datapoints
Bandwidth - 10TB egress per month
Notifications - 1 million delivery options per month, 1000 emails sent per month
Full, detailed list - https://www.oracle.com/cloud/free/
IBM Cloud

Cloud Functions - 5 million executions per month
Object Storage - 25GB per month
Cloudant database - 1 GB of data storage
Db2 database - 100MB of data storage
API Connect - 50,000 API calls per month
Availability Monitoring - 3 million data points per month
Log Analysis - 500MB of daily log
Full, detailed list - https://www.ibm.com/cloud/free/
Alibaba Cloud

Compute - 1 ecs.t5-lc1m1.small for 12 months with 40 GB ultra cloud disk or SSD disk and 1 MB internet bandwidth.
Function Compute - 1 million calls free each month, 400,000 GB-seconds free each month
API Gateway - For the 1st year you activate API Gateway, you get 1 million free calls each month.
.tech Domain Name - Free to use for one year
Full, detailed list - https://www.alibabacloud.com/campaign/free-trial
### Outros Links
