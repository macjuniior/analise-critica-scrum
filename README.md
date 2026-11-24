# Análise crítica da adoção do Scrum na Salesforce.com: a transformação ágil "big-bang" de 2006–2007

> **Nota de contextualização:** Estudo de caso baseado em Fry e Greene (2007), Levitt *et al.* (s.d.) e apresentações posteriores de Greene e Fry (2008).

---

## 1. Introdução e justificativa da escolha do caso

Este trabalho analisa criticamente a adoção do Scrum, na versão adaptada que a empresa chamou de **Adaptive Development Methodology (ADM)**, pela área de Pesquisa e Desenvolvimento da Salesforce.com. O caso é relevante por três razões principais:

1. **Relevância histórica:** É um dos relatos mais citados de transformação ágil em larga escala;
2. **Estratégia ousada:** A empresa optou por uma abordagem incomum, a conversão simultânea de toda a organização (*"big-bang"*), em vez de pilotos graduais;
3. **Pluralidade de fontes:** Existe documentação de natureza distinta sobre o mesmo evento, incluindo um relato de experiência dos próprios protagonistas (FRY; GREENE, 2007) e um caso de ensino da Universidade de Stanford (LEVITT *et al.*, s.d.), o que permite uma leitura menos dependente de uma única voz.

Segundo o relato de experiência, a empresa converteu uma equipe de cerca de **duzentas pessoas** ao método ágil em uma janela de **três meses**, em uma das maiores e mais rápidas transformações do tipo (FRY; GREENE, 2007). Apresentações posteriores falam em cerca de **trinta equipes Scrum** (GREENE; FRY, 2008).

*A análise a seguir estrutura-se em torno das cinco questões propostas no desafio.*

---

## 2. Por que a abordagem ágil, e não a tradicional?

O contexto anterior à mudança reunia sintomas clássicos de esgotamento do modelo sequencial (ROYCE, 1970) em organizações que crescem rapidamente:

* **Feedback tardio:** As funcionalidades só eram avaliadas no fim do ciclo de lançamento.
* **Ciclos longos e imprevisíveis:** As versões tornaram-se mais espaçadas e difíceis de prever. Antes da mudança, a empresa havia desacelerado para cerca de **uma grande versão por ano**, enquanto depois relata uma média de **quatro** (FRY; GREENE, 2007).
* **Queda gradual de produtividade com o crescimento do time:** O processo informal que funcionava com poucas pessoas-chave deixou de escalar.
* **Modelo de negócio:** A Salesforce vende software sob demanda (SaaS). Todos os clientes usam a mesma versão em um serviço hospedado, o que torna o intervalo entre lançamentos um fator competitivo e reduz o custo de distribuir atualizações frequentes. *(Nota: Esta é uma inferência desta análise, coerente com o contexto descrito, e não uma afirmação literal das fontes).*

Sob a ótica de Boehm e Turner (2003), métodos ágeis tendem a ser mais adequados quando há alta taxa de mudança, necessidade de feedback rápido e cultura aberta à autonomia. O caso mostra uma empresa jovem, em crescimento acelerado, com produto de entrega contínua — perfil mais próximo do polo ágil do que o de organizações com requisitos estáveis e rígidos.

> **Ponto crítico:** Segundo o caso de Stanford, os dois executivos que conduziram a mudança queriam iniciar com um piloto, enquanto o diretor de tecnologia, Parker Harris, defendeu uma implantação em larga escala (LEVITT *et al.*, s.d.). A escolha do ágil, portanto, foi consensual; a velocidade e a abrangência da implantação, não.

---

## 3. Por que o Scrum?

O Scrum é um framework leve, empírico, baseado em **transparência, inspeção e adaptação** (SCHWABER; SUTHERLAND, 2020). Sua adequação ao problema da Salesforce pode ser lida pela correspondência direta entre dor organizacional e mecanismo do framework:

| Problema enfrentado | Mecanismo do Scrum |
| :--- | :--- |
| **Feedback tardio** | Sprints curtos com demonstração e revisão ao final |
| **Imprevisibilidade de prazos** | Cadência fixa e planejamento baseado em velocidade |
| **Perda de produtividade com a escala** | Equipes pequenas, auto-organizadas e interdisciplinares |
| **Falta de visibilidade para a gestão** | Backlog priorizado, *burndown* e reuniões regulares |

Três escolhas de implantação merecem destaque:

1. **Preparação cultural:** Segundo a Scrum Alliance, a empresa não adotou o Scrum cegamente; primeiro educou os funcionários sobre o alinhamento do método com valores que a empresa já possuía (SCRUM ALLIANCE, s.d.).
2. **Uso do próprio Scrum para implantar o Scrum:** Os apresentadores descrevem uma equipe dedicada à transformação com papéis de *Product Owner* e *Scrum Master* assumidos por Fry e Greene, além de uma *wiki* para documentar a adoção (GREENE; FRY, 2007; 2008). Trata-se de uma aplicação reflexiva do princípio de inspecionar e adaptar.
3. **Adaptação contextual:** A empresa nomeou sua versão de **ADM**, o que sugere customização. Ainda assim, mantém o vocabulário e as cerimônias essenciais do Scrum.

> **Ponto crítico:** A literatura distingue o Scrum canônico de adaptações contextuais. Como a empresa não é uma organização de pequeno porte, a adoção exigiu mecanismos de coordenação entre equipes que o guia do Scrum, por si só, não oferece (LARMAN; VODDE, 2010). As fontes consultadas não detalham todos esses mecanismos, o que limita a profundidade da análise neste aspecto.

---

## 4. O resultado final era inovador? Por quê?

Pelo **Manual de Oslo** (OCDE, 2005), é preciso distinguir inovação de produto, de processo, organizacional e de marketing:

* **Inovação organizacional (Sim — núcleo do caso):** A conversão simultânea de toda a área de P&D foi, no relato dos autores, uma decisão deliberada e arriscada, em contraste com a recomendação mais comum de pilotos e expansão gradual. A empresa também tratou a transformação como projeto ágil, com cerimônias, backlog e retrospectivas próprias.
* **Inovação de processo (Sim — grau incremental):** O Scrum já existia; a contribuição da Salesforce foi demonstrar sua viabilidade em escala e em uma empresa de produto SaaS, além de criar a ADM, com métricas e pesquisas internas.
* **Inovação de produto (Indireta):** As fontes consultadas descrevem sobretudo mudanças de processo. Elas relatam, porém, entregas rápidas de funcionalidades, como mais de **sessenta funcionalidades críticas em menos de nove meses** e um tempo médio de cerca de **2,2 trimestres** entre a ideia e o lançamento (GREENE; FRY, 2007), o que sugere que o novo ritmo facilitou a inovação de produto. Não há, nos materiais examinados, evidência direta sobre a qualidade ou originalidade dessas funcionalidades.

### Resultados declarados
* Cerca de **61%** de melhoria na frequência de lançamentos e **38%** de aumento de funcionalidades entregues por desenvolvedor (GREENE; FRY, s.d.).
* Percentuais elevados em pesquisas internas: **87%** dos profissionais de tecnologia afirmavam que sua equipe Scrum era auto-organizada (FRY; GREENE, 2007) e **92%** consideravam a ADM uma abordagem eficaz (GREENE; FRY, 2008).

> **Avaliação metodológica:** Do ponto de vista científico, o resultado é inovador sobretudo como experiência organizacional, não como invenção de método. A força dos dados, porém, é limitada: foram produzidos pela própria empresa, em materiais de divulgação, sem grupo de controle nem auditoria independente. Há ainda possível viés de seleção de indicadores favoráveis e o efeito de entusiasmo típico dos primeiros anos (*efeito Hawthorne*).

---

## 5. Análise crítica do emprego do Scrum

### Pontos fortes
* **Patrocínio executivo forte:** A decisão de converter toda a organização teve apoio da alta direção, condição frequentemente apontada como crítica em transformações ágeis de larga escala (DIKERT; PAASIVAARA; LASSENIUS, 2016).
* **Preparação e comunicação:** A educação prévia sobre valores, o treinamento, a transparência dos dados e a documentação coletiva por *wiki* favorecem a adesão.
* **Aprendizado por inspeção e adaptação:** Pesquisas periódicas com a equipe criaram um ciclo de retroalimentação sobre o próprio processo.
* **Coerência entre método e negócio:** A cadência frequente combina naturalmente com a dinâmica de um produto SaaS.

### Pontos fracos e riscos
* **Risco do *"big-bang"*:** Converter dezenas de equipes de uma vez multiplica o risco de falhas simultâneas, dilui o suporte de *coaching* e impede aprender com um piloto antes de escalar. A literatura de mudança organizacional adverte contra declarar vitória cedo demais e subestimar a resistência (KOTTER, 1995).
* **Percepção de vigilância e sobrecarga de cerimônias:** Comentários coletados nas pesquisas internas indicam que alguns colaboradores sentiam o Scrum como um sistema de monitoramento permanente e que consideravam gastar tempo excessivo discutindo o próprio processo (GREENE; FRY, 2008). Esse é um achado importante: a transparência, valorizada pela gestão, pode ser experimentada como controle pelos times, o que tensiona o princípio da auto-organização.
* **Métricas focadas apenas em eficiência:** Indicadores como funcionalidades por desenvolvedor e frequência de lançamentos podem induzir comportamentos de otimização local quando se tornam metas (STRATHERN, 1997). As fontes não mostram indicadores equivalentes de qualidade técnica, satisfação do cliente ou dívida técnica.
* **Fonte e autoria interessada:** Os autores são os próprios líderes da transformação, o que cria viés de defesa. O caso de Stanford é uma contrapartida valiosa, mas também foi preparado com a participação deles.
* **Generalização limitada:** Trata-se de uma empresa de software, com cultura tecnológica e crescimento acelerado, em um momento específico. Os resultados podem não se repetir em organizações mais hierárquicas ou reguladas.

---

## 6. O que eu faria diferente?

Caso conduzisse uma iniciativa semelhante, adotaria sete medidas preventivas e corretivas:

1. **Combinar piloto e expansão acelerada:** Executar em poucas semanas um piloto de duas ou três equipes para calibrar papéis, métricas e treinamento, e só então escalar. Isso preservaria o ritmo defendido pela direção e reduziria o risco apontado pelos próprios autores.
2. **Definir linha de base e métricas equilibradas antes da mudança:** Incluir qualidade (defeitos escapados, retrabalho), satisfação de clientes e bem-estar das equipes, além de frequência de lançamentos e produtividade.
3. **Tratar explicitamente a percepção de vigilância:** Separar claramente os dados usados para coordenação e aprendizagem dos dados usados para avaliação individual, comunicando essa fronteira com transparência.
4. **Racionalizar as cerimônias:** Medir o tempo gasto em reuniões e ajustar a carga por equipe, reduzindo a sensação de que se discute mais o processo do que o produto.
5. **Investir cedo em práticas técnicas:** Integração contínua, testes automatizados e gestão de dívida técnica sustentam a cadência frequente de lançamentos (BECK *et al.*, 2001).
6. **Buscar avaliação externa:** Contratar ou convidar pesquisadores independentes para validar os resultados, reduzindo o viés de relato.
7. **Preparar a coordenação entre equipes:** Definir desde o início mecanismos de gestão de dependências e de backlog de produto em escala, usando referências como Larman e Vodde (2010) ou, hoje, frameworks de escala consolidados, em vez de resolver os problemas apenas à medida que surgem.

---

## 7. Outros tópicos de interesse

* **Lei de Conway:** Equipes auto-organizadas e interfuncionais tendem a produzir arquiteturas e processos menos fragmentados do que silos funcionais (CONWAY, 1968).
* **Ágil como vantagem competitiva:** Rigby, Sutherland e Takeuchi (2016) argumentam que a agilidade ultrapassa a área de TI e atinge a gestão de produtos. O caso Salesforce se alinha a essa tese ao combinar ritmo de lançamento e estratégia de produto.
* **Gestão da complexidade:** O desenvolvimento de plataformas SaaS em crescimento aproxima-se do domínio complexo de Snowden e Boone (2007), no qual experimentar e adaptar é mais adequado do que planejar integralmente.
* **Primazia da cultura:** O alinhamento prévio com valores corporativos mostra que métodos ágeis dependem de cultura, e não apenas de técnica.

---

## 8. Conclusão

O caso Salesforce mostra que o Scrum pode ser implantado com rapidez e em larga escala, desde que haja forte patrocínio executivo, comunicação transparente e disposição para adaptar o método. Sua principal contribuição é de natureza organizacional: a conversão simultânea de toda a área de P&D, que gerou ganhos declarados de frequência de lançamentos e produtividade. 

As limitações são metodológicas: autoria interessada, ausência de avaliação independente, métricas centradas em eficiência e sinais de desgaste cultural, como a percepção de vigilância e o excesso de reuniões. Uma replicação prudente combinaria a ambição da mudança com piloto inicial, métricas equilibradas e validação externa.

> **Nota metodológica:** Os dados numéricos citados provêm de relatos e apresentações elaborados pela própria empresa e foram lidos em resumos e páginas públicas; recomenda-se conferir os números diretamente nas fontes originais antes da entrega formal do trabalho.

---

## Referências

* BECK, K. *et al.* **Manifesto for Agile Software Development**. 2001.
* BOEHM, B.; TURNER, R. **Balancing Agility and Discipline: A Guide for the Perplexed**. Boston: Addison-Wesley, 2003.
* CONWAY, M. E. How do committees invent? **Datamation**, v. 14, n. 4, 1968.
* DIKERT, K.; PAASIVAARA, M.; LASSENIUS, C. Challenges and success factors for large-scale agile transformations: a systematic literature review. **Journal of Systems and Software**, v. 119, 2016.
* FRY, C.; GREENE, S. Large scale agile transformation in an on-demand world. In: **AGILE 2007 Conference**. IEEE, 2007.
* GREENE, S.; FRY, C. **Unleashing the Fossa: scaling agile in an ambitious culture**. Apresentação, QCon San Francisco, 2008.
* GREENE, S.; FRY, C. **The Year of Living Dangerously: extraordinary results for an enterprise agile revolution**. Apresentação, Scrum Gathering, Chicago, 2008.
* KOTTER, J. P. Leading change: why transformation efforts fail. **Harvard Business Review**, v. 73, n. 2, 1995.
* LARMAN, C.; VODDE, B. **Practices for Scaling Lean and Agile Development**. Boston: Addison-Wesley, 2010.
* LEVITT, R. E.; FRY, C.; GREENE, S.; KAFTAN, C. **Salesforce.com: the development dilemma**. Caso de ensino, Stanford University, s.d.
* OECD; EUROSTAT. **Oslo Manual**. 3. ed. Paris: OECD, 2005.
* RIGBY, D. K.; SUTHERLAND, J.; TAKEUCHI, H. Embracing agile. **Harvard Business Review**, v. 94, n. 5, 2016.
* ROYCE, W. W. Managing the development of large software systems. In: **Proceedings of IEEE WESCON**, 1970.
* SCHWABER, K.; SUTHERLAND, J. **The Scrum Guide**. 2020.
* SCRUM ALLIANCE. **Salesforce: an agile case study**. Artigo, s.d.
* SNOWDEN, D. J.; BOONE, M. E. A leader's framework for decision making. **Harvard Business Review**, v. 85, n. 11, 2007.
* STRATHERN, M. 'Improving ratings': audit in the British University system. **European Review**, v. 5, n. 3, 1997.
