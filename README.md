# dio-ferramenta-investimento-FII
Repositório do desafio de criação de uma Ferramenta de Controle de Investimentos FII com Excel

# Criando uma Ferramenta de Controle de Investimentos com Excel

## Narrativa 

Laboratório para desenvolvimento de uma ferramenta de simulação de investimentos em fundos imobiliários. A ferramenta visa auxiliar o usuário a realizar cálculos mais complexos, de forma a responder perguntas importantes para uma tomada de decisões mais informada sobre seus investimentos.

### Contexto ❓

O projeto busca responder as seguintes perguntas:
- **Quanto investir por mês?** Baseado no Salário informado pelo usuário, é calculado uma porcentagem para sugerir o valor de investimento mensal e mostrar cenários de investimentos a partir dessa sugestão;
- **Por quantos anos?** Diferentes tempos de investimentos trazem diferentes retornos, então a ferramenta simula investimentos de 2, 5, 10, 20 e 30 anos;
- **Taxa de rendimento mensal?** A partir da menor taxa praticada, a ferramenta esclarece o quanto o valor investido pode render mensalmente, sendo possível simular cenários com outras taxas;
- **Patrimônio acumulado?** Além do rendimento mensal, a ferramenta também traz uma perspectiva do patrimônio acumulado a final do tempo de investimento. Também é possível simular outros Cenários além daqueles já expostos na ferramenta;
- **Dividendos mensais?** Similar ao Patrimônio acumulado, a ferramenta também traz perspectivas de Dividendos mensais em Cenários já simulados, além de permitir simular novos cenários a partir do Valor de investimento, do Tempo e da Taxa de rendimento mensal que o usuário queira simular.

### Considerações 📌

- Além das perguntas anteriormente apresentadas, o usuário também pode acompanhar Sugestões de investimentos nos diferentes tipos de FII a partir de diferentes perfis: Conservador, Moderado e Agressivo;
- Para facilitar a compreensão do usuário, a ferramenta inclui um gráfico que simula, percentualmente, a distribuição do Investimento nos tipos de FII.

## Aprendizados 📝

O que você aprendeu construindo esse projeto? Quais desafios você enfrentou e como você superou-os?

- Uso de fórmulas financeiras (VF) já contidas no Excel, evitando erros na construção manual de fómrulas mais complexas;
- Nomeação de células, facilitando o uso posterior na construção de novos valores;
- Uso de chaves compostas na construção de chaves únicas para modificar valores dinamicamente a partir de uma Validação de dados do tipo Lista;
- Planilha com Tabela de apoio, evitando uso de fórmulas dentro de fórmulas, que podem resultar em lentidão no carregamento da ferramenta e erros nos valores apresentados ocasionados pela construção das fórmulas, além de permitir facilidade na atualização das informações contidas na Tabela;
- Uso do Procv para modificação dinâmica de valores dentro da ferramenta, usando a Tabela de apoio para busca desses valores,permitindo a simulação de diferentes distribuições de Investimentos, a partir das informações previamente dadas pelo usuário;
- Noção de Uniformidade Visual, buscando trazer um visual mais amigável e intuitivo, facilitando a compreensão da informação que se quer buscar na ferramenta.


