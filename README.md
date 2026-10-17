# Computação em Nuvem e Virtualização — Aulas

Material didático da disciplina **Computação em Nuvem e Virtualização (CNVI)**
do **Curso Técnico em Redes de Computadores** do **IFSP — Câmpus Boituva**.

- **Professor:** Ricardo Pasquati Pontarolli
- **Contato:** pasquati@ifsp.edu.br
- **Carga horária:** 60 h — 2 aulas por semana
- **Formato das aulas:** slides em PDF (Beamer) gerados a partir de fontes Quarto/Markdown

---

## Como usar este repositório

As aulas estão na pasta [`aulas/`](aulas/), organizadas em **40 semanas** (`s01` a `s40`). Cada **semana** reúne as **2 aulas** do período num único arquivo.

- Para **estudar**, abra o arquivo **`.pdf`** da semana (ex.: [`aulas/s01.pdf`](aulas/s01.pdf)).
- Cada semana também tem a **fonte editável** `.qmd` (mesmo nome), para quem quiser adaptar o conteúdo.
- As **avaliações** (`.gift`, com gabarito) ficam na pasta `aulas/` junto das aulas e **não** são publicadas.

> Dica: no GitHub, clique no arquivo `.pdf` e depois em **Download** para abrir os slides.

---

## Plano de Ensino

> Baseado no **Plano de Ensino** e no **Plano de Aulas** do PPC do curso (arquivos `BTVCNVI.pdf` e `plano-de-aula.pdf`).

### Identificação

| Campo | Valor |
|---|---|
| Curso | Técnico em Redes de Computadores Integrado ao Ensino Médio |
| Componente curricular | Computação em Nuvem e Virtualização |
| Tipo | Obrigatório/Técnica |
| Núcleo | NET |
| Série | 3º |
| Sigla | BTVCNVI |
| Aulas semanais | 2 |
| Total de aulas | 80 |
| Carga horária presencial | 60 h |
| Carga horária em laboratório | 60 h |
| Docentes | Felipe Alexandre Cardoso Pazinatto · Andre Luyde da Silva Souza · Ricardo Pasquati Pontarolli |

### Conhecimentos essenciais do currículo de referência

Programação/Redes de Computadores.

### Ementa

O componente curricular apresenta como os novos modelos de infraestruturas e arquiteturas em TI, com ênfase para a computação em nuvem e virtualização, podem afetar os negócios de uma empresa. Também contempla os fundamentos da computação em nuvem associados à governança em TI.

### Objetivos

- Compreender os aspectos principais relacionados ao funcionamento de máquinas virtuais e computação em nuvem, além de suas relações e impactos com os negócios de uma empresa;
- Empregar técnicas de virtualização;
- Configurar e utilizar máquinas virtuais e sistemas operacionais;
- Identificar e compartilhar equipamentos, periféricos e programas necessários ao estabelecimento do processo de interação com o usuário final;
- Diferenciar, analisar e organizar diferentes tipos de virtualização;
- Compreender a importância da sustentabilidade para a área de tecnologia da informação;
- Planejar e avaliar a computação em nuvem.

### Conteúdo Programático

- Análise do uso de técnicas de virtualização em infraestrutura de TI;
- Apresentação dos principais dispositivos para comunicação e armazenamento;
- Estudo de novos modelos de infraestrutura: grades computacionais e computação em nuvem;
- Conceitos e fundamentos de TI verde;
- Virtualização em Data Centers: conceitos básicos e normas, modelos de virtualização, organização de Data Centers, consolidação de serviços, VMware e Xen;
- Computação em Nuvem: conceitos básicos e normas, modelos de serviço e implantação, arquitetura de referência NIST, Amazon Web Services/Azure/Google Cloud/outros, OpenStack, análise de soluções de nuvem selecionadas.

### Avaliação

O sistema avaliativo é embasado em **duas atividades avaliativas por bimestre**, postadas no **Moodle** (questões de múltipla escolha e/ou dissertativas), disponíveis por período não superior a 24 horas, além de uma **avaliação bimestral**. A nota final corresponde à **média ponderada** (pesos diferentes) entre todas as atividades. Aprovação: **MF ≥ 6,0** e frequência às aulas (FA) **≥ 75%**.

### Bibliografia Básica

- CHEE, Brian J. S.; FRANKLIN, Curtis Junior. *Computação em Nuvem: cloud computing — tecnologias e estratégias*. 1. ed. São Paulo: M Books, 2013. ISBN 8576802074.

### Bibliografia Complementar

- OLIVEIRA, Rômulo Silva; CARISSIMI, Alexandre da Silva; TOSCANI, Simão Sirineo. *Sistemas operacionais*. 4. ed. Porto Alegre: Bookman, 2010.
- SILVA, Robson Santos da. *Ambientes virtuais e multiplataformas online na EAD*. São Paulo: Novatec, 2015. ISBN 9788575224434.
- VELTE, Anthony T.; VELTE, Toby J.; ELSENPETER, Robert. *Cloud computing: computação em nuvem — uma abordagem prática*. 1. ed. Rio de Janeiro: Alta Books, 2011. ISBN 8576085364.
- VERAS, Manoel. *Virtualização: componente central do datacenter*. Rio de Janeiro: Brasport, 2011.

---

## Conteúdo por Bimestre

Cronograma com **64 aulas de conteúdo** (16 por bimestre), organizadas em **32 semanas de 2 aulas** cada, e **8 avaliações** (2 por bimestre), em formato **GIFT** para importação no Moodle (10 questões cada).

### 1º Bimestre — Fundamentos, Modelos de Serviço e Virtualização

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 1:** Apresentação da Disciplina · **Aula 2:** Introdução à computação em nuvem | [s01](aulas/s01.pdf) | [.qmd](aulas/s01.qmd) |
| 2 | **Aula 3:** Como a Nuvem Funciona · **Aula 4:** Atividade: Computação em Nuvem | [s02](aulas/s02.pdf) | [.qmd](aulas/s02.qmd) |
| 3 | **Aula 5:** Modelos de Serviço em Nuvem · **Aula 6:** IaaS: Infraestrutura como Serviço | [s03](aulas/s03.pdf) | [.qmd](aulas/s03.qmd) |
| 4 | **Aula 7:** PaaS: Plataforma como Serviço · **Aula 8:** SaaS: Software como Serviço | [s04](aulas/s04.pdf) | [.qmd](aulas/s04.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s05-avaliacao-1.gift` |
| 6 | **Aula 9:** Comparativo: IaaS × PaaS × SaaS · **Aula 10:** Modelos de Implantação em Nuvem | [s06](aulas/s06.pdf) | [.qmd](aulas/s06.qmd) |
| 7 | **Aula 11:** Atividade: Modelos de Serviço e Implantação · **Aula 12:** Virtualização: Conceitos e Fundamentos | [s07](aulas/s07.pdf) | [.qmd](aulas/s07.qmd) |
| 8 | **Aula 13:** Tipos de Virtualização · **Aula 14:** Virtualização na Nuvem | [s08](aulas/s08.pdf) | [.qmd](aulas/s08.qmd) |
| 9 | **Aula 15:** Data Centers e Infraestrutura · **Aula 16:** Atividade: Virtualização e Data Centers | [s09](aulas/s09.pdf) | [.qmd](aulas/s09.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s10-avaliacao-2.gift` |

### 2º Bimestre — Hipervisores, Máquinas Virtuais, Segurança e Contêineres

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 17:** Hipervisores: conceitos e tipos · **Aula 18:** Criação e Gerenciamento de Máquinas Virtuais | [s11](aulas/s11.pdf) | [.qmd](aulas/s11.qmd) |
| 2 | **Aula 19:** Prática: VirtualBox — Criando a Primeira VM · **Aula 20:** Prática: Instalando um Sistema Convidado | [s12](aulas/s12.pdf) | [.qmd](aulas/s12.qmd) |
| 3 | **Aula 21:** Atividade: Máquinas Virtuais · **Aula 22:** Alta Disponibilidade e Mobilidade de VMs | [s13](aulas/s13.pdf) | [.qmd](aulas/s13.qmd) |
| 4 | **Aula 23:** Segurança em Nuvem: Fundamentos · **Aula 24:** Segurança: Identidade, Acesso e Criptografia | [s14](aulas/s14.pdf) | [.qmd](aulas/s14.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s15-avaliacao-1.gift` |
| 6 | **Aula 25:** Segurança em Nuvem: Soluções e Boas Práticas · **Aula 26:** Atividade: Segurança em Nuvem | [s16](aulas/s16.pdf) | [.qmd](aulas/s16.qmd) |
| 7 | **Aula 27:** Modelos de Gerenciamento em Nuvem · **Aula 28:** Contêineres: Conceitos e VM × Contêiner | [s17](aulas/s17.pdf) | [.qmd](aulas/s17.qmd) |
| 8 | **Aula 29:** Docker: Conceitos e Arquitetura · **Aula 30:** Práticas com Docker: imagens, contêineres, volumes e redes | [s18](aulas/s18.pdf) | [.qmd](aulas/s18.qmd) |
| 9 | **Aula 31:** Atividade: Contêineres e Docker · **Aula 32:** Orquestração de Contêineres com Kubernetes | [s19](aulas/s19.pdf) | [.qmd](aulas/s19.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s20-avaliacao-2.gift` |

### 3º Bimestre — Big Data, Redes em Nuvem e Serverless

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 33:** Revisão e Prática de Kubernetes · **Aula 34:** Computação em nuvem para Big Data | [s21](aulas/s21.pdf) | [.qmd](aulas/s21.qmd) |
| 2 | **Aula 35:** Machine Learning na Nuvem · **Aula 36:** Prática: Big Data e ML na Nuvem | [s22](aulas/s22.pdf) | [.qmd](aulas/s22.qmd) |
| 3 | **Aula 37:** Atividade: Big Data e Machine Learning · **Aula 38:** Redes em Nuvem: Conceitos | [s23](aulas/s23.pdf) | [.qmd](aulas/s23.qmd) |
| 4 | **Aula 39:** VPC, Sub-redes e Conectividade Híbrida · **Aula 40:** Atividade: Redes em Nuvem | [s24](aulas/s24.pdf) | [.qmd](aulas/s24.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s25-avaliacao-1.gift` |
| 6 | **Aula 41:** Prática: Redes Virtuais em Nuvem · **Aula 42:** Computação sem Servidor (Serverless) | [s26](aulas/s26.pdf) | [.qmd](aulas/s26.qmd) |
| 7 | **Aula 43:** Serverless: Funções, Eventos e Provedores · **Aula 44:** Atividade: Computação sem Servidor | [s27](aulas/s27.pdf) | [.qmd](aulas/s27.qmd) |
| 8 | **Aula 45:** Grades Computacionais · **Aula 46:** TI Verde e Sustentabilidade | [s28](aulas/s28.pdf) | [.qmd](aulas/s28.qmd) |
| 9 | **Aula 47:** Edge Computing e Internet das Coisas · **Aula 48:** VMware e Xen em Data Centers | [s29](aulas/s29.pdf) | [.qmd](aulas/s29.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s30-avaliacao-2.gift` |

### 4º Bimestre — Banco de Dados, DevOps, Provedores e Projeto Integrador

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 49:** Serviços de Banco de Dados em Nuvem · **Aula 50:** Bancos Gerenciados: RDS e NoSQL | [s31](aulas/s31.pdf) | [.qmd](aulas/s31.qmd) |
| 2 | **Aula 51:** Prática: Banco de Dados Gerenciado · **Aula 52:** Cloud DevOps: Conceitos | [s32](aulas/s32.pdf) | [.qmd](aulas/s32.qmd) |
| 3 | **Aula 53:** Integração e Entrega Contínua (CI/CD) · **Aula 54:** Prática: Pipeline CI/CD | [s33](aulas/s33.pdf) | [.qmd](aulas/s33.qmd) |
| 4 | **Aula 55:** Atividade: Cloud DevOps e CI/CD · **Aula 56:** Provedores: Amazon Web Services (AWS) | [s34](aulas/s34.pdf) | [.qmd](aulas/s34.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s35-avaliacao-1.gift` |
| 6 | **Aula 57:** Provedores: Microsoft Azure · **Aula 58:** Provedores: Google Cloud Platform e OpenStack | [s36](aulas/s36.pdf) | [.qmd](aulas/s36.qmd) |
| 7 | **Aula 59:** Análise de Soluções de Nuvem · **Aula 60:** Governança e FinOps na Nuvem | [s37](aulas/s37.pdf) | [.qmd](aulas/s37.qmd) |
| 8 | **Aula 61:** Projeto Integrador: Planejamento · **Aula 62:** Projeto Integrador: Desenvolvimento | [s38](aulas/s38.pdf) | [.qmd](aulas/s38.qmd) |
| 9 | **Aula 63:** Projeto Integrador: Apresentação · **Aula 64:** Encerramento e Avaliação Final | [s39](aulas/s39.pdf) | [.qmd](aulas/s39.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s40-avaliacao-2.gift` |

---


## Estrutura do repositório

```
.
├── README.md            # este arquivo (inclui o cronograma)
└── aulas/
    ├── s01.pdf         # slides da semana (para estudar)
    ├── s01.qmd         # fonte editável (Quarto/Markdown)
    ├── s05-avaliacao-1.gift      # avaliações (não publicadas)
    ├── images/         # ilustrações e diagramas
    └── ...
```

## Observações

- As **fontes** `.qmd` permitem editar o conteúdo e gerar novamente os PDFs com o Quarto.
- As aulas são apresentadas em **PDF (Beamer)** para leitura simples e impressão.
- Dúvidas e sugestões: fale com o professor.

## Licença

Material didático do IFSP. Uso educacional.
