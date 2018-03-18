# Aula TP - 19/Mar/2018


Cada grupo deve colocar a resposta às perguntas dos seguintes exercícios na área do seu grupo no Github até ao final do dia 26/Mar/2018\. Por cada dia de atraso será descontado 0,15 valores à nota desse trabalho.


## Exercícios

### 1\. RGPD (Regulamento Geral de Proteção de Dados)

Na diretoria Aula7 estão disponibilizados os seguintes documentos:
+ Regulamento (UE) 2016/679 (RGPD);
+ Draft da ISO 27552 (_Security techniques - Extension to ISO/IEC 27001 and to ISO/IEC 27002 for privacy management — Requirements and guidelines_).


#### Pergunta P1.1

Cada grupo deverá escolher um dos documentos e efetuar uma pequena análise, de acordo com as regras seguintes:
+ Se o grupo escolher o RGPD, deverá analisar o seguinte artigo do regulamento e escrever um pequeno texto (entre 1/2 e 1 página A4) em que reflita sobre a forma como esse artigo do regulamento pode influir no desenvolvimento do software. Note que o documento tem 173 considerandos iniciais, podendo alguns serem relevantes para esta reflexão.
  - Artigo 5º - Grupos 1, 5, 9
  - Artigo 25º - Grupos 2, 6, 10
  - Artigo 32º - Grupos 3, 7, 11
  - Artigo 83º - Grupos 4, 8, 12
+ Se o grupo escolher o draft do ISO 27552, deverá analisar o seguinte ponto e escrever um pequeno texto (entre 1/2 e 1 página A4) em que reflita sobre as implicações que esse ponto tem no desenvolvimento do software e/ou na operação do mesmo.
  - 6.4 (_Human resource security_) e 6.5 (_Asset management_) - Grupos 1, 5, 9
  - 6.9 (_Operations Security_) - Grupos 2, 6, 10
  - 6.13 (_Information security incident management_) -  Grupos 3, 7, 11
  - 6.15 (_Compliance_) - Grupos 4, 8, 12

Note que a análise deverá apenas ser efectuada a um dos documentos, devendo o grupo escolher qual prefere, de acordo com as regras anteriores.


## 2\. Projeto de desenvolvimento de software

Os alunos deverão utilizar o resto desta aula TP para continuarem o projeto de desenvolvimento de software. **Note que foram adicionados dois pontos ao output desta fase, baseado no RGPD.**

O projeto 1 (Leilões online) será efetuado, em conjunto, pelos grupos 1, 6, 10, 11, 12.

O projeto 2 (Gestor de passwords com base em QrCodes) será efetuado, em conjunto, pelos grupos 2, 3, 4, 5, 7, 8, 9.

- Projeto 1 – Leilões online

  - Leilões online, com entrega de propostas em "carta fechada";
  - Pode ser uma extensão para software open source de leilões online.

- Projeto 2 – Gestor de passwords com base em QrCodes

  - Gestor de passwords, em que com base em QrCode apresentado pelo site, o telemóvel lê o QrCode e envia o user + password para desbloquear o acesso;
  - Pode ser uma extensão para software open source de gestão de passwords.

Nesta primeira fase, os dois grupos de projeto devem definir em traços gerais o projeto e as suas funcionalidades, e pensarem de que modo serão utilizado as técnicas criptográficas no projeto.

Com output desta fase, deverão ter um primeiro draft de:

- definição do projeto e suas funcionalidades,
- etapas e fluxos de comunicação / mensagens, podendo utilizar como exemplo o formato visto no segundo exemplo do voto eletrónico, na aula teórica. Esta componente deve conter um diagrama e uma parte textual de explicação do diagrama,
- **(novo requisito adicionado)** identificar os passos efetuados para a concepção e desenvolvimento do projeto, de forma a seguir os princípios de "_privacy by design_" e "_data minimization_" do RGPD (Regulamento Geral de Proteção de Dados);
- **(novo requisito adicionado)** identificar de que modo o software garante os direitos do titular dos dados, de acordo com o RGPD.

Estes pontos deverão fazer parte também do relatório final do projeto.
