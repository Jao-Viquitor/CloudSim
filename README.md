## Introdução
Nesta aula prática, utilizamos o CloudSim para simular um ambiente de computação em nuvem, visando compreender suas funcionalidades e benefícios.

## Métodos
1. Instalação do NetBeans.
2. Download e instalação do JDK.
3. Download e configuração do CloudSim.
4. Criação de um projeto no NetBeans e adição do exemplo CloudSimExample1.

## Resultados
Após a configuração, conseguimos executar o exemplo CloudSimExample1 com sucesso, simulando a criação de data centers e a alocação de recursos em um ambiente de nuvem.

## Detalhes da Execução:

```yaml
Starting CloudSimExample1...
Initialising...
Starting CloudSim version 3.0
Datacenter_0 is starting...
Broker is starting...
Entities started.
0.0: Broker: Cloud Resource List received with 1 resource(s)
0.0: Broker: Trying to Create VM #0 in Datacenter_0
0.1: Broker: VM #0 has been created in Datacenter #2, Host #0
0.1: Broker: Sending cloudlet 0 to VM #0
400.1: Broker: Cloudlet 0 received
400.1: Broker: All Cloudlets executed. Finishing...
400.1: Broker: Destroying VM #0
Broker is shutting down...
Simulation: No more future events
CloudInformationService: Notify all CloudSim entities for shutting down.
Datacenter_0 is shutting down...
Broker is shutting down...
Simulation completed.
```

## _Output_

| Cloudlet ID | STATUS  | Data center ID | VM ID | Time | Start Time | Finish Time |
|-------------|---------|----------------|-------|------|------------|-------------|
| 0           | SUCCESS | 2              | 0     | 400  | 0.1        | 400.1       |


## Conclusão

O CloudSim se mostrou uma ferramenta eficaz para a simulação de infraestruturas de computação em nuvem, permitindo uma análise detalhada sem a necessidade de um investimento significativo em hardware real. Esta prática proporcionou uma compreensão valiosa sobre a utilização de frameworks de simulação na pesquisa e desenvolvimento de soluções em computação em nuvem.
