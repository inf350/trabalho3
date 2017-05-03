This folder contents the Trabalho 3 specification
Portuguese Version

Trabalho 3
a) Explorar leituras de sensores (DHT, Ultrasonico e LDR) com ajustes via terminal serial. 
Implementar os comandos com funcoes. Atraves da Interface serial é possivel enviar os comandos e
visualizar a saida. Qualquer comando pode ser ativado ou inibido. Comandos: Intervalo de Leitura, 
Valor para minimo, maximo, media, numero de leituras para armazenar, Led 13 como alerta para 
min ou max, relogio com a hora associado a leitura, Fazer n leituras e descartar x valores fora da 
mediana, Dependo da disponibilidade, seu trabalho será usando o DHT, o Ultrasonico ou LDR. Mas
deve ser independente do sensor. Na avaliação podem ser usado para teste qualquer um dos 
sensores.
O sensor deve ser encapsulado no método SensorRead(), onde facilmente podemos escolher entre 
DHT, LDR ou Poteciometro, Ultrasonico
Usar ON para Ativar e OFF para desativar um comando.
Comandos
Min/ON para ligar o medidor de Minimo
Min/OFF para desligar
Min/PRINT para mostrar o valor atual do minimo
Min/Event/<valor>, exemplo Min/Event/20 para gerar alerta sempre que baixar de 20. liga LED 13.
O mesmo para Average e Max (media e maximo)
Rate/SET para ajustar o tempo entre uma medida e outra em ms
Clock/ON
Clock/OFF
Clock/SET/<hora>
Clock/PRINT
Sample/SET/<n> para armazenar as n ultimas leituras, fixar em 20 o maximo para n. 
Sample/PRINT 
Drop/ON  - faz m leituras e descartar k leituras (longe da mediana) 
Drop/OFF 
Drop/SET/<m>/<k> para programar m e k
b) Refazer o trabalho 2 do contador com 2 arduinos ligado pela serial. Usar a biblioteca software 
serial. A chave de um arduino irá fazer o led do outro arduino piscar e vice e versa. Montar no 123D
circuits. 

