# Computação em Nuvem e Virtualização — Aulas

Material didático da disciplina **Computação em Nuvem e Virtualização (CNVI)**
do **Curso Técnico em Redes de Computadores** do **IFSP — Câmpus Boituva**.

- **Professor:** Ricardo Pasquati Pontarolli
- **Contato:** pasquati@ifsp.edu.br
- **Carga horária:** 60 h — 2 aulas por semana
- **Formato das aulas:** slides em PDF (Beamer) gerados a partir de fontes Quarto/Markdown

---

## Como usar este repositório

As aulas estão na pasta [`aulas/`](aulas/), numeradas de **01 a 80**.

- Para **estudar**, abra o arquivo **`.pdf`** da aula (ex.: [`aulas/aula-01.pdf`](aulas/aula-01.pdf)).
- Cada aula também tem a **fonte editável** `.qmd` (mesmo nome), para quem quiser adaptar o conteúdo.
- As **avaliações** (`.gift`, com gabarito) ficam na pasta `aulas/` junto das aulas e **não** são publicadas.

> Dica: no GitHub, clique no arquivo `.pdf` e depois em **Download** para abrir os slides.

---

## Conteúdo por Bimestre

Cronograma com **72 aulas de conteúdo** (18 por bimestre) e **8 avaliações** (2 por bimestre), em formato **GIFT** para importação no Moodle (10 questões cada).

> As aulas são apresentações **Beamer (PDF)** geradas a partir das fontes `.qmd`.
> As avaliações (`.gift`) ficam na pasta `aulas/` e **não** são publicadas.

### 1º Bimestre — Fundamentos, Modelos de Serviço e Virtualização

| # | Aula | PDF | Fonte (.qmd) |
|---|---|-----|-----|
| 01 | Apresentação da disciplina e critérios de avaliação | [aula-01](aulas/aula-01.pdf) | [.qmd](aulas/aula-01-apresentacao-disciplina.qmd) |
| 02 | Introdução à computação em nuvem — Parte 1 (história e evolução) | [aula-02](aulas/aula-02.pdf) | [.qmd](aulas/aula-02-introducao-nuvem-parte-1.qmd) |
| 03 | Introdução à computação em nuvem — Parte 2 (definição e características) | [aula-03](aulas/aula-03.pdf) | [.qmd](aulas/aula-03-introducao-nuvem-parte-2.qmd) |
| 04 | Como a nuvem funciona: data centers, virtualização e elasticidade | [aula-04](aulas/aula-04.pdf) | [.qmd](aulas/aula-04-como-a-nuvem-funciona.qmd) |
| 05 | Atividade — Computação em Nuvem | [aula-05](aulas/aula-05.pdf) | [.qmd](aulas/aula-05-atividade-computacao-em-nuvem.qmd) |
| 06 | Modelos de serviço em nuvem — visão geral e a pilha | [aula-06](aulas/aula-06.pdf) | [.qmd](aulas/aula-06-modelos-de-servico-visao-geral.qmd) |
| 07 | IaaS — Infraestrutura como Serviço | [aula-07](aulas/aula-07.pdf) | [.qmd](aulas/aula-07-iaas-infraestrutura-como-servico.qmd) |
| 08 | PaaS — Plataforma como Serviço | [aula-08](aulas/aula-08.pdf) | [.qmd](aulas/aula-08-paas-plataforma-como-servico.qmd) |
| 09 | SaaS — Software como Serviço | [aula-09](aulas/aula-09.pdf) | [.qmd](aulas/aula-09-saas-software-como-servico.qmd) |
| 10 | **Avaliação 1 (GIFT, 10 questões)** | — | `aula-10-avaliacao-b1-av1.gift` |
| 11 | Comparativo IaaS × PaaS × SaaS e o Serverless | [aula-11](aulas/aula-11.pdf) | [.qmd](aulas/aula-11-comparativo-iaas-paas-saas.qmd) |
| 12 | Modelos de implantação: pública, privada e híbrida | [aula-12](aulas/aula-12.pdf) | [.qmd](aulas/aula-12-modelos-de-implantacao.qmd) |
| 13 | Atividade — Modelos de Serviço e Implantação | [aula-13](aulas/aula-13.pdf) | [.qmd](aulas/aula-13-atividade-modelos-de-servico.qmd) |
| 14 | Virtualização: conceitos e fundamentos | [aula-14](aulas/aula-14.pdf) | [.qmd](aulas/aula-14-virtualizacao-conceitos.qmd) |
| 15 | Tipos de virtualização | [aula-15](aulas/aula-15.pdf) | [.qmd](aulas/aula-15-tipos-de-virtualizacao.qmd) |
| 16 | Virtualização na nuvem: benefícios e desafios | [aula-16](aulas/aula-16.pdf) | [.qmd](aulas/aula-16-virtualizacao-na-nuvem.qmd) |
| 17 | Data centers e organização da infraestrutura | [aula-17](aulas/aula-17.pdf) | [.qmd](aulas/aula-17-data-centers.qmd) |
| 18 | Atividade — Virtualização e Data Centers | [aula-18](aulas/aula-18.pdf) | [.qmd](aulas/aula-18-atividade-virtualizacao-data-centers.qmd) |
| 19 | Revisão para a avaliação bimestral | [aula-19](aulas/aula-19.pdf) | [.qmd](aulas/aula-19-revisao-bimestre-1.qmd) |
| 20 | **Avaliação 2 (GIFT, 10 questões)** | — | `aula-20-avaliacao-b1-av2.gift` |

### 2º Bimestre — Hipervisores, Máquinas Virtuais, Segurança e Contêineres

| # | Aula | PDF | Fonte (.qmd) |
|---|---|-----|-----|
| 21 | Hipervisores: conceitos e funcionamento | [aula-21](aulas/aula-21.pdf) | [.qmd](aulas/aula-21-hipervisores-conceitos.qmd) |
| 22 | Hipervisores tipo 1 × tipo 2 | [aula-22](aulas/aula-22.pdf) | [.qmd](aulas/aula-22-hipervisores-tipo-1-e-2.qmd) |
| 23 | Criação e gerenciamento de máquinas virtuais | [aula-23](aulas/aula-23.pdf) | [.qmd](aulas/aula-23-gerenciamento-de-vms.qmd) |
| 24 | Prática: VirtualBox — criando a primeira VM | [aula-24](aulas/aula-24.pdf) | [.qmd](aulas/aula-24-pratica-virtualbox.qmd) |
| 25 | Prática: instalando e configurando um SO convidado | [aula-25](aulas/aula-25.pdf) | [.qmd](aulas/aula-25-pratica-so-convidado.qmd) |
| 26 | Atividade — Máquinas Virtuais | [aula-26](aulas/aula-26.pdf) | [.qmd](aulas/aula-26-atividade-maquinas-virtuais.qmd) |
| 27 | Alta disponibilidade e mobilidade de VMs | [aula-27](aulas/aula-27.pdf) | [.qmd](aulas/aula-27-alta-disponibilidade-vms.qmd) |
| 28 | Segurança em nuvem: fundamentos | [aula-28](aulas/aula-28.pdf) | [.qmd](aulas/aula-28-seguranca-em-nuvem-fundamentos.qmd) |
| 29 | Segurança em nuvem: identidade, acesso e criptografia | [aula-29](aulas/aula-29.pdf) | [.qmd](aulas/aula-29-seguranca-identidade-criptografia.qmd) |
| 30 | **Avaliação 1 (GIFT, 10 questões)** | — | `aula-30-avaliacao-b2-av1.gift` |
| 31 | Segurança em nuvem: soluções e boas práticas | [aula-31](aulas/aula-31.pdf) | [.qmd](aulas/aula-31-seguranca-solucoes-boas-praticas.qmd) |
| 32 | Atividade — Segurança em Nuvem | [aula-32](aulas/aula-32.pdf) | [.qmd](aulas/aula-32-atividade-seguranca-em-nuvem.qmd) |
| 33 | Modelos de gerenciamento em nuvem | [aula-33](aulas/aula-33.pdf) | [.qmd](aulas/aula-33-modelos-de-gerenciamento-nuvem.qmd) |
| 34 | Contêineres: conceitos e VM × contêiner | [aula-34](aulas/aula-34.pdf) | [.qmd](aulas/aula-34-containers-conceitos.qmd) |
| 35 | Docker: conceitos e arquitetura | [aula-35](aulas/aula-35.pdf) | [.qmd](aulas/aula-35-docker-arquitetura.qmd) |
| 36 | Prática: Docker 1 — imagens e contêineres | [aula-36](aulas/aula-36.pdf) | [.qmd](aulas/aula-36-pratica-docker-1.qmd) |
| 37 | Prática: Docker 2 — volumes e redes | [aula-37](aulas/aula-37.pdf) | [.qmd](aulas/aula-37-pratica-docker-2.qmd) |
| 38 | Atividade — Contêineres e Docker | [aula-38](aulas/aula-38.pdf) | [.qmd](aulas/aula-38-atividade-containers-docker.qmd) |
| 39 | Orquestração de contêineres com Kubernetes | [aula-39](aulas/aula-39.pdf) | [.qmd](aulas/aula-39-orquestracao-kubernetes.qmd) |
| 40 | **Avaliação 2 (GIFT, 10 questões)** | — | `aula-40-avaliacao-b2-av2.gift` |

### 3º Bimestre — Big Data, Redes em Nuvem e Serverless

| # | Aula | PDF | Fonte (.qmd) |
|---|---|-----|-----|
| 41 | Revisão e prática de Kubernetes | [aula-41](aulas/aula-41.pdf) | [.qmd](aulas/aula-41-revisao-pratica-kubernetes.qmd) |
| 42 | Computação em nuvem para Big Data — Parte 1 | [aula-42](aulas/aula-42.pdf) | [.qmd](aulas/aula-42-big-data-na-nuvem-parte-1.qmd) |
| 43 | Computação em nuvem para Big Data — Parte 2 | [aula-43](aulas/aula-43.pdf) | [.qmd](aulas/aula-43-big-data-na-nuvem-parte-2.qmd) |
| 44 | Machine Learning na nuvem | [aula-44](aulas/aula-44.pdf) | [.qmd](aulas/aula-44-machine-learning-na-nuvem.qmd) |
| 45 | Prática: serviços de Big Data e ML na nuvem | [aula-45](aulas/aula-45.pdf) | [.qmd](aulas/aula-45-pratica-big-data-ml.qmd) |
| 46 | Atividade — Big Data e Machine Learning | [aula-46](aulas/aula-46.pdf) | [.qmd](aulas/aula-46-atividade-big-data-ml.qmd) |
| 47 | Redes em nuvem: conceitos | [aula-47](aulas/aula-47.pdf) | [.qmd](aulas/aula-47-redes-em-nuvem-conceitos.qmd) |
| 48 | Redes em nuvem: VPC, sub-redes e conectividade híbrida | [aula-48](aulas/aula-48.pdf) | [.qmd](aulas/aula-48-redes-vpc-sub-redes.qmd) |
| 49 | Atividade — Redes em Nuvem | [aula-49](aulas/aula-49.pdf) | [.qmd](aulas/aula-49-atividade-redes-em-nuvem.qmd) |
| 50 | **Avaliação 1 (GIFT, 10 questões)** | — | `aula-50-avaliacao-b3-av1.gift` |
| 51 | Configuração de redes virtuais em nuvem (prática) | [aula-51](aulas/aula-51.pdf) | [.qmd](aulas/aula-51-pratica-redes-virtuais.qmd) |
| 52 | Computação sem servidor (Serverless): conceitos | [aula-52](aulas/aula-52.pdf) | [.qmd](aulas/aula-52-serverless-conceitos.qmd) |
| 53 | Serverless: funções, eventos e provedores | [aula-53](aulas/aula-53.pdf) | [.qmd](aulas/aula-53-serverless-funcoes-eventos.qmd) |
| 54 | Atividade — Computação sem Servidor | [aula-54](aulas/aula-54.pdf) | [.qmd](aulas/aula-54-atividade-serverless.qmd) |
| 55 | Grades computacionais: conceitos | [aula-55](aulas/aula-55.pdf) | [.qmd](aulas/aula-55-grades-computacionais.qmd) |
| 56 | TI Verde e sustentabilidade na nuvem | [aula-56](aulas/aula-56.pdf) | [.qmd](aulas/aula-56-ti-verde-sustentabilidade.qmd) |
| 57 | Edge computing e Internet das Coisas | [aula-57](aulas/aula-57.pdf) | [.qmd](aulas/aula-57-edge-computing-iot.qmd) |
| 58 | Virtualização em data centers: VMware e Xen | [aula-58](aulas/aula-58.pdf) | [.qmd](aulas/aula-58-vmware-xen-data-centers.qmd) |
| 59 | Revisão para a avaliação bimestral | [aula-59](aulas/aula-59.pdf) | [.qmd](aulas/aula-59-revisao-bimestre-3.qmd) |
| 60 | **Avaliação 2 (GIFT, 10 questões)** | — | `aula-60-avaliacao-b3-av2.gift` |

### 4º Bimestre — Banco de Dados, DevOps, Provedores e Projeto Integrador

| # | Aula | PDF | Fonte (.qmd) |
|---|---|-----|-----|
| 61 | Implementação de serviços de banco de dados em nuvem | [aula-61](aulas/aula-61.pdf) | [.qmd](aulas/aula-61-bancos-de-dados-em-nuvem.qmd) |
| 62 | Bancos gerenciados: RDS e NoSQL | [aula-62](aulas/aula-62.pdf) | [.qmd](aulas/aula-62-banco-gerenciado-rds-nosql.qmd) |
| 63 | Prática: banco de dados gerenciado na nuvem | [aula-63](aulas/aula-63.pdf) | [.qmd](aulas/aula-63-pratica-banco-de-dados-nuvem.qmd) |
| 64 | Cloud DevOps: conceitos | [aula-64](aulas/aula-64.pdf) | [.qmd](aulas/aula-64-cloud-devops-conceitos.qmd) |
| 65 | Integração e entrega contínua (CI/CD) | [aula-65](aulas/aula-65.pdf) | [.qmd](aulas/aula-65-cicd-integracao-continua.qmd) |
| 66 | Prática: pipeline CI/CD | [aula-66](aulas/aula-66.pdf) | [.qmd](aulas/aula-66-pratica-pipeline-cicd.qmd) |
| 67 | Atividade — Cloud DevOps e Integração Contínua | [aula-67](aulas/aula-67.pdf) | [.qmd](aulas/aula-67-atividade-cloud-devops.qmd) |
| 68 | Provedores: AWS — visão geral | [aula-68](aulas/aula-68.pdf) | [.qmd](aulas/aula-68-provedores-aws.qmd) |
| 69 | Provedores: Microsoft Azure | [aula-69](aulas/aula-69.pdf) | [.qmd](aulas/aula-69-provedores-azure.qmd) |
| 70 | **Avaliação 1 (GIFT, 10 questões)** | — | `aula-70-avaliacao-b4-av1.gift` |
| 71 | Provedores: Google Cloud Platform | [aula-71](aulas/aula-71.pdf) | [.qmd](aulas/aula-71-provedores-gcp.qmd) |
| 72 | Provedores: OpenStack | [aula-72](aulas/aula-72.pdf) | [.qmd](aulas/aula-72-provedores-openstack.qmd) |
| 73 | Análise de soluções de nuvem selecionadas | [aula-73](aulas/aula-73.pdf) | [.qmd](aulas/aula-73-analise-solucoes-nuvem.qmd) |
| 74 | Governança em TI e custos na nuvem (FinOps) | [aula-74](aulas/aula-74.pdf) | [.qmd](aulas/aula-74-governanca-finops.qmd) |
| 75 | Projeto integrador — planejamento | [aula-75](aulas/aula-75.pdf) | [.qmd](aulas/aula-75-projeto-integrador-planejamento.qmd) |
| 76 | Projeto integrador — desenvolvimento | [aula-76](aulas/aula-76.pdf) | [.qmd](aulas/aula-76-projeto-integrador-desenvolvimento.qmd) |
| 77 | Projeto integrador — apresentação | [aula-77](aulas/aula-77.pdf) | [.qmd](aulas/aula-77-projeto-integrador-apresentacao.qmd) |
| 78 | Revisão geral do curso | [aula-78](aulas/aula-78.pdf) | [.qmd](aulas/aula-78-revisao-geral-curso.qmd) |
| 79 | Encerramento e avaliação final | [aula-79](aulas/aula-79.pdf) | [.qmd](aulas/aula-79-encerramento-avaliacao-final.qmd) |
| 80 | **Avaliação 2 (GIFT, 10 questões)** | — | `aula-80-avaliacao-b4-av2.gift` |

---

## Estrutura do repositório

```
.
├── README.md            # este arquivo (inclui o cronograma)
└── aulas/
    ├── aula-01.pdf      # slides (para estudar)
    ├── aula-01-*.qmd     # fonte editável (Quarto/Markdown)
    ├── aula-NN-avaliacao-*.gift  # avaliações (não publicadas)
    ├── images/          # ilustrações e diagramas
    └── ...
```

## Observações

- As **fontes** `.qmd` permitem editar o conteúdo e gerar novamente os PDFs com o Quarto.
- As aulas são apresentadas em **PDF (Beamer)** para leitura simples e impressão.
- Dúvidas e sugestões: fale com o professor.

## Licença

Material didático do IFSP. Uso educacional.
