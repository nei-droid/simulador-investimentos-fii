# Simulador de Investimentos - FII

Simulador em planilha Excel para projetar aportes mensais em Fundos Imobiliários (FIIs), estimar patrimônio futuro, dividendos mensais e distribuição por tipo de FII conforme perfil de investidor.[file:1]

---

## Visão geral

- Formato: arquivo Excel (`Simulador-de-Investimentos.xlsx`).[file:1]  
- Foco: investimentos mensais em FIIs, com base em salário, taxa de retorno da carteira e perfil (Conservador, Moderado ou Agressivo).[file:1]  
- Saídas principais: patrimônio acumulado, dividendos estimados e distribuição sugerida do aporte entre tipos de FII.[file:1]

---

## Estrutura da planilha

### Aba `Simulador`

Contém a interface principal de uso.[file:1]

- **Configurações**  
  - Salário  
  - Rendimento da carteira (taxa média mensal em decimal, ex.: 0,006)  
  - Sugestão de investimento (20% do salário por padrão).[file:1]

- **Investimento Mensal**  
  - Quanto investir por mês  
  - Por quantos anos  
  - Taxa de rendimento mensal (ex.: 0,01079)  
  - Patrimônio acumulado estimado  
  - Dividendos mensais estimados.[file:1]

- **Cenários de longo prazo**  
  Projeções de patrimônio e dividendos para diferentes horizontes de tempo (ex.: 2, 5, 10, 20 e 30 anos).[file:1]

- **Perfil e distribuição por tipo de FII**  
  - Campo de perfil (ex.: Agressivo).[file:1]  
  - Valor a ser investido por mês (aporte total).[file:1]  
  - Tabela com tipos de FII (PAPEL, TIJOLO, HÍBRIDOS, FOFs, DESENVOLVIMENTO, HOTELARIAS), percentual sugerido e valor correspondente do aporte.[file:1]

### Aba `Apoio`

Base de dados com a configuração de percentuais por perfil e tipo de FII.[file:1]

- Colunas principais:  
  - CHAVE (ex.: Agressivo-PAPEL)  
  - PERFIL (Conservador, Moderado, Agressivo)  
  - TIPO DE FII  
  - % (percentual sugerido para aquele tipo dentro do perfil).[file:1]

Essa aba é usada como tabela de referência para gerar automaticamente a distribuição da aba `Simulador`.[file:1]

---

## Como usar

1. Abra o arquivo `Simulador-de-Investimentos.xlsx` no Excel ou software compatível.[file:1]  
2. Na aba **Simulador**, preencha em Configurações:  
   - Seu salário mensal.  
   - Rendimento esperado da carteira (mensal, em decimal).  
   - Ajuste a sugestão de investimento, se desejar (por padrão é 20% do salário).[file:1]  
3. Em **Investimento Mensal**, informe:  
   - Quanto pretende investir por mês (pode usar o valor sugerido).  
   - Por quantos anos deseja manter os aportes.  
   - Taxa de rendimento mensal esperada.[file:1]  
4. Verifique os campos calculados de:  
   - Patrimônio acumulado.  
   - Dividendos mensais estimados.  
   - Projeções de cenários para 2, 5, 10, 20 e 30 anos.[file:1]  
5. Defina o perfil de investidor (Conservador, Moderado ou Agressivo).[file:1]  
6. Consulte a tabela de distribuição por tipo de FII para saber quanto alocar em cada categoria (PAPEL, TIJOLO, etc.).[file:1]

---

## Personalização e ajustes

- Você pode alterar os percentuais de cada tipo de FII por perfil na aba `Apoio`, caso queira um modelo diferente do padrão.[file:1]  
- Também pode ajustar o percentual de investimento do salário (ex.: 15%, 25%) alterando a fórmula da “Sugestão de Investimento (20%)”.[file:1]  
- Para incluir novos tipos de FII ou perfis, basta seguir o padrão de chave (Perfil-TIPO) na aba `Apoio` e adaptar as fórmulas na aba `Simulador`, se necessário.[file:1]

---

## Aviso

Este simulador tem finalidade educativa e de planejamento e **não** constitui recomendação de investimento, análise profissional ou garantia de retorno financeiro.[file:1]

