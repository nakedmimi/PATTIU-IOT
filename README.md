# PATTIU-Gestão Inteligente de Pátios Mottu
**DISRUPTIVE ARCHITECTURES: IOT, IOB &amp; GENERATIVE IA**
 
## Descrição do Projeto
Este projeto foi desenvolvido para otimizar a gestão de grandes pátios de motos, como os utilizados pela Mottu, utilizando tecnologia de ponta para garantir localização rápida, controle preciso e rastreabilidade em tempo real. A solução integra BLE (Bluetooth Low Energy), NFC e um sistema de localização com LEDs e sinais sonoros, proporcionando agilidade operacional e redução de perdas por desorganização ou falhas manuais.
 
Com isso, utilizamos o microcontrolador ESP32 para representar nossa ideia — neste caso, um LED e um buzzer — por meio do envio de comandos em formato JSON, representando uma tag de cadastro da moto. A proposta é criar uma solução simples, leve e funcional, que pode ser aplicada em cada moto para uma melhor visualização, permitindo que o funcionário localize rapidamente a moto no pátio.
 
## Vídeo Pitch
https://youtu.be/cEEgseSmiNI?si=kHukSM8zD2d82MIB


## Link Wokwi

 
## Funcionalidades
* Identificação Individual: Cada moto pode conter um ESP32 configurado para representar sua “tag digital”.
* Localização Visual e Sonora: O LED facilita a identificação visual da moto; o buzzer permite localizá-la mesmo em ambientes com baixa visibilidade.
* Ativação por Comando Remoto: A ativação do LED e do buzzer é feita por meio de comandos JSON(que representa a tag de cadastro da moto) simples.
* Aplicação em Pátios ou Garagens: Ideal para a organização de veículos com agilidade.

 
## Tecnologias Utilizadas
 * **Hardware**
-ESP32
-LED
-Buzzer
-resistores e jumpers
 * **Linguagem**
-C++
 * **Software**
-Wokwi
-Interpretação de comandos em JSON via mobile
-Comunicação via Wi-Fi

## Execução do projeto via APP mobile

Para a o envio de comando json via MOBILE, acesse o link do repositorio da aplicação MOBILE
https://github.com/FIAP-MOBILE/challenge-pattiu
 
## Próximos Passos
* Realização do Projeto Físico: Desenvolvimento de uma versão compacta e resistente do circuito para ser fixada diretamente nas motos da frota.
* Mapeamento dos Pátios: Integração com sistema de geolocalização via NFC e AR Tags para saber a posição exata da moto dentro do pátio.
* Testes em Ambiente Real: Validação da solução em pátios reais, com monitoramento de desempenho, autonomia e eficiência.
* Escalabilidade: Preparação do sistema para funcionar com dezenas ou centenas de dispositivos ESP32 simultaneamente.
* Alimentação Independente: Implementação de bateria recarregável ou conexão direta com a bateria da moto.

## Autores
* Leonardo Botelho - RM: 556110 - Turma: 2TDSB - GitHub: https://github.com/Wanderluzter
* Mirian Bronzati - RM: 555041 - Turma: 2TDSB - GitHub: https://github.com/nakedmimi
* Raul Clauson| - RM: 555006 - Turma: 2TDSB - GitHub: https://github.com/RaulClauson
