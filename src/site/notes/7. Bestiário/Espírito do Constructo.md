---
{"dg-publish":true,"permalink":"/7-bestiario/espirito-do-constructo/"}
---

```statblock
layout: Basic 5e Layout
columns: 1
forceColumns: true
image: "[[Ancient Black Dragon.jpg]]"
name: Espírito do Constructo
size: Médio
type: Constructo
alignment: Neutro
ac: 13 + o círculo da magia 
hp: 40 + 15 para cada círculo de magia acima do 4°
speed: "9 m (30 ft.)"
stats: [18, 10, 18, 14, 11, 5]
senses: "Visão no escuro 18 m (60 ft.), Percepção passiva 10"
languages: "Entende os idiomas que você falar"
damage_resistances: "Venenoso"
condition_immunities: "[[Enfeitiçado]], [[Exaustão|Exausto]], [[Amedrontado]], [[Paralisado]], [[Envenenado]]"
traits:
  - name: "Corpo Aquecido (apenas Metal)"
    desc: "Uma criatura que atinge o espírito com um ataque corpo a corpo ou que inicia seu turno imobilizando o espírito sofre 1d10 pontos de dano Ígneo."
  - name: "Letargia Empedernida (apenas Pedra)"
    desc: "Quando uma criatura começa o turno dela a até 3 m (10 ft.) do espírito, o espírito pode atacá-la com energia mágica se o espírito puder vê-la. *Salvaguarda de Sabedoria*: CD igual a CD para evitar sua magia. *Falha*: Até o início do próximo turno do espírito, o alvo não pode realizar Ataques de Oportunidade e seu Deslocamento é reduzido pela metade."
actions:
  - name: Ataques Múltiplos
    desc: "O espírito realiza um número de ataques igual a metade do círculo da magia (arredondado para baixo)."
  - name: Pancada
    desc: "*Jogada de Ataque Corpo a Corpo*: Bônus é igual ao seu modificador de ataque mágico, alcance 1,5 m (5 ft.). *Dano*: 1d8 + 4 + o círculo da magia pontos de dano Contundente."
reactions:
  - name: Reação Violenta (apenas Argila)
    desc: "*Gatilho*: O espírito sofre dano de uma criatura. *Reação*: O espírito realiza um ataque de Pancada contra essa criatura, se possível, ou o espírito se move até metade do seu Deslocamento em direção a essa criatura sem provocar Ataques de Oportunidade."
```
