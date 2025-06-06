# Ferramenta para Simulação de Investimentos em Fundos Imobiliários

## Configurações

No campo **Configurações**, preencha os campos **Salário** e **Rendimento da Carteira**.  
Será sugerido o valor de investimento com base no salário informado.

## Investimento Mensal

Em **Investimento Mensal**, preencha os seguintes campos:
- **Quanto investir por mês**
- **Por quantos anos**
- **Taxa de rendimento mensal**

No campo **Patrimônio acumulado**, será mostrado o valor acumulado durante o período informado.  
No campo **Dividendos mensais**, será exibido o valor do rendimento referente ao patrimônio acumulado.

## Cenários

Em **Cenários**, é apresentado o patrimônio acumulado e o dividendo mensal considerando diferentes horizontes de tempo: 2, 5, 10, 20 e 30 anos.

## Perfil

Em **Perfil**, informe o valor a ser investido e selecione o tipo de perfil.  
Será exibido o percentual para investimento com base no valor informado e no perfil escolhido.

---

Foi utilizada a fórmula `VF` do Excel para calcular o valor acumulado durante o período informado, considerando a taxa de rendimento e o valor investido mensalmente.  
Foi utilizada a fórmula `PROCV` para encontrar o percentual de investimento de acordo com o perfil escolhido.
