# IPG_Monitor - NodeJS App

## Definições gerais

**Tudo fica registado neste documento, e é atualizado conforme o andamento do projeto.**
**Aquilo que não se vai implementar, é simplesmente riscado, mas não apagado.** Isso permite que tenhamos uma ideia do que foi pensado, e o que foi descartado. Também podemos voltar a pensar nisso mais tarde, ou modificar para se adequar ao que se está a pensar no momento.

Exemplo: 

~~- [ ] Implementação da função para tirar cafés~~

## TODO list

### Server

- [ ] Receber conexões TCP
- [ ] Enviar comandos e apresentar a resposta do cliente
- [ ] Pedir um diagnóstico arbitrário e receber resposta
- [ ] Envio de algum tipo de mensagem quando receber informações críticas de um computador ( e-mail, SMS, WhatsApp?! )
- [ ] Listagem de equipamentos (JSON com todas as máquinas)
- [ ] Criar cli com comandos básicos e um belo panela num while loop infinito
- [ ] agrupar computadores por salas, avisar que salas podem está em aula


### Clientes

- [ ] Verificar conexão à internet. (ping -c 1 www.google.pt?)
- [ ] Verificar portas ligadas:
    - [ ] ecrã
    - [ ] internet
    - [ ] teclado e rato
- [ ] Enviar dados ao servidor ( JSON )
- [ ] recuperar o seu MAC address e o seu IP
- [ ] Enviar OS, updates available, tanto Windows como wingets
- [ ] Check de espaço disponível em disco
    - [ ] Definir pouco espaço e espaço crítico 
- [ ] Executar comandos vindo do servidor, e enviar STDOUT e STDERR como resposta de volta ao servidor
- [ ] ser capaz de enviar o diagnóstico ao ligar o PC, mas também quando um parâmetro passe a ser critico


## Ideias

Penso que seja necessário, tanto para o servidor, como para os cliente, de esperar e receber dados, logo, talvez é necessário serem todos client/server ao mesmo tempo
