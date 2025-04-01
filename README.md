Una empresa nos convoca para armar una APP que controle el clima de un datacenter. La misma deberá
tener registro (actual e histórico) de: temperatura, humedad y permitiendo controlar el “Clima” a través de
una API de terceros (MS-Forecast) que se invocan desde la APP. La APP será por consola a efectos del final.
La APP MS-Forecast posee las siguientes interfaces:
1. Up_Temp( int X)
2. Down_Temp( int X)
3. Up_Humity( int X)
4. Down_Humity( int X)
5. Read_Temp
6. Read_Humity
EL componente MS-Forecast se invoca directamente (se sugiere construir un MOCK para simularlo)
