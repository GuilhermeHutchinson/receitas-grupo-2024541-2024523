\# 📊 Relatório Final - Projeto Colaborativo de Receitas



\*\*Disciplina:\*\* Git e GitHub - 2025  

\*\*Professor:\*\* Alex Steil  

\*\*Data de Entrega: 3 Dezembro 2025



---



\## 👥 Identificação do Grupo



| Nome | Número de Aluno | GitHub Username |

|------|----------------|-----------------|

| Guilherme Hutchinson | 2024541 | @GuilhermeHutchinson |

| Martim Pinto | 2024523 | @maErHelloworld |



\*\*Repositório:\*\* https://github.com/GuilhermeHutchinson/receitas-grupo-2024541-2024523



---



\## 📝 Sumário Executivo



Este projeto teve como objetivo aplicar práticas de desenvolvimento colaborativo utilizando Git e GitHub. O grupo desenvolveu uma página colaborativa de receitas, onde cada membro contribuiu com receitas individuais e colaborativas, utilizando branches, Pull Requests, Issues e práticas de code review.



---



\## 🎯 Objetivos do Projeto



\### Objetivos Alcançados:

\- ✅ Criar repositório a partir do template do professor

\- ✅ Trabalhar colaborativamente usando Git e GitHub

\- ✅ Utilizar branches para organização do trabalho

\- ✅ Implementar fluxo de Pull Requests e code review

\- ✅ Usar Issues para gestão de tarefas

\- ✅ Resolver conflitos de merge

\- ✅ Documentar o projeto adequadamente

\- ✅ Criar receitas em formato Markdown



---



\## 📚 Receitas Desenvolvidas



\### 1. 🍰 Bolo de Cenoura com Cobertura de Chocolate

\- \*\*Responsável:\*\* Guilherme Hutchinson

\- \*\*Branch:\*\* `feature/bolo-cenoura`

\- \*\*Ficheiro:\*\* `receitas/bolo-cenoura.md`

\- \*\*Descrição:\*\* Receita tradicional portuguesa/brasileira com ingredientes detalhados e modo de preparo completo.

\- \*\*Status:\*\* ✅ Concluída e integrada



\### 2. 🥗 Húmus de Grão-de-Bico (Vegana)

\- \*\*Responsável:\*\* Guilherme Hutchinson

\- \*\*Branch:\*\* `feature/receitas-veganas`

\- \*\*Ficheiro:\*\* `receitas/veganas/humus-grao.md`

\- \*\*Descrição:\*\* Receita vegana do Médio Oriente, rica em proteínas e saudável, com variações e dicas de conservação.

\- \*\*Categoria:\*\* Receita Vegana

\- \*\*Status:\*\* ✅ Concluída e integrada



\### 3. 🍲 Feijoada Tradicional (Colaborativa)

\- \*\*Responsáveis:\*\* 

&nbsp; - Guilherme Hutchinson - Estrutura, ingredientes e introdução

&nbsp; - Martim Pinto - Modo de preparo e finalização

\- \*\*Branches:\*\* 

&nbsp; - `feature/feijoada-colaborativa`

&nbsp; - \*\*Ficheiro:\*\* `receitas/feijoada-colaborativa.md`

\- \*\*Descrição:\*\* Receita colaborativa onde cada membro contribuiu com uma parte específica através de Pull Requests separados.

\- \*\*Status:\*\* ✅ Concluída e integrada





2\. 🧀 Pão de Queijo



Responsável: Martim Pinto



Branch: feature/pao-de-queijo



Ficheiro: receitas/pao-de-queijo.md



Descrição: Receita tradicional brasileira com ingredientes detalhados e modo de preparo completo, incluindo dicas para garantir a textura ideal.



Status: ✅ Concluída e integrada





---



\## 🌿 Organização de Branches



\### Estrutura de Branches Criadas:



```

main (branch principal)

├── feature/bolo-cenoura

├── feature/receitas-veganas

├── feature/feijoada-colaborativa

└── docs/atualizar-readme

```



\### Estratégia Utilizada:

\- \*\*Branch `main`:\*\* Código estável e funcional

\- \*\*Feature branches:\*\* Uma por receita ou funcionalidade

\- \*\*Naming convention:\*\* `feature/nome-da-funcionalidade` ou `docs/nome-do-documento`

\- \*\*Merge strategy:\*\* Pull Requests com code review obrigatório



---



\## 🔄 Pull Requests Realizados



| # | Título | Autor | Branch | Status | Revisado por |

|---|--------|-------|--------|--------|--------------|

| #1 | Adiciona receita de bolo de cenoura | Guilherme | feature/bolo-cenoura → main | ✅ Merged | Martim |

| #2 | Cria categoria veganas com húmus | Guilherme | feature/receitas-veganas → main | ✅ Merged | Martim |

| #3 | \[Colaborativa 1/2] Estrutura feijoada | Guilherme | feature/receita-colaborativa → main | ✅ Merged | Martim |

| #4 | \[Colaborativa 2/2] Modo de preparo | Martim | feature/feijoada-modo-preparo → main | ✅ Merged | Guilherme |

| #5 | Atualiza README completo | Guilherme | docs/atualizar-readme → main | ✅ Merged | Martim |



\*\*Total de Pull Requests:\*\* 5 (5 merged )







\### Issues Criadas:



| # | Título | Tipo | Responsável | Status |

|---|--------|------|-------------|--------|

| #1 | 🍞 Criar receita de pão de queijo | feature | - | ✅ Fechada |

| #2 | 🍰 Criar receita de bolo de cenoura | feature | Guilherme | ✅ Fechada |

| #3 | 📄 Revisar README.md | documentation | Guilherme | ✅ Fechada |

| #4 | 🔧 Padronizar nomes dos arquivos | enhancement | - | ✅ Fechada |

| #5 | 🐛 Corrigir erro de digitação | bug | - | ✅ Fechada |

| #6 | 🥗 Discutir inclusão de receitas veganas | discussion | Guilherme | ✅ Fechada |

| #7 | 🔄 Adicionar receita colaborativa | feature | Ambos |  ✅ Fechada



\*\*Estatísticas:\*\*

\- Total criadas: 7

\- Fechadas: 7



---



\## 🔧 Conflitos Resolvidos



\### 1. Conflito na pasta `src/`

\*\*Situação:\*\* Ficheiro `bolo-cenoura.md` criado incorretamente na pasta `src/` em vez de `receitas/`.



\*\*Resolução:\*\*

```bash

git mv src/bolo-cenoura.md receitas/bolo-cenoura.md

git commit -m "Move bolo-cenoura.md para pasta receitas"

```



\*\*Aprendizagem:\*\* Confirmámos a importância de planear e organizar a estrutura de pastas desde o início,

&nbsp;garantindo que todos os ficheiros estejam no local correto, o que evita conflitos e facilita em muito a colaboração.

achamos que é das etapas mais cruciais para facilitar todo um projeto ao longo da sua criação.

---



\### 2. Ficheiro duplicado em diferentes localizações

\*\*Situação:\*\* `humus-grao.md` existia tanto em `receitas/` como em `receitas/veganas/`.



\*\*Resolução:\*\*

```bash

git mv receitas/humus-grao.md receitas/veganas/humus-grao.md

git commit -m "Move húmus para categoria veganas"

```





