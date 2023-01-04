name: Bug report
about: Report un bug
title: '[Bug]'
labels: ''
assignees: SirLink23
body:
  - type: input
    id: pseudo
    attributes:
      label: Pseudo Discord
    validations:
      required: true
  - type: textarea
    id: what-happened
    attributes:
      label: Que s'est-il passé ?
      description: Dites-nous ce qui est arrivé
    validations:
      required: true
  - type: textarea
    id: what-should-happened
    attributes:
      label: 'Qu''aurait-il dû arriver ?'
  - type: dropdown
    id: server
    attributes:
      label: Serveur
      description: Sur quel projet est-ce arrivé ?
      options:
        - Global
        - Market
        - System
        - Giveaways
