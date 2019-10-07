# Backend Assessment

# Descrição:

  O teste a seguir é dividido em duas partes que serão avaliadas e deverão utilizar .Net Core. Dado o cenário em que a empresa NFE Now necessita de uma aplicação para cadastrar as notas fiscais por cliente.

# 1ª parte:
  Criar um microserviço para cadastro de NFe de forma síncrona. Os campos para o cadastro da NFe são CNPJ, Endereço, Razão Social, Valor, Número da nota (este deverá ser gerado sequencialmente) e Número de série.
  
# 2ª parte:
  Após um grande investimento em Marketing, o volume de clientes e emissões de NFe subiu consideravelmente. O SAC começou a receber inúmeras reclamações de notas duplicadas.
  
  Segundo a análise, o problema ocorre quando dois ou mais usuários estão tentando cadastrar a mesma nota ao mesmo tempo (uma nota não pode ter o mesmo número de nota e nem o mesmo número de série).
  
  Desenvolva uma segunda versão para o cadastro NFe de forma assíncrona que resolva o problema citado.
    
# Os critérios que serão avaliados:
  - Injeção de depedência
  - Estratégia de testes
  - Lidar com Exceptions e Logs
  - Async
  - Events e Commands
  - Web API
  - Microserviços
  - Nomenclatura
  - Organização de código
  - Padrões de arquitetura
  - Concorrência e Paralelismo
  - Versionamento
