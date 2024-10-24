# Benefícios da Computação em Nuvem

SLA → Service Level Agreement

Um **SLA** (Service Level Agreement) é um acordo formal entre um provedor de serviços e um cliente que define as expectativas de serviço. Ele estabelece os níveis de serviço que o provedor se compromete a oferecer, incluindo:

1. **Objetivos de Desempenho**: Define métricas específicas, como tempo de resposta, tempo de disponibilidade (uptime), e desempenho esperado do serviço.
2. **Responsabilidades**: Especifica as obrigações de ambas as partes, como o que o provedor fará para garantir a qualidade do serviço e o que o cliente deve fazer para facilitar esse processo.
3. **Penalidades e Remediações**: Inclui consequências se os níveis de serviço não forem atendidos, como descontos ou créditos no serviço.
4. **Revisões e Atualizações**: Estabelece como e quando o SLA pode ser revisto ou atualizado, para refletir mudanças nas necessidades ou na tecnologia.

Em resumo, um SLA é essencial para garantir clareza e entendimento mútuo entre o provedor e o cliente, ajudando a manter a qualidade do serviço e a satisfação do cliente.

## Alta disponibilidade

Se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.

## Escalabilidade

A escalabilidade refere-se à capacidade de ajustar recursos para tender à demanda.

A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.

Outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços.

Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa.

Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.

Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual.

## Elasticidade

Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente). EX: Período da Black Friday

Pode-se basear o crescimento repentino através de requisições.

Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão.

Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente ( de maneira automática ou manual)

## Confiabilidade

Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente.

Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo.

Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.

## Previsibilidade

A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo MS Azure Well-Architected Framework. 

O **Microsoft Azure Well-Architected Framework** é um conjunto de diretrizes que ajuda os desenvolvedores a criar aplicações na nuvem de forma eficiente, segura e escalável. Ele se baseia em cinco pilares principais:

1. **Desempenho e Escalabilidade**: Garante que a aplicação funcione bem e possa crescer conforme necessário. Isso envolve escolher os recursos certos e monitorar o desempenho.
2. **Segurança**: Foca na proteção de dados e na aplicação. Inclui práticas como autenticação, controle de acesso e proteção contra ameaças.
3. **Confiabilidade**: Assegura que a aplicação esteja disponível e funcione corretamente. Isso envolve planejamento para falhas, backups e recuperação de desastres.
4. **Eficiência de Custo**: Ajuda a gerenciar os custos operacionais, garantindo que os recursos sejam usados de maneira econômica. Isso inclui monitorar gastos e ajustar recursos conforme necessário.
5. **Exceutibilidade**: Envolve a capacidade de monitorar e entender o comportamento da aplicação. Isso é feito através de logs e métricas, permitindo melhorar continuamente.

Esses pilares ajudam a criar soluções na Azure que são robustas, seguras e alinhadas com as melhores práticas da indústria.

## Segurança

A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.

Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção.

Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você

## Governança

A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação.

Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada

## Gerenciabilidade

Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento.

O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Por exemplo:

- Por meio de um portal da Web
- Usando uma interface de linha de comando
- Usando APIs
- Usando o PowerShell
