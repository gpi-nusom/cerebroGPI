# Interações remotas com instrumentos musicais acústicos

## Pessoas envolvidas no Projeto
- [[Esteban Viveros]]
- [[Vitor Kisil]]

## Objetivo Inicial
Instaurar interação remota do usuário com o instrumento musical.

  
  
  

## Resumo do Projeto
Criar interações entre pessoas e instrumentos musicais remotos explorando possibilidades poéticas e técnicas que surgem desse tipo de condicionante a performance musical ou sonora.

No momento a poética é aberta, e devemos explorar possíveis temas em outros documentos com links aqui.

Iniciaremos uma primeira fase, procurando por parcerias e realizando um projeto inicial de interação. No futuro outras fases serão acrescentadas neste documento.


## Palavras Chave
Interação Remota, Luteria Experimental

  

## Metodologia
Pretendemos através de esforço coletivo e procurando parcerias no NuSom e no CompMus viabilizar a infra estrutura técnica para construção de dispositivos (instrumentos automatizados / #luteriaExperimental) comunicação remota via Internet das coisas ou outras formas de comunicação remota necessárias.

É imprescindível documentar e publicar de alguma forma os avanços do projeto através de comunicações acadêmicas em seminários, simpósios, congressos e conferências acadêmicas, assim como em plataforma pública própria \[[site do GPI](https://app.gitbook.com/@gpi-nusom/spaces)\].


## Descrição Detalhada do Projeto

### Primeira Fase
Na primeira fase desse projeto pretendemos implementar um controle por webcam para tocar o instrumento [Risicare](https://gpi-nusom.gitbook.io/documentacao/atividades/eventos/exposicoes/segunda-edicao-sons-de-silicio/descricao-das-obras/risicare-2019) do Vitor Kisil.

Esse instrumento, no momento se toca sozinho. Ele tem 4 ações controladas por um arduino. Assim para viabilizar o nosso projeto precisamos de:
1.  Destrinchar em detalhes as ações que Risicare oferece
	1.  Listar as ações
	2.  Frequência máxima possível para realizar cada ação

2.  Automação de Risicare para ser operado de maneira remota
	1. Código fonte atual do Arduino que controla essas ações
	2. Escrever código para ESP32 ou ESP8266 reimplementando essas ações com controle remoto via:
		1. Rede WiFi local
		2. Por MQTT (sugestão do dj: [http://dweet.io/](http://dweet.io/) )
		3. Podem ser acrescentadas outras formas de controle no futuro

3.  Criação de uma interface web com capacidade de:
	1.  Utilizar a câmera do usuário como sensor para entrada de ações de controle do instrumento Risicare
	2.  Receba o som gerado pelo Instrumento Risicare
		1.  O som gerado pode conter uma composição que soará junto ao som do instrumento tocado de forma remota
		2.  Posteriormente podem ser implementados DSP em webAudio API para modificar o som do instrumento em tempo real.


### Outras Fases

Outras fases podem ser adicionadas conforme formos nos familiarizando com as ferramentas e conhecendo suas potencialidades e limitações.

No momento existem as ideias de:
-   Montar performances com instrumentos musicais automatizados suspensos em espaço público que podem ser tocados de forma remota por dispositivos móveis ou mesmo por interfaces desenvolvidas pelo grupo.


## Documentação de Realizações do Projeto
[Este espaço é dedicado ao registro de espaços atingidos pelo projeto. Pode conter links para artigos de blogs, artigos acadêmicos, registro no site do GPI, repositório git ou qualquer outra espécie de repositório ou site no qual o projeto está hospedado ou foi citado\]

## Documentado por:
- [[Esteban Viveros]]
  
  
  
  

## Log de Alterações
- 12/06/2021 Migração do Google Drive por [[Esteban Viveros]]



