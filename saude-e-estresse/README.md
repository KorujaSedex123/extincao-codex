# Saúde e Estresse

## Mente e Corpo

Em Extinção, morrer não é o pior destino. Você pode sobreviver com o corpo intacto, mas com a mente estilhaçada.

***

### 1. Saúde Física (PV)

Os **Pontos de Vida** representam a integridade física do seu corpo. Ferimentos de bala, mordidas profundas e cortes sangrentos reduzem seus PVs.

#### Cálculo

> **PV MÁXIMO = (Constituição x 3) + 10**

#### A Beira da Morte (0 PV)

Se seus PVs chegarem a **zero**, você não morre instantaneamente. Você entra no estado **"Caído"**.

1. Você não pode realizar ações.
2. Você ganha um **Ferimento Persistente** (veja a tabela abaixo).
3.  Se sofrer qualquer dano adicional enquanto estiver a 0 PV, você morre.

    <div data-gb-custom-block data-tag="hint" data-style="danger" class="hint hint-danger"><p><strong>Dano Massivo:</strong> Se um único ataque causar dano maior que <strong>metade da sua vida total</strong>, você deve fazer um teste de Constituição (1 Sucesso) ou desmaiar de choque imediatamente.</p></div>

    \---

### 2. Resistência e Fôlego (PR)

Os **Pontos de Resistência** são seu "escudo" de exaustão. Eles representam adrenalina, fôlego e hematomas superficiais.

#### Cálculo

> **PR MÁXIMO = (Constituição + Vontade) x 5**

#### Como funciona?

* **Escudo de Dano:** Danos não-letais (socos, quedas curtas, empurrões) são descontados primeiro do PR. Se o PR acabar, o dano passa a ir para o PV.
* **Esforço Heroico:** Você pode gastar **5 PR** voluntariamente para adicionar **+1d6** em um teste físico desesperado (correr, segurar uma porta).

***

### 3. O Sistema de Estresse

O apocalipse desgasta a mente. Monstros, violência extrema e desesperança geram **Estresse**.

#### O Teste de Medo

Sempre que encontrar uma situação aterrorizante, role sua **Vontade (d6)**.

* **Sucesso:** Você engole o medo.
* **Falha:** Você ganha **+1 Ponto de Estresse**.

#### A Escala da Loucura

O Estresse acumula. Não há como fugir dele facilmente.

| Nível de Estresse | Efeito                                                         |
| ----------------- | -------------------------------------------------------------- |
| **1 a 3 Pontos**  | **Ansiedade:** Mãos trêmulas, suor frio. Apenas interpretação. |
| **4 a 5 Pontos**  | **Abalado:** -1d6 em todos os testes Mentais e de Tiro.        |
| **6 Pontos**      | **COLAPSO:** O personagem quebra.                              |

### 4. Recuperação

No fim do mundo, curar é lento.

{% tabs %}
{% tab title="Descanso Curto" %}
**Tempo:** 1 Hora (Seguro).

* **PR:** Recupera 100%.
* **Estresse:** Recupera 1 ponto se tiver um vício/conforto.
* **PV:** Não recupera. Estanca sangramentos.
{% endtab %}

{% tab title="Descanso Longo" %}
**Tempo:** 8 Horas de Sono (Abrigo Seguro).

* **PR:** Recupera 100%.
* **Estresse:** Recupera 2 pontos.
* **PV:** Recupera **1d6 + Constituição** (com suprimentos médicos).
{% endtab %}

{% tab title="Cirurgia/Tratamento" %}
Requer kit médico e teste de Medicina.

* Cura ferimentos persistentes ou danos críticos.
* Recupera PV baseado nos sucessos do médico.
{% endtab %}
{% endtabs %}

***

### Apêndice: Tabelas de Consequência

#### Tabela de Ferimentos Persistentes

_Role 1d6 quando cair a 0 PV. A penalidade é **-2d6** na ação listada._

| d6    | Ferimento              | Penalidade (-2d6)                               | Cura                |
| ----- | ---------------------- | ----------------------------------------------- | ------------------- |
| **1** | **Concussão**          | Inteligência e Percepção.                       | 3 Dias.             |
| **2** | **Perna Quebrada**     | Correr e Esquiva (Velocidade caiu pela metade). | 2 Semanas + Tala.   |
| **3** | **Braço Quebrado**     | Armas de duas mãos e Força.                     | 2 Semanas + Tala.   |
| **4** | **Costelas Trincadas** | Resistência (PR não recupera).                  | 1 Semana.           |
| **5** | **Infecção**           | -1d6 em TUDO (Febre).                           | Antibióticos Raros. |
| **6** | **Cicatriz Horrenda**  | Interação Social (Carisma).                     | Permanente.         |

#### Tabela de Traumas Mentais

_Ganho após um Colapso. Impõe **-2d6** quando o gatilho ocorre._

| Trauma             | Gatilho / Efeito                                |
| ------------------ | ----------------------------------------------- |
| **Paranoia**       | Não aceita ajuda (dados extras) de aliados.     |
| **Gatilho Sonoro** | Congela ao ouvir sons altos (tiros/gritos).     |
| **Mãos Trêmulas**  | Penalidade em mira fina ou cirurgia.            |
| **Insônia**        | Começa o dia com metade do PR máximo.           |
| **Fobia**          | Escolha uma (Escuro, Sangue, Lugares Fechados). |
