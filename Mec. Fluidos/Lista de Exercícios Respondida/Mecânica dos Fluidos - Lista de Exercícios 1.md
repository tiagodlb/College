#Resolução #MecanicaFluidos
# Resolução
#### 1) Com relação à variação de pressão em fluidos em repouso, assinale a alternativa incorreta.
###### Resposta 
- **Letra d, a distribuição de pressão em um fluido homogêneo, incompreensível e em repouso é função da profundidade, do tamanho e da forma do recipiente que contém o fluido.** 

#### 2) Com relação às pressões e aos medidores de pressão, assinale a alternativa incorreta.
###### Resposta 
- **Letra b, as pressões absolutas são medidas em relação à pressão atmosférica local.** 

#### 3) Defina manometria. Além disso, defina tubo piezométrico, manômetro com tubo em U e manômetro com tubo inclinado, ilustrando cada um deles e descrevendo como são feitos os cálculos das pressões em cada um deles.
###### Resposta 
1.Definição de  manometria
	Técnica utilizada na medição de pressão, envolve o uso de colunas de líquidos verticais ou inclinadas. Os dispositivos para a medida da pressão baseados nessa técnica são chamados de manômetros.
2. Tubo Piezométrico
	Tipo mais simples de manômetro que consiste num tubo vertical aberto no topo e conectado ao recipiente no qual desejamos conhecer a pressão (Fig. 1.0). A equação da pressão é aplicável pois a coluna de líquido se encontra em equilíbrio.
	$$ p = p_0 + \gamma h  $$
	Esta equação fornece o valor gerada para a pressão em qualquer coluna de fluido homogêneo em função da pressão de referência  p0  e da distância vertical entre os planos de p e p0. Sabendo que a pressão aumenta quando nos movimentamos para baixo da coluna do fluido e diminui ao nos movimentarmos para cima, a aplicação da equação ao tubo piezométrico da Fig. 1.0 fica: $$p_A = \gamma _1h_1$$
	![[Pasted image 20230926153005.png]]
								Figura 1.0
3. Tubo em U
	O manômetro com tubo em U foi desenvolvido para melhorar as dificuldades do manômetro  de tubo piezométrico ( só pode ser usado nos casos onde a pressão do recipiente é maior do que a ada pressão atmosférica, além de precisar que a pressão do reservatório não seja muito grande e do fato que o fluido do recipiente ser necessariamente líquido). Nele o fluido que se encontra no tubo do manômetro é denominado fluido manométrico. Para encontrarmos  a pressão no mesmo utilizamos a seguinte equação: $$ p_A = \gamma _2 h_2 - \gamma _1 h_1$$
	![[Pasted image 20230926154509.png]]
4. Tubo em U inclinado
	O manômetro em U inclinado tem o mesmo princípio de funcionamento do manômetro em U porém com maior sensibilidade. Uma de suas pernas é inclinada em relação a outra. A sensibilidade é regulada através do ângulo formado entre o tubo e o horizonte. A pressão é encontrada através da seguinte equação: $$p_b - p_a = (p_m - p_f) gH$$ Onde,$$H = L\sin(\theta)+h$$
	![[Pasted image 20230926154441.png]]
#### 4)  A água de um lago localizado em uma região montanhosa apresenta temperatura média igual a 5 °C e a profundidade máxima do lago é de 50 m. Se a pressão barométrica local é de 580 mmHg, determine a pressão absoluta na região mais profunda do lagoa.

![[Pasted image 20230926154834.png]]

###### Resposta 
$$p = p_0 + \gamma h$$$$p_0 = \gamma _m h = 133\cdot0,58 = 77,14kN/m^2 $$
$$p = 77,14 + 9,807 \cdot 50 = 567,49kPa$$
#### 5) Um tanque fechado contém ar comprimido e um óleo que apresenta densidade 0,8. O fluido manométrico utilizado no manômetro em U conectado ao tanque é mercúrio (densidade igual a 13,6). Se h1 = 900 mm, h2 = 151 mm e h3 = 200 mm, determine a leitura no manômetro localizado no topo do tanque.

![[Pasted image 20230926154811.png]]

###### Resposta 
  $$p_1 = p_a + \gamma _o(h_1+h_2)$$
$$p_a + \gamma _o(h_1 + h_2) - \gamma _h \cdot h_3 = 0$$
$$p_a = 13,6 \cdot 9800 \cdot 0,2 - \cdot 0,8 \cdot 9800 \cdot (0,9 + 0,151) \implies$$
$$p_a = (26659 - 8239,54) = 18416,16 Pa \implies p_a = 18,42kPa $$
