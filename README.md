# Meshtastic Macanudos
Rede DeFLoRa

Descrição: rede de dispostivos Meshtastic LoRa de troca de mensagens, emergência e localização fora da rede. Sem qualquer dependência da internet. Comunique offgrid ou use a rede como gateway para IoT.

Frequência: 433 Mhz e 868 Mhz (preferencialmente 433 Mhz) - bandas livres

Estado: Em testes com 5 routers e 3 clientes. (18.12.2022)

## Projecto DeFLoRa

Para consutlar o mapas, saber ou obter informação detalhada, mais consulte a página do projecto: https://macanudos.org/deflora

## Suporte

Online: o suporte desta rede LoRa é realizado através de um chat no servidor IRC #redesuporte e do mumble do Macanudos.org, canal redesuporte

Fora da rede: mas dentro da rede DEFLORA, suporte no canal suporte.

## Equipamentos
Os equipamentos fornecidos já vêm programados e configurados para a rede, com os canais extra e as prioridades máximas. Configuramos ao sabor do cliente. Todos os dispositivos são universais podendo servir qualquer outra função futura que venha a ter necessidade. Para saber mais, consulta a página DeFLoRa.

# Instalação do firmware Mestastic Macanudos

Deve instalar o firmware usando a tool [Flash Download Tools	Windows](https://www.espressif.com/en/support/download/other-tools)

# Exemplos de configuração para modelos ESP32

## Update Firmware

![Update](imagens/Exemplo-configuração-Update.png)

## Factory Default ou Primeira instalação

![Factory Default](imagens/Exemplo-configuração-Factory-Default.png)

# Exemplo de configuração para modelos NRF52

## Update Firmware

* Conecte seu dispositivo ao computador com um cabo de dados USB.
* Clique duas vezes no botão de reinicialização do seu dispositivo (isso o colocará no modo bootloader)
* Observe que uma nova unidade será montada em seu computador (Windows, Mac ou Linux)
* Abra esta unidade e você verá três arquivos: CURRENT.UF2, INDEX.HTM e INFO_UF2.TXT
* Solte o arquivo de firmware apropriado (Por Exemplo: T-Echo.Macanudos.firmware.uf2) da versão nesta unidade.
* Depois que o arquivo for copiado para a unidade, o dispositivo será reinicializado e instalará o firmware Meshtastic-Macanudos

# Canais da rede DefLoRa

Existem 3 canais publicos iniciais na rede, um é o "primary" que é o canal principal da rede meshtastic, e do outros um é o canal 333 e o suporte.
Para configurar o canais da rede basta ler o QRK code aqui.
O canal #rodinha é reservado a convite e econtra-se ligado à vénus e destinado a testes.

