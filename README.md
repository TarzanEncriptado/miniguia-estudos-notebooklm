# miniguia-estudos-notebooklm
Treinamento de um NotebookLM sobre OSINT em dados púbicos

## Guia estruturado básico: OSINT e dados públicos

### Processo de pesquisa (5 porquês)
1. **Por que falar sobre dados públicos?**  
   Porque eles permitem análises transparentes, verificáveis e com baixo custo de acesso para estudos e decisões.
2. **Por que isso é relevante agora?**  
   Porque o volume de informações digitais cresceu e a capacidade de verificar fontes se tornou essencial.
3. **Por que OSINT entra nesse processo?**  
   Porque OSINT organiza a coleta, validação e análise de fontes abertas para gerar inteligência útil.
4. **Por que diferenciar dado, dado público e informação analisada?**  
   Porque dado bruto sem contexto pode levar a erro; o valor está no tratamento crítico e na correlação.
5. **Por que consolidar tudo em método?**  
   Porque um processo repetível melhora a qualidade da investigação e reduz viés.

### Conceitos essenciais
- **Quem mencionou esse tema?**  
  O conceito de OSINT foi consolidado em ambientes de inteligência e segurança, sendo amplamente citado por órgãos governamentais, comunidade acadêmica e profissionais de investigação digital.
- **O que é OSINT?**  
  Open Source Intelligence: metodologia de obtenção e análise de informações a partir de fontes abertas e legalmente acessíveis.
- **O que é dado?**  
  Registro bruto de um fato (número, texto, imagem, data, localização etc.).
- **O que é dado público?**  
  Dado disponibilizado para acesso aberto por governos, instituições, empresas ou plataformas, respeitando leis e limites de uso.
- **Por que fazer OSINT nos dias atuais?**  
  Para apoiar decisões, checar fatos, mapear riscos, investigar contexto e reduzir desinformação com evidências.

### Tabela de prompts e melhorias para troubleshooting

| Objetivo | Prompt base | Melhoria para troubleshooting |
|---|---|---|
| Definir escopo da investigação | "Liste os pontos centrais do tema X para uma investigação OSINT inicial." | Adicionar recorte temporal, geográfico e palavras-chave negativas (ex.: "não incluir opinião"). |
| Levantar fontes públicas confiáveis | "Quais fontes públicas oficiais posso usar para pesquisar X?" | Solicitar classificação por tipo de fonte (governo, imprensa, base acadêmica) e nível de confiabilidade. |
| Validar uma informação | "Como verificar se a informação Y é verdadeira com dados públicos?" | Exigir no mínimo 3 fontes independentes e critério de divergência entre fontes. |
| Organizar evidências | "Monte uma estrutura para registrar achados de OSINT sobre X." | Pedir modelo com campos obrigatórios: fonte, data, URL, evidência, hipótese, status de validação. |
| Resolver bloqueio de pesquisa | "Estou sem novos resultados sobre X, quais caminhos alternativos seguir?" | Solicitar reformulação de termos, sinônimos, buscas por idioma e inversão de perspectiva (pessoa, local, evento). |
| Refinar hipótese | "Com base nos achados, quais hipóteses são mais plausíveis sobre X?" | Pedir evidência pró/contra para cada hipótese e indicar lacunas de dados antes de concluir. |

### Análise da estrutura
Uma estrutura básica eficiente de OSINT em dados públicos segue: **objetivo claro → coleta em fontes abertas → validação cruzada → organização das evidências → síntese crítica**. Esse fluxo reduz ruído, melhora rastreabilidade e facilita revisão por terceiros.

### Resumo prático
Para aplicar hoje: defina uma pergunta específica, colete apenas fontes públicas relevantes, valide com múltiplas origens, registre tudo de forma padronizada e conclua com base em evidências. Em OSINT, método e criticidade valem mais que volume de dados.
