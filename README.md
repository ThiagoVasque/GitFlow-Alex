# GitFlow-Alex
O Git Flow é um jeito organizado de trabalhar com código de software. Funciona assim:
Temos duas branches principais: a Master, onde fica o código pronto para ser usado, e a Develop, onde fazemos as mudanças.
Quando precisamos fazer algo novo ou corrigir algo, criamos branches específicas, tipo Fix para correções ou Feat para melhorias.
As branches seguem um jeito de nomear, com um prefixo (como Feat ou Fix), número da tarefa ou algo parecido, e uma descrição curta.
Depois de fazer as mudanças, mandamos para a Develop usando um "Pull Request" para que a equipe revise.
Voltamos para a Develop e atualizamos com as mudanças feitas, para manter tudo em ordem.
Com o Git Flow, fica mais fácil trabalhar em equipe e manter o código organizado em diferentes etapas do desenvolvimento.

Master: A branch "master" contém o código de produção estável. É a versão do software que está pronta para ser implantada.

Develop: A branch "develop" é onde o desenvolvimento contínuo ocorre. É usada para integrar funcionalidades e correções de bugs em desenvolvimento.

Feature: Branches de feature são usadas para desenvolver novas funcionalidades. Cada funcionalidade é desenvolvida em uma branch de feature separada e depois mesclada na "develop" quando concluída.

Release: Branches de release são usadas para preparar uma nova versão do software para lançamento. Correções finais e ajustes são feitos aqui antes de mesclar na "master" e "develop".

Hotfix: Branches de hotfix são usadas para corrigir problemas críticos em produção. Quando um bug sério é descoberto, uma branch de hotfix é criada e mesclada tanto na "master" quanto na "develop".

Support (opcional): Branches de support são usadas para fornecer suporte a versões antigas do software, aplicando correções de segurança ou resolvendo problemas em versões mais antigas.
