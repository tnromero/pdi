:::mermaid

C[Engenharia de Dados]
C --> C0[Airflow]
C --> C1[PySpark]
C --> C2[AWS Glue Jobs]
C --> C22[AWS Glue DataQuality]
C --> C3[AWS EMR]
C --> C4[OpenTableFormat]
C --> C5[AWS Lake Formation]

C4 --> C41[Iceberg]
C4 --> C42[HUDI]
C4 --> C43[DeltaLake]

D[Mensageria]
D --> D1[Apache Kafka]

E[DevOps]
E --> E1[Terraform]
E --> E2[GitHub Actions]
E --> E3[Técnicas de Deploy]

E3 --> E31[Blue/Green]
E3 --> E32[Canary]
    
C0 --> C111[Treinamentos Alura 1]
C1 --> C112[Treinamentos Alura 2]

:::