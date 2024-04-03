---
tags:
  - computer_science
---
Created: 2024-02-26

# Notion de transaction

Une transaction est:: une unité de travail effectuée sur une base de données.
<!--SR:!2024-04-24,21,214-->

Il est important de contrôler ces transactions pour garantir:: la cohérence et l'intégrité des données et gérer les erreurs de la base de données.
<!--SR:!2024-04-24,23,252-->

Par définition, une transaction de base de données doit être (4):: atomique, cohérente, isolée et durable. (ACID)
<!--SR:!2024-05-02,29,272-->


- Si aucune erreur ne s'est produite pendant l'exécution de la transaction, le système valide la transaction et la termine. Une opération de validation de transaction applique toutes les manipulations de données dans le cadre de la transaction et persiste les résultats dans la base de données. Cette opération est communément appelée:: Commit.
<!--SR:!2024-04-25,39,290-->
- Si une erreur survient au cours de la transaction, ou si l'utilisateur spécifie une opération de retour en arrière, les manipulations de données effectuées dans le cadre de la transaction ne sont pas conservées dans la base de données. Une opération est effectuée pour remettre la base de données à son état avant l’exécution de la transaction. Cette opération est communément appelée:: Rollback.
<!--SR:!2024-04-19,31,270-->