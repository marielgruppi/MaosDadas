# Análise dos dados do Portal da Transparência: fontes dos convênios do Mãos Dadas

- **Data:** 29/10/2026
- **Base:** planilhas do branch `Dados`, principalmente `Valores pagos Mãos Dadas por município.xlsx`. Ela foi montada com os dados abertos de MG ("Convênios de saída" e "Despesa pública").
- **Conferência:** recalculei os totais das abas 2, 3 e 4 a partir dos pagamentos de cada convênio, na coluna "Pagamentos (ano: valor – fonte)". Os números **batem centavo a centavo** com a aba 5.

> Esta análise é técnica e não substitui parecer jurídico. Os pontos marcados com **[conferir]** dependem de texto legal que não está no repositório.

---

## 1. O que os dados mostram

### 1.1 Totais pagos por fonte (R$)

| Componente | Fundeb | QESE | Recursos ordinários | Outras | **Total pago** |
|---|---:|---:|---:|---:|---:|
| **Convênios Mãos Dadas** (obras, bens, veículos): 456 convênios | **463.225.877** (46%) | 4.382.730 | 529.905.600 | – | **997.514.208** |
| **Repasse do 1º ano** (absorção de matrículas): 178 convênios | 31.250.571 (9%) | **206.701.120** (57%) | 124.107.358 | 442.090 (FNDE) | **362.501.138** |
| **Fortalecimento das Escolas Municipais** (não é Mãos Dadas) | **105.549.655** | 121.044.527 | 350.502.680 | – | 577.096.861 |
| Outros convênios (emendas etc.) | 8.585.078 | 26.506.370 | 65.856.952 | 2.085.032 | 103.033.432 |

**Fundeb estadual pago em convênios com municípios:** cerca de **R$ 608,6 milhões**:
- R$ 463,2 mi em convênios de investimento do Mãos Dadas;
- R$ 31,3 mi no repasse do 1º ano;
- R$ 105,5 mi no Fortalecimento;
- R$ 8,6 mi em outros convênios.

### 1.2 Quando o Fundeb foi usado
Nos convênios de investimento do Mãos Dadas, **todo o Fundeb foi pago em 2021 (R$ 127,7 mi) e 2022 (R$ 335,6 mi)**. A partir de 2023, os mesmos tipos de convênio passaram a ser pagos com **recursos ordinários**. O Fortalecimento segue o mesmo padrão: Fundeb só em 2022.

### 1.3 Em que o Fundeb foi gasto (convênios de investimento)
A classificação é aproximada, feita pelas palavras do título e do tipo de atendimento:

| Objeto | Fundeb (R$) |
|---|---:|
| Obras em escolas (construção, reforma, ampliação) | ~396,9 mi |
| Mobiliário e equipamentos | ~27,4 mi |
| Veículos / transporte escolar | ~17,6 mi |
| Educação infantil (creches, CMEIs, escolas infantis) | ver abaixo |

- **Maiores convênios pagos com Fundeb:**
  - Betim: R$ 69,7 mi, 8 prédios escolares, 2021;
  - São Joaquim de Bicas: R$ 49,5 mi, 10 escolas;
  - Coronel Fabriciano: R$ 20,2 mi;
  - Ubá: R$ 19,9 mi e R$ 7,0 mi;
  - Mateus Leme: R$ 15,0 mi, **5 escolas infantis**.
- **Educação infantil paga com Fundeb estadual:**
  - pelo menos **R$ 21,3 mi** em convênios só de educação infantil: Mateus Leme, Nepomuceno (2 creches), Desterro de Entre Rios, Aguanil, Perdões, São João do Oriente, playground e parquinho;
  - mais **R$ 13,0 mi** em convênios mistos, de escola com creche: Ribeirão das Neves, Medina, Itaúna e Machacalis.
- Ao todo, o Fundeb aparece em **217 convênios de 104 municípios**.

### 1.4 O "repasse do 1º ano" quase não usou Fundeb
- Os títulos dizem "repasse de recursos do **FUNDEB, QESE e PNAE**", mas o dinheiro saiu majoritariamente de outras fontes:
  - **QESE:** R$ 203,1 mi só em 2022;
  - **recursos ordinários:** R$ 123,2 mi em 2023;
  - **Fundeb:** apenas R$ 31,3 mi;
  - **fonte FNDE (PNAE):** só R$ 442 mil.
- Exemplos de 2022 em que o título fala em Fundeb, QESE e PNAE e **100% foi pago com QESE**: Caeté, Inhapim, Pedra Azul e São João do Oriente.

**Em resumo, há uma inversão:**
- o repasse que o título e a norma dizem ser de **Fundeb** (custeio das matrículas) foi pago principalmente com **QESE e Tesouro**;
- os convênios de **obras e bens**, que a norma trata como apoio facultativo "conforme disponibilidade orçamentária", receberam **R$ 463 mi de Fundeb**.

---

## 2. Questionamentos sobre a legalidade

Abaixo estão os argumentos que sustentam os questionamentos e os contra-argumentos que o Estado provavelmente usaria.

### 2.1 Fundeb estadual transferido a municípios por convênio
- **[conferir] Lei 14.113/2020, art. 21:** os recursos do Fundo são creditados e **executados** nas contas únicas e específicas do ente, **vedada a transferência para outras contas**.
  - No convênio, o dinheiro sai da conta Fundeb do Estado para a **conta do convênio do município**, que não é conta do Fundeb municipal.
  - Assim, o dinheiro sai do controle do Conselho de Acompanhamento do Fundeb (CACS) estadual e não entra no do municipal.
- **[conferir] Lei 14.113/2020, art. 25:** o Fundeb só pode ser usado em MDE da **educação básica pública** pelo próprio ente.
  - Argumento contrário: obras e equipamentos escolares são MDE (LDB, art. 70, II), e o Estado tem dever de colaboração (CF, art. 211, §4º).
  - Argumento a favor do questionamento: a despesa é **do Estado** apenas no papel. Ela custeia escolas que **não são da rede estadual**.
- **Lógica de distribuição:** o Fundeb é distribuído **por matrícula**. Depois da absorção, essas matrículas passam a gerar Fundeb **para o próprio município**. Usar o Fundeb estadual, que é proporcional às matrículas estaduais, para construir escolas municipais é uma **segunda transferência** de recursos do fundo para a rede municipal.

### 2.2 Fundeb estadual em educação infantil
- **[conferir] CF, art. 211, §§2º e 3º, e ADCT, art. 212-A:** o Estado atua prioritariamente no ensino **fundamental e médio**, e os municípios no ensino fundamental e na **educação infantil**. A regra constitucional do Fundeb manda aplicar os recursos no **âmbito de atuação prioritária** de cada ente. Conferir a redação exata.
- Se confirmada, essa regra torna **mais frágil** o pagamento de creches e escolas infantis municipais (≥ R$ 21,3 mi, mais R$ 13,0 mi mistos) com o **Fundeb estadual**. É o ponto mais forte do questionamento.

### 2.3 Concentração do Fundeb em 2021 e 2022
- Os anos coincidem com o início do novo Fundeb, quando a arrecadação subiu muito.
- **Hipótese a verificar:** o Estado pode ter usado convênios com municípios para executar dentro do exercício recursos do Fundeb que, de outro modo, ficariam como saldo.
- **[conferir]** A Lei 14.113, art. 25, §3º, permite deixar até 10% para o 1º quadrimestre do ano seguinte.
- O **parecer prévio do TCE-MG sobre as contas do Governador de 2021 e 2022** deve tratar da aplicação do Fundeb e de saldos. Vale ler.

### 2.4 Repasse do 1º ano pago com QESE
- **[conferir] Lei 9.766/1998, art. 7º:** o salário-educação **não pode pagar pessoal**.
- O 1º ano das matrículas absorvidas é sobretudo **folha de professores**. Os municípios que receberam o repasse do 1º ano só em QESE (a maioria em 2022) **não podiam usá-lo para folha**. Isso deve aparecer nas prestações de contas.
- A Res. SEE 5.148, art. 11, deixa a QESE fora da ressalva de "legislação específica". As regras próprias da QESE continuam valendo de qualquer forma.

### 2.5 "Fundos de MDE" e o mínimo de 25%
- Nos dados, a outra fonte grande é "**Recursos ordinários**", ou seja, o Tesouro sem vinculação. Ela não tem restrição de uso, mas a pergunta é **como o Estado a contabiliza**.
- **[conferir]** Se o Estado computa esses repasses como **sua** despesa em MDE para cumprir os 25% da CF, art. 212, e o município também computa o gasto do mesmo dinheiro, há **dupla contagem**.
- Onde verificar:
  - **RREO, Anexo 8 (demonstrativo de MDE)** do Estado;
  - **SIOPE** (FNDE), para o Estado e para os municípios;
  - entendimento do TCE-MG nos pareceres sobre as contas do Governador.

### 2.6 Outros pontos já levantados
- A Lei Estadual 12.768/1998, base estadual do projeto, ainda fala em **FUNDEF**.
- Nenhum documento do branch `Legislação` autoriza expressamente pagar obras com Fundeb. A Res. 5.148, arts. 4º, IV e 9º, só fala em "disponibilidade financeiro-orçamentária".
- Na planilha de infraestrutura do ANTIGO, o status cita "**após período eleitoral**". Isso indica que a SEE controla a restrição eleitoral dos convênios, mas vale conferir as datas de 2022, 2024 e 2026.

---

## 3. Como achar o Mãos Dadas no orçamento estadual (LOA)

### 3.1 O que procurar
Cada pagamento no SIAFI-MG carrega uma **classificação orçamentária completa**. Os campos que interessam são:

| Campo | O que esperar no Mãos Dadas | Observação |
|---|---|---|
| **Órgão / Unidade orçamentária** | SEE. O nº dos convênios no SIGCON começa com **1261** (ex.: `1261001101/2021`), que deve ser o código da SEE | Confirmar na LOA |
| **Função / Subfunção** | 12 – Educação; 361 – Ensino fundamental; 365 – Educação infantil; 368 – Educação básica | A subfunção 365 nos convênios de creche reforça o ponto 2.2 |
| **Programa e Ação** | O programa e a ação do PPAG em que o Mãos Dadas está. Pode ser uma ação própria ou uma ação genérica de "apoio aos municípios" | **É o campo-chave.** Ele liga o pagamento à LOA |
| **Fonte de recurso** | Fundeb, salário-educação (QESE), recursos ordinários | Desde 2023, MG usa a codificação padronizada da STN (ex.: 500 recursos não vinculados, 540 Fundeb, 550 salário-educação). **[conferir]** no classificador da SEF/SEPLAG |
| **Natureza da despesa** | **4.4.40.42**: investimento, transferência a municípios, auxílios (obras e bens). **3.3.40.41**: custeio, transferência a municípios, contribuições (repasse do 1º ano) | A modalidade **40** identifica transferência a municípios |
| **Identificador de procedência e uso / marcador de MDE** | Indica se a despesa conta para o mínimo de MDE | Se existir no detalhamento, responde à questão 2.5 |

### 3.2 Passo a passo
1. **Pegar a "ação" dos empenhos que vocês já ligaram aos convênios.**
   - Na base "Despesa pública" dos dados abertos de MG (dados.mg.gov.br), filtrar pelos nºs de empenho da planilha.
   - Trazer as colunas **programa, ação, subfunção, natureza da despesa e fonte**. A planilha atual tem a fonte, mas **não tem programa nem ação**.
2. **Procurar essas ações na LOA de cada ano (2021 a 2026).** A LOA está no site da SEPLAG-MG (Planejamento e Orçamento) e no da ALMG, onde tramita o projeto de lei.
   - Usar o **Quadro de Detalhamento da Despesa (QDD)** da SEE.
   - O QDD mostra, por ação, a **dotação inicial por fonte**. É assim que se vê se o Estado **planejou** pagar o Mãos Dadas com Fundeb ou se isso aconteceu depois, por remanejamento.
3. **Ver o PPAG (Plano Plurianual de Ação Governamental) 2020-2023 e 2024-2027.** A descrição da ação diz a finalidade e as metas físicas, como nº de municípios e de escolas.
4. **Ver os créditos suplementares e as alterações de fonte.** Os decretos de crédito suplementar no Diário Oficial (Jornal Minas Gerais) mostram se houve **troca de fonte** para Fundeb em 2021 e 2022.
5. **Comparar com os relatórios oficiais:**
   - RREO, Anexo 8 (MDE e Fundeb) de cada ano;
   - SIOPE do Estado;
   - **relatório técnico e parecer prévio do TCE-MG** sobre as contas do Governador de 2021 e 2022.
6. **Se a ação não aparecer nas bases abertas**, pedir pela **Lei de Acesso à Informação** (e-SIC MG) à SEE:
   - a(s) ação(ões) orçamentária(s) do Mãos Dadas;
   - a dotação por fonte em cada ano;
   - a justificativa jurídica para pagar convênios com a fonte Fundeb;
   - a forma de cômputo desses repasses no mínimo de MDE.

---

## 4. Próximos passos sugeridos
1. Acrescentar à planilha as colunas **programa / ação / natureza da despesa** de cada empenho (passo 3.2, item 1). Com isso, dá para fechar a análise da LOA.
2. Separar os convênios de **educação infantil pagos com Fundeb** em uma lista própria, com nº do convênio e do empenho. Ela serve de base para um eventual questionamento ao TCE-MG.
3. Juntar ao branch `Legislação`:
   - a Lei 14.113/2020, arts. 21, 25 e 29;
   - o ADCT, art. 212-A;
   - a Lei 9.766/1998;
   - os pareceres prévios do TCE-MG de 2021 e 2022.
4. Cruzar a lista dos 16 municípios com diferença (aba 1) com a resposta da SEE.
