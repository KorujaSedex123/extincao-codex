# Saúde e Estresse

## Mente e Corpo

Em **EXTINÇÃO**, morrer não é o pior destino. Você pode sobreviver com o corpo intacto, mas com a mente estilhaçada pelo horror.

***

### 1. Saúde Física (PV)

Os **Pontos de Vida** representam a integridade estrutural do seu corpo. Ferimentos de bala, mordidas profundas e cortes sangrentos reduzem seus PVs.

#### Cálculo
> **PV MÁXIMO = (Constituição x 3) + 10**
> *(Exceção: O Defeito Frágil calcula como `(CON x 2) + 5`)*

#### À Beira da Morte (0 PV)

Se seus PVs chegarem a **zero**, você não morre instantaneamente; você entra no estado **"Caído"**:

1. Você cai no chão incapacitado e não pode realizar Ações Principais nem Correr.
2. Você ganha imediatamente um **Ferimento Persistente** (veja a tabela abaixo).
3. Se sofrer qualquer dano adicional enquanto estiver a 0 PV, você morre na hora.

{% hint style="danger" %}
**Dano Massivo:** Se um único ataque causar dano igual ou superior a **metade da sua vida total**, você deve fazer imediatamente um teste de Constituição (Dificuldade 1) ou desmaiar de choque traumático na hora.
{% endhint %}

---

### 2. Resistência e Fôlego (PR - Stamina)

Os **Pontos de Resistência** são sua reserva de fôlego, adrenalina e reflexos motores.

#### Cálculo
> **PR MÁXIMO = (Constituição + Vontade) x 5**

#### Como Funciona?
* **Escudo contra Nocaute:** Danos não-letais (socos, quedas curtas, empurrões) são descontados primeiro do PR. Se o PR zerar, o alvo desmaia.
* **Manobras de Adrenalina:** Gaste **5 PR** para ativar manobras táticas: **Mira Rápida** (-1 Dificuldade), **Esquiva Reativa** (contestar ataques) ou **Esforço Heroico** (+1d6).
* **Condição de Exaustão (0 PR):** Ao atingir zero PR, o sobrevivente fica ofegante: perde a capacidade de correr e sofre -1d6 em Atletismo e Esquiva.

---

### 3. O Sistema de Estresse e Pânico

O apocalipse corrói a sanidade. O Estresse no **EXTINÇÃO** não é apenas um contador passivo: ele é o termômetro biológico entre o instinto de sobrevivência acelerado pela adrenalina e a ruptura caótica da mente.

#### Como o Estresse Aumenta?
O sobrevivente acumula pontos de Estresse (de 0 a 6) por duas vias:
1. **Decisão Tática (Forçar o Limite):** Ao falhar em um teste crucial, o jogador pode marcar **+1 Estresse** voluntariamente para travar os sucessos e rerrolar todos os dados restantes (veja em Mecânicas Básicas).
2. **O Teste de Medo e Choque:** Diante de horrores extremos (ver um aliado ser devorado vivo, sofrer Dano Massivo, puxar o gatilho no "Tiro de Misericórdia" de um amigo ou ficar no breu total cercado por infectados), o Controlador exige um teste de **VONTADE (Dificuldade 1)**:
   * **Sucesso (pelo menos um '6'):** Você cerra os dentes e mantém o controle.
   * **Falha (zero sucessos):** Você marca **+1 Ponto de Estresse**.
   * **Glitch:** Você marca **+2 Pontos de Estresse** e entra em espasmo nervoso imediato.

---

#### A Gangorra Biológica: A Escala do Estresse (0 a 6)

| Nível de Estresse | Estado Mental | Efeito Mecânico no Jogo |
| :---: | :--- | :--- |
| **0 Pontos** | **Lúcido** | Controle absoluto. Sem penalidades ou bônus. |
| **1 a 3 Pontos** | **Adrenalina Primitiva (Luta ou Fuga)** | O fluxo de adrenalina acelera os músculos. Ganha **+1d6 em rolagens de Fuga e Força Bruta** (*Atletismo* e *Briga*). Em contrapartida, fica proibido de realizar ações delicadas sob pressão (como ganzuar fechaduras no meio do combate). |
| **4 a 5 Pontos** | **Abalado & Visão de Túnel** | O cortisol satura o cérebro. Tremores intensos e hiperventilação. Sofre **-1d6 em testes de Precisão, Intelecto e Calma** (*Tiro*, *Medicina*, *Mecânica*, *Percepção* e *Lábia*). **Proibido de Forçar o Limite em testes mentais ou de tiro.** *(Mantém o +1d6 em Briga/Atletismo por puro desespero animal)*. |
| **6 Pontos** | **COLAPSO MENTAL** | A mente atinge a ruptura. Sofre crise imediata na cena, perde metade do PR atual e ganha 1 Trauma Permanente, a menos que decida **Sacrificar sua Âncora Moral** (amortecendo para 3 de Estresse). |

---

#### ⚡ A Rolagem de Espasmo Nervoso (`1d6 + Estresse Atual`)

Sempre que você **ganhar 1 ponto de Estresse enquanto estiver em combate, fuga ativa ou perigo iminente** (ou ao rolar um Glitch ao Forçar o Limite), o choque neurológico atinge seu corpo.

O jogador rola na hora:
$$\mathbf{\text{Espasmo}} = \mathbf{1d6} + \mathbf{\text{Nível Atual de Estresse}}$$

| Resultado | Reação Fisiológica | Efeito Mecânico Imediato na Cena |
| :---: | :--- | :--- |
| **2 a 5** | **Frio na Espinha** | O coração dispara, mas você engole o pânico e **mantém o controle total**. |
| **6** | **Tremor Muscular Severo** | Espasmos motores involuntários. Você **derruba imediatamente** o que estiver segurando (lanterna, arma, faca) ou sofre **-1d6** na sua próxima ação. |
| **7** | **Dedo Nervoso / Espasmo de Som** | Se estiver empunhando arma de fogo engatilhada, você dispara um tiro involuntário a esmo (**consome 1 uso do `Ud` de munição** e adiciona **+1 Tique no Relógio da Horda**). Se estiver corpo a corpo, chuta um cano ou bate em algo metálico (+1 Tique). |
| **8** | **Hiperventilação e Sufoco** | A garganta fecha e falta ar. Você perde imediatamente **5 Pontos de Resistência (PR)** por esforço pulmonar agudo. |
| **9** | **Congelamento por Choque (Freeze)** | O medo te paralisa no lugar de olhos arregalados. **Sua Defesa cai para 0** e você não pode realizar ações principais no próximo turno, até que um aliado gaste uma ação para te sacudir e gritar com você. |
| **10** | **Fúria Cega (Berserker / Fight)** | Uma raiva assassina e incontrolável consome sua mente! Você avança para estraçalhar o inimigo mais próximo com ataques viscerais, ignorando a própria segurança (proibido de recuar, buscar cobertura ou se esquivar). Esse frenesi **só termina quando o alvo morrer** OU se um aliado gastar uma ação principal para te imobilizar e acalmar (`Vontade + Lábia` Dif 1). |
| **11** | **Pânico Primal e Fuga (Flight)** | O pavor vence o raciocínio. Você solta um berro ensurdecedor de terror (**+2 Tiques no Relógio da Horda**) OU gasta todo o seu próximo turno em disparada desesperada na direção oposta, sem olhar para trás. |
| **12 ou mais** | **COLAPSO MENTAL INSTANTÂNEO** | A mente estilhaça completamente na hora. O personagem entra em Colapso Imediato (veja detalhes adiante) a menos que queime sua Âncora na hora. |

---

### 4. Recuperação e Cuidados Médicos

No apocalipse, remédios e ataduras limpas valem mais que ouro.

{% tabs %}
{% tab title="Primeiros Socorros" %}
**Tempo:** 5 a 10 Minutos (Logo após o confronto).
* **Efeito:** Trata ferimentos leves e estanca hemorragias ativas, recuperando **1d6 PV**.
* **A Regra de Ouro:** Apenas **uma única tentativa de Primeiros Socorros por personagem ferido** após cada combate ou cena de trauma. Não pode ser repetido em sequência para "encher a barra de vida".
* **Custo:** Rola o Dado de Uso (`Ud d6`) do Kit de Primeiros Socorros ao término do curativo.
{% endtab %}

{% tab title="Descanso Curto" %}
**Tempo:** 1 Hora (Em área segura).
* **PR:** Recupera 100% da Stamina.
* **Estresse:** Recupera 1 ponto se tiver um vício, conforto ou interagir com um aliado de Vínculo.
* **PV:** Não recupera PV naturally. Estanca sangramentos.
{% endtab %}

{% tab title="Descanso Longo" %}
**Tempo:** 8 Horas de Sono (Refúgio Seguro com vigias).
* **PR:** Recupera 100%.
* **Estresse:** Recupera 2 pontos (ou +2 se interagir com sua Âncora).
* **PV:** Recupera **1d6 + Constituição** (se houver comida e água garantidas).
{% endtab %}

{% tab title="Cirurgia e Tratamento" %}
**Tempo:** Requer Kit Cirúrgico (`Ud d8`), ambiente limpo e teste de **Medicina**.
* Cura ferimentos persistentes ou fraturas ósseas.
* Recupera PV adicional com base nos sucessos do médico cirurgião.
{% endtab %}
{% endtabs %}

---

### Apêndice: Tabelas de Consequência

#### Tabela de Ferimentos Persistentes
_Role 1d6 quando cair a 0 PV. A penalidade é **-2d6** na ação listada até que seja tratada com Medicina._

| d6 | Ferimento | Penalidade (-2d6) | Tratamento e Recuperação |
| :---: | :--- | :--- | :--- |
| **1** | **Concussão Cerebral** | Testes de Inteligência e Percepção. | 3 Dias de repouso absoluto no escuro. |
| **2** | **Perna Fraturada** | Movimento pela metade; proibido Correr e -2d6 em Esquiva. | 2 Semanas com tala e apoio. |
| **3** | **Braço Quebrado** | Proibido armas de duas mãos; -2d6 em Força com esse braço. | 2 Semanas imobilizado com tipoia. |
| **4** | **Costelas Trincadas** | A dor trava a respiração: PR Máximo cai pela metade. | 1 Semana sem combate pesado. |
| **5** | **Infecção Oportunista** | Febre bacteriana secundária (-1d6 Físico). | Tratamento com Antibióticos (`Ud d6`). |
| **6** | **Cicatriz Lacerante** | Marca física hedionda no rosto ou tórax. | Permanente (gera respeito ou repulsa social). |
