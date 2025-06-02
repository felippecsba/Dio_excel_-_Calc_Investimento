# Calculadora de Investimentos

Esta planilha é uma ferramenta simples e robusta, desenvolvida para auxiliar no planejamento financeiro pessoal, com foco na projeção de investimentos em Fundos de Investimento Imobiliário (FIIs). Criada por **Felippe Araújo**, ela permite configurar o valor a ser investido mensalmente, projetar o crescimento do patrimônio e dividendos ao longo do tempo, e sugere uma distribuição do investimento em diferentes tipos de FIIs com base no perfil do investidor.

## Funcionalidades

* **Cálculo Sugerido de Investimento:** Sugere um valor de investimento mensal baseado em uma porcentagem do seu salário (padrão de 30%).
* **Projeção de Patrimônio e Dividendos:** Estima o acúmulo de patrimônio e a geração de dividendos mensais em diferentes horizontes de tempo (2, 5, 10, 20 e 30 anos), considerando uma taxa de rendimento mensal.
* **Alocação Sugerida em FIIs:** Oferece uma sugestão de distribuição do seu investimento mensal em diferentes categorias de FIIs (Papel, Tijolo, Híbridos, FOFs, Desenvolvimento, Hotelarias), de acordo com o perfil de investidor selecionado.

## Como Usar

1.  **Abertura:** Abra o arquivo da planilha (provavelmente um arquivo `.xlsx` ou similar) em um software compatível (ex: Microsoft Excel, Google Sheets, LibreOffice Calc).
2.  **Campos de Entrada (Dados do Usuário):** Os campos a seguir são onde o usuário pode inserir suas informações e preferências:
    * `Salário`: Insira o seu salário mensal atual.
    * `Rendimento Carteira`: (Opcional) Preencha com o rendimento atual da sua carteira de investimentos, se aplicável.
    * `Sugestão de Investimento (30%)`: Este campo calculará automaticamente 30% do seu salário como sugestão de investimento. Você pode ajustar a porcentagem se desejar.
    * `Quanto investir por mês?`: Este campo será preenchido automaticamente com a `Sugestão de Investimento`, mas você pode alterá-lo manualmente para o valor exato que deseja investir.
    * `Por Quantos Anos?`: Defina o horizonte de tempo (em anos) para o qual você deseja fazer a projeção inicial de acúmulo de patrimônio e dividendos.
    * `Taxa de Rendimento mensal?`: Insira a taxa de rendimento mensal esperada para seus investimentos (ex: `0,01` para 1%).
    * `Seu perfil`: Escolha uma opção através do **menu dropdown** para definir o perfil de risco do investidor (por exemplo, Conservador, Moderado, Agressivo). Esta escolha influenciará a sugestão de alocação em FIIs.
3.  **Análise dos Cenários:**
    * A seção "Cenários" mostrará automaticamente as projeções de quanto você teria acumulado e quanto receberia em dividendos em diferentes períodos, com base nas configurações de investimento mensal e taxa de rendimento.
4.  **Alocação em FIIs:**
    * A tabela "TIPO DE FII" mostrará a porcentagem sugerida e o valor correspondente a ser investido em cada categoria de FII, de acordo com o perfil selecionado. Use isso como um guia para diversificar sua carteira de FIIs.

## Conhecimentos de Excel Aplicados

Esta planilha foi construída utilizando diversos recursos avançados do Microsoft Excel para garantir precisão e dinamismo nos cálculos:

* **Soma e Multiplicação:** Funções básicas para cálculos de totais e projeções.
* **VF (Valor Futuro):** Utilizada para calcular o patrimônio acumulado ao longo do tempo, considerando o investimento mensal e a taxa de rendimento.
* **PROCV (ou XLOOKUP):** Empregada para buscar e retornar informações de tabelas de apoio, como as configurações de alocação de FIIs baseadas no perfil do usuário.
* **Chave Composta:** Utilizada para a combinação de critérios em buscas e referências, permitindo maior flexibilidade na extração de dados.
* **Variáveis Globais:** Conceito de células dedicadas que armazenam valores-chave (como a taxa de rendimento ou o valor do salário) que são referenciados em toda a planilha, facilitando atualizações.
* **Tabelas de Apoio:** Utilizadas para organizar dados auxiliares, como as diferentes sugestões de alocação para cada perfil de investidor, tornando a planilha mais organizada e escalável.
* **Validação de Dados (Menu Dropdown):** Implementada para o campo "Seu perfil", garantindo que o usuário selecione uma opção válida de uma lista pré-definida, melhorando a usabilidade e prevenindo erros.

## Observações Importantes

* Esta planilha é uma **ferramenta de auxílio e projeção**, e não uma recomendação de investimento.
* As projeções são baseadas nas taxas de rendimento inseridas e não garantem retornos futuros. O mercado financeiro possui riscos e incertezas.
* Sempre busque conhecimento e, se necessário, o auxílio de um profissional certificado antes de tomar decisões de investimento.

## Autor

Felippe Araújo
