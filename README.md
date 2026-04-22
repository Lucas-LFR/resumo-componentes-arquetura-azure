# resumo-componentes-arquetura-azure

Principais componentes arquitetônicos do Azure

-Descrever os recusos e os grupos de recursos do Azure.
-Descrever as assinaturas.
-Descrever os grupos de gerenciamento
-Descrever a hierarquia de grupos de recusos, assinaturas e grupos de gerenciamento.

REGIÕES
-Nem todos os recursos estão para todas regiões.
-O Azure oferece mais regiões globais do que qualquer outro provedor de nuvem, com mais de 60 regiões representando mais de 140 países.
-As regiões são compostas de um ou mais datacenters muito próximos.
-Eles fornecem flexibilidade e escala para reduzir a latência do cliente.
-As regiões preservam aresidência dos dados com uma oferta abrangente de conformidade.
-Quando uma região toda fica off (DISASTER RECOVERY)

----ETENDENDO PARES DE REGIÃO E GRUPOS DE RECURSOS-----
-No mínimo 300 milhas de separação entre pares de regiões
-Replicação automática para alguns serviços
-Recuperação de região priorizada em caso de interrupção
-As atualizações são distribuídas sequencialmente para minimizar o tempo de inatividade.

REGIÕES SOBERANAS DO AZURE
-Serviços Governamentais dos EUA
-Atende às necessidades de segurança e conformidade das agências federais, governos estaduais e localis dos EUA e seus provedores de soluções.
-Instância separada do Azure.
-Fisicamente isolada de implantações que não sejam do governo dos EUA.
Acessível somente a pessoal verificado e autorizado

GRUPOS DE RECURSOS
-Um grupo de recursos é um contêiner que você usa para gerenciar e agregar recursos em uma única unidade.
-Os recursos podem existir em apenas um grupo de recursos 
-Os recursos podem existir em diferentes regiões.
-Os recursos podem ser movidos para diferentes grupos de recursos.
-Os aplicativos podem utilizar vários grupos de recursos.



