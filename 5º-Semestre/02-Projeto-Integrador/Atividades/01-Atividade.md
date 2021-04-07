
# Atividade I

Muitas vezes, estamos na maior paz na empresa, de repente, seu chefe com a costumeira delicadeza fala:
Você é o responsável pelo projeto de informatização de uma empresa de nosso portfólio. Ele necessita transferir informações entre suas duas filiais (que se encontram geograficamente separadas por uma distância de 350 Km). Diante das opções de meios físicos disponíveis, você deve decidir pela implantação da melhor solução com o menor custo.  
Ele passou algumas informações:

- A quantidade de dados que precisa ser transferida todos os dias à noite é de 22 MegaBytes. Não deve ser usada compactação nem compressão. O tempo disponível para transferência é de 6 horas no máximo.  
- O método de transferência deve ser assíncrono, com dois bits de sincronismo (a cada 8 bits transmitidos, 6 bits são de dados e 2 são de parada, 75% de aproveitamento).
- O protocolo de comunicação estabelece o aproveitamento de no mínimo 70% da taxa de transferência efetiva disponível. Os 30% restantes serão gastos com o protocolo e eventuais correções de erro na transmissão.  
- E, por fim, pediu a gentileza de colocar na mesa dele antes do almoço qual a taxa de transferência efetiva mínima que deve estar disponível, porque ele ia passar para a equipe de campo e para o cliente para deixá-lo tranquilo.
