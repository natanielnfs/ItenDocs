# Fluxo de funcionamento - Iten Tecnologia

## Novo chamado

### Analise de Ticket

É aqui onde o gestor define o tipo do ticket e seu responsável

### Visita técnica
- Manutenção
- Suporte remoto
- Verificar se etiqueta do dispositivo é válida

#### Tem etiqueta
- Não tem etiqueta 
  - Processo de inventário

#### Incluir no domínio
- Recolhimento
  - ⚠️ Documentar foto ou vídeo no Bitrix
  - Equipe coleta
  - Cliente trás
  - Agendar visita para recolhimento
  - Visita
  - Check-In no escritório
  - Transferência para manutenção
  - Aguarda retorno da manutenção
  - Pedido de compra
  - Autorização de transferência para terceiros
  - Pedido pronto
  - Sem solução
    - Devolução
  - Pedido de autorização para cliente
    - Cliente autorizou
    - Cliente não autorizou

### Sem solução
- Devolução

#### Cliente autorizou
- Cliente não autorizou

#### Aguarda terceiro

### Verifica se equipamento possui etiqueta
- Tem etiqueta
- Não tem etiqueta

### Define nome de equipamento

#### Veja mais detalhes sobre o padrão de nome no fluxo de inventário

- Imprime e cola etiqueta

### Análise física

#### Contagem de equipamentos por tipo
- VIRT: Virtualizador
- SRV: Servidor
- WKS: Workstation (terminais)
- FWL: Firewall
- SW: Switch
- RTR: Roteador

### Definir sigla da empresa
⚠️ Verificar se sigla não está sendo utilizada para outra empresa no GLPI

### Definir nome de equipamentos
Os itens devem seguir o padrão

EMP-TYPE-000A


Onde:
- EMP = SIGLA DA EMPRESA
- TYPE = TIPO DO DISPOSITIVO
- 0000 = CONTAGEM CRESCENTE

⚠️ Com exceção para os tipos: FWL e SRV, que devem estar na frente do nome.

Exemplo: SRV-EMP-0001

### Exportar lista XLSX no NafTI
1. Acessar NafT
2. Clique em exportar etiqueta
3. Filtre os dispositivos
4. Clique em exportar como XLSX

### Impressão
- Acesse o template de etiquetas que está na base de conhecimento, e importe o XSLX exportado na etapa anterior, logo imprima em massa todas etiquetas.

### Agendar visita
- Visita

### Alterar nome do dispositivo
Essa etapa é crucial para inventário, pode ser realizada na inclusão no Active Directory

- Colar etiqueta em seu respectivo equipamento
- Criar equipamento no GLPI
- Fotografar e documentar dispositivo no GLPI
- Verificar se agente GLPI está instalado e se sincronizou informações

### Verifique a lista de nomenclaturas de dispositivos na base de conhecimentos do Bitrix

### Técnico avalia tipo de suporte
- Impressoras
- Active Directory
- VPN
- Terminal
- Redes
- Internet

### Instalação de impressora
- Impressora não imprime

### Outro
- Criar usuário
- Incluir máquina no AD
  - Não loga

### Instalação de VPN
  - VPN não conecta/lenta

### Problemas físicos
  - Mudança de local
  - Pedido de revisão

### Destino fora de alcance
  - Rede parada
  - Sem internet
  - Wi-Fi parado
  - Internet lenta
  - Algo específico não carrega

### Amarelo: São pedidos que podem virar visita técnica

## Começo
- Manutenção
- Processo de inventário
- Suporte remoto
