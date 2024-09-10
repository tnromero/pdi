# PDI

## Objetivos de Conhecimento

- **PySpark:** Alcançar Nível 4 de proficiência
- **AWS Glue e EMR:** Atingir Nível 3 de conhecimento em ambos
- **Apache Iceberg:** Desenvolver competência de Nível 3
- **HUDI e Delta Lake:** Obter Nível 2 de compreensão em ambos formatos de tabela aberta
- **Técnicas de Deploy:** Dominar conceitos de Nível 2, incluindo Blue/Green e Canary
- **GitHub Actions:** Alcançar Nível 2 de conhecimento
- **Terraform:** Desenvolver Nível 3 de conhecimento
- **Apache Kafka:** Atingir Nível 2 de conhecimento

## Plano de Estudos

```mermaid

graph LR;
    C[Engenharia de Dados];
    C --> C0[Airflow];
    C --> C1[PySpark];
    C --> C2[AWS Glue Jobs];
    C --> C22[AWS Glue DataQuality];
    C --> C3[AWS EMR];
    C --> C4[OpenTableFormat];
    C --> C5[AWS Lake Formation];

    C4 --> C41[Iceberg];
    C4 --> C42[HUDI];
    C4 --> C43[DeltaLake];

    D[Mensageria];
    D --> D1[Apache Kafka];

    E[DevOps];
    E --> E0[Git];
    E --> E1[Terraform];
    E --> E2[GitHub Actions];
    E --> E3[Técnicas de Deploy];

    E3 --> E31[Blue/Green];
    E3 --> E32[Canary];
    
    C0 --> C111[Treinamentos Alura 1];
    C1 --> C112[Treinamentos Alura 2];

```
