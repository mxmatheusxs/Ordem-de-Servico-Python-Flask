# **Ordem de Serviço Python Flask**

Este é um projeto para o gerenciamento de **Ordens de Serviço (OS)**, desenvolvido com foco em aumentar a produtividade e simplificar o acompanhamento diário de tarefas, atendimentos e tempo investido pelos colaboradores.
O sistema permite que usuários filtrem, visualizem e copiem informações detalhadas de ordens de serviço, incluindo imagens, descrições e horários. Ele também auxilia no controle de carga horária diária, destacando o tempo restante para completar 8 horas de trabalho.

## **Funcionalidades**
- **Gerenciamento de Ordens de Serviço:**
  - Visualização de cliente, data, horários (início e término), duração e descrição da OS.
  - Adição de novas OS e exclusão de OS antigas diretamente pelo painel.
- **Filtragem por Data:**
  - Seleção de uma data específica para exibir apenas as ordens de serviço daquele dia.
- **Cálculo Automático de Duração:**
  - O sistema calcula a duração de cada OS com base nos horários de início e término.
- **Cálculo de Horas Restantes:**
  - Mostra o total de horas que faltam para completar as 8 horas diárias de trabalho.
- **Botão Copiar Descrição:**
  - Copia a descrição detalhada da OS, incluindo texto e imagens, para a área de transferência.
- **Visualização de Descrição:**
  - Exibição expandida/retraída das descrições longas, com um botão "Ver mais/Ver menos".
- **Design Responsivo:**
  - Interface amigável, projetada para dispositivos de diferentes tamanhos.

## **Tecnologias Utilizadas**
- **Back-end:**
  - Python com Flask
- **Front-end:**
  - HTML5, CSS3, JavaScript
  - Framework Bootstrap para responsividade
- **Banco de Dados:**
  - SQLite (ou outro banco compatível com Flask)

## **Como Executar**
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/gerenciador-ordem-servico.git

2. Navegue até a pasta do projeto:
   ```bash
   cd gerenciador-ordem-servico
 
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt

4. Execute a aplicação
   ```bash
   python app.py

5. Acesse o sistema no navegador:
   ```bash
   URL padrão: http://127.0.0.1:5000

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

Autor: Matheus Tomaz Dantas
