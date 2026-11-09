# OPERAÇÃO AGV — Sinal Sob Controle

Plataforma didática gamificada para estudo de **amplificadores operacionais, osciladores e condicionamento de sinais aplicados a um Veículo Guiado Automaticamente (AGV)**.

A aplicação apresenta uma situação-problema industrial: um AGV apresenta falhas de orientação porque o sinal analógico de seu sensor de linha sofre oscilações. O estudante assume o papel de integrante da equipe técnica e percorre uma jornada de investigação, estudo, experimentação, diagnóstico e documentação para transformar esse sinal instável em uma informação confiável para o controlador.

## 1. Objetivo educacional

Desenvolver conhecimentos e capacidades relacionados à análise e ao condicionamento de sinais em sistemas eletrônicos, contextualizando o uso de amplificadores operacionais e circuitos associados em uma aplicação de mecatrônica.

O desafio apresentado parte das seguintes condições:

- O sensor fornece um sinal analógico entre **0,8 V e 3,2 V**.
- O sinal pode sofrer oscilações provocadas por ruído elétrico, sombras, irregularidades do piso e variação de velocidade.
- O controlador do AGV precisa interpretar dois estados: **linha detectada** ou **linha não detectada**.
- A substituição do sensor não é permitida.
- A solução proposta envolve diagnóstico e condicionamento do sinal, sem dispensar os procedimentos de segurança e a validação técnica.

## 2. Público e contexto

O certificado e os textos da aplicação identificam o contexto formativo como:

- **Curso:** Técnico em Mecatrônica — 2º ano do Ensino Médio Técnico.
- **Unidade Curricular:** Sistemas Eletrônicos.
- **Atividade:** Encontro 06 — Projeto Integrador AGV.
- **Tema:** Amplificadores Operacionais e Osciladores aplicados ao AGV.

## 3. Organização pedagógica — MSEP

A experiência está organizada com referências às etapas da Metodologia SENAI de Educação Profissional (MSEP), explicitadas na aplicação:

| Etapa | Aplicação na jornada |
|---|---|
| Contextualização | Apresentação do cenário industrial e do problema de orientação do AGV. |
| Apresentação do desafio | Definição da falha, das restrições e da missão técnica. |
| Organização da aprendizagem | Percurso por módulos, mapa da operação e requisitos de conclusão. |
| Desenvolvimento de capacidades | Estudos, questões, simuladores e atividades de laboratório. |
| Mediação | Dicas conceituais, feedback imediato e acompanhamento do progresso. |
| Análise e avaliação | Checkpoints, análise de falhas, medições e resultados registrados. |
| Síntese e aplicação | Dossiê técnico e integração final da solução. |

A gamificação funciona como apoio ao percurso de aprendizagem. A pontuação e as medalhas não substituem a avaliação por competências, conforme o próprio painel de resultados informa.

## 4. Mapa de módulos

A jornada contém **9 módulos**, numerados de 0 a 8. O avanço é sequencial: o módulo seguinte é liberado após a conclusão do anterior.

| Módulo | Setor | Foco | XP de conclusão |
|---:|---|---|---:|
| 0 | Centro de Comando | O desafio do AGV e avaliação diagnóstica | 20 |
| 1 | Laboratório de Eletrônica Analógica | Amplificadores operacionais | 30 |
| 2 | Documentação Técnica e Osciladores | Datasheet e geração de sinais | 25 |
| 3 | Engenharia de Condicionamento | Comparador, histerese e filtros | 40 |
| 4 | Laboratório de Montagem | Protoboard, organização e inspeção | 30 |
| 5 | Instrumentação e Medições | Fonte, multímetro e osciloscópio | 35 |
| 6 | Central de Diagnóstico | Análise de falhas | 50 |
| 7 | Documentação Técnica | Registros, medições e dossiê | 40 |
| 8 | Integração Final | Missão concluída | 60 |

Cada módulo apresenta conteúdo e um checkpoint. Para concluir um módulo, o estudante deve atender aos requisitos exibidos na própria tela; em geral, isso inclui acertar todas as questões do checkpoint, além de requisitos específicos da atividade quando aplicáveis.

## 5. Recursos e funcionalidades

### Dashboard

- Cadastro do nome do estudante.
- Exibição do nível atual, XP e barra de progresso.
- Indicadores de módulos concluídos, medalhas, medições e checkpoints.
- Atalho para continuar a próxima missão.
- Visualização das conquistas desbloqueadas e pendentes.

### Mapa da Operação

- Visão geral dos nove módulos.
- Identificação dos módulos disponíveis, concluídos e bloqueados.
- Navegação sequencial pela jornada.

### Conteúdo e checkpoints

- Conteúdo didático contextualizado no problema do AGV.
- Ilustrações e diagramas em SVG incorporados ao HTML.
- Questões de múltipla escolha com feedback para respostas corretas e incorretas.
- Possibilidade de tentar novamente uma questão respondida incorretamente.
- Registro de questões já acertadas, evitando pontuação duplicada pela mesma questão.
- Dicas conceituais em módulos que as disponibilizam.
- Indicador dos requisitos necessários para concluir cada módulo.

### Laboratório interativo

A área de laboratório reúne controles e visualizações didáticas para explorar o comportamento de circuitos e sinais, incluindo:

- **Comparador:** ajuste de tensão de entrada e tensão de referência para observar o estado da saída.
- **Gerador de sinais:** ajuste de frequência, amplitude e ciclo de trabalho (*duty cycle*).
- **Osciloscópio didático:** ajuste de escala vertical (V/div) e base de tempo (tempo/div), com visualização da forma de onda.
- **Comparador com histerese:** ajuste dos limiares superior e inferior e comparação das comutações com e sem histerese.

As simulações são recursos didáticos da página. Elas não substituem a montagem física, a consulta aos datasheets dos componentes nem as medições em equipamentos reais.

### Inventário e conquistas

O inventário apresenta as medalhas e estatísticas acumuladas. Entre as conquistas previstas estão:

- Primeira Missão.
- Mestre dos Terminais.
- Leitor de Datasheets.
- Caçador de Ruídos.
- Guardião da Segurança.
- Mestre das Medições.
- Detetive de Falhas.
- Engenheiro Integrador.
- Trabalho em Equipe.

As medalhas são desbloqueadas por ações e entregas específicas da jornada.

### Resultados

A tela de resultados apresenta:

- Desempenho por checkpoint.
- Quantidade de acertos e tentativas.
- Situação de conclusão de cada módulo.
- Tabela de medições registradas, quando houver dados.

### Certificado

Após a conclusão dos nove módulos, a aplicação libera a tela de certificado. O documento inclui nome do estudante, identificação da atividade, desempenho, nível, medalhas, capacidades evidenciadas, data e código identificador.

O certificado pode ser impresso ou salvo em PDF. A folha está configurada para **A4 em orientação paisagem**.

## 6. Sistema de gamificação

A pontuação utiliza as seguintes regras:

- Cada questão acertada pela primeira vez concede **10 XP**.
- A conclusão de cada módulo concede a quantidade adicional de XP indicada no mapa.
- O XP de uma questão não é concedido novamente se ela já tiver sido registrada como correta.
- As medalhas são liberadas quando seus critérios são cumpridos.
- O nível do estudante é determinado pelo total de XP.

### Níveis

| XP mínimo | Nível |
|---:|---|
| 0 | Aprendiz de Eletrônica |
| 50 | Analista de Sinais |
| 150 | Investigador Técnico |
| 250 | Projetista de Condicionamento |
| 350 | Técnico de Bancada |
| 450 | Especialista em Diagnóstico |
| 560 | Integrador de Sistemas |

## 7. Como executar

A aplicação está reunida em um único arquivo HTML, com CSS e JavaScript incorporados. Não há etapa de instalação de dependências ou processo de compilação descrito no projeto.

1. Salve o arquivo `deepseek_html_20261109_a46275.html` em uma pasta do computador.
2. Abra o arquivo em um navegador moderno, como Google Chrome, Microsoft Edge ou Firefox.
3. Na tela inicial, informe o nome do estudante.
4. Acesse **Mapa** e inicie o Módulo 0.
5. Siga a sequência, realizando as atividades e os checkpoints.
6. Ao concluir todos os módulos, acesse o certificado e use **Imprimir / Salvar PDF**.

> **Recomendação:** utilize um computador com navegador atualizado. A interface adapta parte do layout a telas menores, mas as atividades de laboratório e a leitura de diagramas são mais confortáveis em uma tela maior.

## 8. Salvamento e dados do estudante

O progresso é armazenado no `localStorage` do navegador, utilizando a chave `operacao_agv_v6`.

São armazenados localmente dados como:

- Nome do estudante.
- XP e medalhas.
- Módulos concluídos.
- Respostas corretas e resultados dos checkpoints.
- Medições registradas.
- Reflexões, verificações de segurança e informações do dossiê.
- Data de conclusão usada na emissão do certificado.

**Importante:**

- Os dados ficam associados ao navegador e ao perfil de usuário em que a aplicação foi aberta.
- Limpar os dados do navegador, utilizar outro perfil ou abrir a aplicação em outro dispositivo pode fazer com que o progresso não esteja disponível.
- O arquivo não implementa, por si só, sincronização em nuvem, banco de dados central ou gerenciamento de turmas.
- Em laboratório compartilhado, cada estudante deve utilizar um perfil de navegador separado ou reiniciar a jornada antes de começar.

### Reiniciar a jornada

No Dashboard, a área **Configurações** oferece a opção **Reiniciar jornada**. Essa ação apaga o progresso armazenado para a aplicação naquele navegador e inicia uma nova jornada.

## 9. Segurança e uso em laboratório

A aplicação apresenta orientações de segurança relacionadas às atividades práticas. Durante qualquer montagem ou teste físico:

- Desligue a alimentação antes de modificar conexões.
- Não energize circuitos sem autorização do professor.
- Realize inspeção cruzada das conexões.
- Consulte o datasheet do componente utilizado.
- Respeite os limites elétricos dos componentes e dos instrumentos.
- Execute montagens e medições sob supervisão do instrutor.

As simulações da plataforma devem ser tratadas como apoio ao estudo, e não como autorização para executar uma montagem real sem análise e supervisão.

## 10. Tecnologias utilizadas

Com base na estrutura do arquivo:

- **HTML5:** estrutura e conteúdo da aplicação.
- **CSS3:** identidade visual, layout responsivo, animações e regras de impressão.
- **JavaScript:** navegação, lógica dos módulos, checkpoints, pontuação, simulações e persistência local.
- **SVG:** diagramas e ilustrações vetoriais dos circuitos e da arquitetura do AGV.
- **Canvas 2D:** renderização de formas de onda e visualizações do laboratório.
- **Web Storage (`localStorage`):** armazenamento local do progresso.

A aplicação não apresenta dependências externas obrigatórias no arquivo analisado.

## 11. Estrutura técnica

O arquivo HTML concentra os elementos da aplicação:

- Estilos e identidade visual na seção `<style>`.
- Constantes, níveis, medalhas e referências MSEP.
- Biblioteca de ilustrações SVG.
- Definição dos módulos, conteúdos, questões e requisitos.
- Estado da aplicação e funções de persistência.
- Funções de renderização das telas.
- Funções de interação, simulação e impressão do certificado.

O roteamento interno utiliza a URL com fragmentos (`hash`) para representar as telas e o módulo atual.

## 12. Limitações e observações

- O progresso é local ao navegador; não há autenticação ou sincronização entre dispositivos.
- O certificado é gerado no próprio navegador e sua impressão depende das configurações do diálogo de impressão.
- A pontuação é um mecanismo de acompanhamento e engajamento, não uma medida suficiente, isoladamente, para atestar domínio prático.
- As simulações são representações didáticas e não substituem equipamentos, circuitos físicos ou validação experimental.
- A aplicação foi analisada como um arquivo HTML autônomo; este README descreve as funcionalidades identificadas no código e não representa uma certificação formal de validação pedagógica, elétrica ou de compatibilidade em todos os navegadores.

---

**Projeto:** OPERAÇÃO AGV — Sinal Sob Controle  
**Tema:** Amplificadores Operacionais e Osciladores aplicados ao AGV  
**Contexto formativo:** Técnico em Mecatrônica — Unidade Curricular Sistemas Eletrônicos  
