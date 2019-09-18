az container create --resource-group k8s --file Neo4j.yaml

az container delete --name myContainerGroup --ids "/subscriptions/e4da59ca-11b0-454e-a89a-cd711dea9094/resourceGroups/k8s/providers/Microsoft.ContainerInstance/containerGroups/myContainerGroup"

https://neo4j.com/graphgists/

:play https://portal.graphgist.org/graph_gists/bank-fraud-detection/graph_guide