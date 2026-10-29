# Combate e Dano

## Regras de Engajamento

O combate em **EXTINÇÃO** é rápido, letal e visceral. Não há turnos infinitos de "eu bato, você bate". Se você errar o tiro, o infectado avança. Se você hesitar, você é mordido.

### 1. Ataque vs Defesa (A Dificuldade do Alvo)

Em combate contra criaturas e infectados, você monta sua parada de dados com **Atributo + Perícia de Combate**. O tipo de inimigo define quantos **Sucessos ('6')** são necessários na rolagem para acertar o golpe:

| Tipo de Inimigo | Dificuldade (Sucessos Necessários) | Exemplos de Ameaças |
| :--- | :---: | :--- |
| **Lento / Padrão** | **1 Sucesso** | Necróticos comuns, zumbis lentos, civis em pânico. |
| **Rápido / Humano** | **2 Sucessos** | Raivosos (corredores), Fúngicos, soldados humanos e sobreviventes rivais. |
| **Elite / Boss** | **3 Sucessos** | Voláteis, mutações pesadas, líderes veteranos fortemente armados. |

> **Superando Defesas Altas:** Enfrentar alvos de Dificuldade 2 ou 3 apenas com a sorte nos dados é quase suicídio. Os sobreviventes devem usar manobras táticas (Mirar, flanquear, queimar PR para Mira Rápida ou coordenar ataques combinados com aliados) para reduzir a Dificuldade necessária para 1 Sucesso.

***

### 2. O Cálculo de Dano

Aqui é onde o treino supera a força bruta. O dano não é aleatório; ele é letal e calculado:

{% hint style="info" %}
**FÓRMULA DE DANO:** DANO = Nível da Perícia + Dano da Arma + (Sucessos Extras)
{% endhint %}

1. **Nível da Perícia:** Seu conhecimento e técnica letal (Ex: *Armas de Fogo 4* = 4 de dano base da técnica).
2. **Dano da Arma:** O poder de parada do equipamento (Ex: *Escopeta* = Dano 5; *Machado* = Dano 4; *Faca* = Dano 2; *Mãos Nuas* = Dano 0).
3. **Sucessos Extras:** Cada número '6' tirado **além** da Dificuldade exigida adiciona **+1 de Dano**.

#### Combate Desarmado (Mãos Nuas):
* **Contra Humanos:** Causa dano no PR do oponente (o PR de NPCs humanos é igual ao seu PV Máximo). Se o PR zerar, o alvo cai desmaiado.
* **Contra Infectados:** Zumbis não têm PR e não sentem dor. Golpes desarmados não removem PV de infectados, mas servem para a **Manobra de Imobilizar** ou para **Empurrar** (3 metros para trás, quebrando o Abraço da Morte). Para ferir o PV de um zumbi desarmado, exige-se *Soco Inglês* ou a Qualidade *Calejado*.

***

### 3. A Defesa do Sobrevivente: Esquiva Reativa

Quando um infectado ou monstro ataca um sobrevivente:
1. O monstro rola sua parada de ataque (ex: *3d6* para Necróticos, *4d6* para Raivosos). Se obtiver ao menos **um '6'**, o golpe vai acertar.
2. **Esquiva Reativa:** O sobrevivente sob ataque pode declarar imediatamente uma reação gastando **5 PR (Stamina)** para rolar `Destreza + Esquiva`.
   * Se o jogador obtiver sucessos iguais ou superiores aos do monstro, ele se esquiva ou apara o ataque sem sofrer dano.
3. **Se o Ataque Acertar:** Subtraia a **RD (Redução de Dano)** da armadura do sobrevivente. O dano restante atinge diretamente os **PV (Pontos de Vida)**.
   * *Atenção Máxima:* Se pelo menos **1 ponto de dano** romper a armadura e ferir os PVs em um ataque de infectado, o sobrevivente contrai **Infecção Automática**.

***

### 4. Manobras Táticas no Combate (Ações Rápidas & Lentas)

* **Mirar com Calma (Ação Rápida):** Você gasta uma ação rápida para respirar fundo e focar a alça de mira. Seu próximo ataque neste mesmo turno (ou no próximo) tem a Dificuldade reduzida em **-1 Sucesso** (ou ganha +2d6).
* **Assumir Cobertura (Ação Rápida):** Abriga-se atrás de um carro ou barricada, ganhando +1 de Defesa ou RD passiva contra disparos.
* **Mira Rápida (5 PR):** Em seu turno de ataque, queime **5 PR** de adrenalina para reduzir a Dificuldade do ataque atual em **-1 Sucesso** sem gastar ações extras.
* **Vantagem Tática (+2d6):** Flanquear, atacar de terreno elevado ou golpear um alvo caído adiciona **+2d6** à sua parada.
* **Fogo de Supressão (Ação Lenta):** Rebaixa o Dado de Uso (Ud) da arma em 1 nível para impor **-2d6** em todos os ataques dos inimigos na área até a próxima rodada.
* **Defesa Total (Ação Lenta):** Foca 100% em sobreviver. Concede **+2d6** em todas as reações de Esquiva e disputas corporais até o próximo turno.

***

### 5. Manobra de Imobilizar / Agarrar (Grapple do Jogador)

Sobreviventes também podem conter e imobilizar ameaças corpo a corpo gastando uma **Ação Lenta**:

* **O Teste:** Role `Força + Briga`.
  * **Contra Inimigo Humano:** É uma **Disputa Resistida** (`Força + Briga` do atacante vs `Força + Briga ou Esquiva` do defensor). Se o jogador vencer, o alvo é considerado **Imobilizado** (não pode se mover, solta itens das mãos e sua Defesa contra ataques externos cai para zero).
  * **Contra Infectado:** O jogador rola contra a **Defesa do Infectado** (1 Sucesso para Necrótico, 2 para Raivoso). Se passar, o sobrevivente segura o tronco/cabeça do zumbi, impedindo-o de morder ou atacar qualquer pessoa naquela rodada.
* **Custo de Manutenção:** Enquanto estiver imobilizando um alvo, o sobrevivente não pode se mover nem atacar com outras armas (mas aliados podem atacá-lo com Dificuldade 1 ou Execução). Soltar o alvo é uma Ação Livre.
