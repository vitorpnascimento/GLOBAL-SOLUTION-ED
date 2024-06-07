#info wave - Monitoramento da Qualidade da Água

## Descrição do Projeto
Este projeto utiliza a plataforma ESP32 e sensores para monitorar dados do litoral, abordando problemas de poluição marinha. Os dados são coletados e enviados para uma plataforma de visualização para conscientização pública.

## Componentes Utilizados
- ESP32
- Sensor de Temperatura e Umidade DHT22

## Instruções de Uso
1. Clone este repositório: `git clone https://github.com/yourusername/oceanguard.git`
2. Instale as bibliotecas necessárias:
   - `DHT sensor library for ESPx`
   - `PubSubClient`
3. Configure seu ESP32 com o código fornecido no arquivo `main.cpp`.
4. Conecte os sensores aos pinos especificados no código.
5. Compile e faça upload do código para o ESP32.
6. Abra o Serial Monitor para verificar os dados dos sensores.

## Requisitos
- Plataforma Arduino IDE
- ESP32
- Sensor DHT22

## Configurar o Código
- Atualize os valores ssid e password com as credenciais da sua rede WiFi, se necessário.

## Simulação Wokwi
[Link para a simulação no Wokwi](https://wokwi.com/projects/400052004877181953)

## Resultados Esperados
Espera-se que os dados coletados proporcionem uma visão em tempo real do ambiente, permitindo ações rápidas para mitigar a poluição marinha e aumentar a conscientização pública.

## Contribuições
Sinta-se à vontade para contribuir com melhorias no código ou na documentação.

## Licença
Este projeto está licenciado sob a MIT License.
