# Treinamento-RPG-MAKER

## Eventos:

### Desativar sensor = desativar corrida - propriedades do mapa

### Transferencia = teletransporte (troca de mapa)

### Porta = porta + transferencia (entrar em locais)

### Tesouro = baú

### pousada = npc que cura toda a vida mediante a um custo

## Tranferencia:
<p>Localização: seleciona para qual mapa ou local do mapa ele ~e teletransportado.</p>
<p>Direção: direção de onde o pesonagem estará olhando.</p>

## Porta:
<p>Seleciona o sprite da porta e onde ela vai levar o personagem.</p>

## Tesouro:
<p>Seleciona o sprite do baú e o conteudo dentro, pode ser ouro(moeda do jogo), item, arma ou armadura.</p>
<p>Tem como alterar com eventos e colocar mais coisas dentro de um baú.</p>

## Pousada:
<p>Seleciona o preço.</p>

## Moviento autonomo:
<p>Movimentação do evento</p>
<p>Reparado = parado</p>
<p>Aleátorio</p>
<p>Abordagem = seguir o protagonista se estiver na mesma tela</p>
<p>Habitual = definido pelo usuário(como um macro)</p>

## Opções:
<p>Relacionamento com a animação do evento(sprites)</p>
<p>Caminhando: enquanto caminha vai ficar mostrando os sprite de andando</p>
<p>Pisando: Marcha, troca de pernas na animação do sprite</p>
<p>Direção fisica: sprite nao muda, fica olhando somente para frente.</p>
<p>Atraves: vira um fantasma com passe livre para andar pelo mapa.</p>

## Prioridade:
<p>Relação da altura do evento em relação ao personagem</p>
<p>Abaixo do personagem: evento no chao</p>
<p>Igual ao personagem: evento colide com o personagem(mesma altura)</p>
<p>Acima do personagem: evento acima do personagem(personagem tera que passar por baixo)</p>

## Disparar:
<p>Define quando o evento sera disparado</p>
<p>Todas as condições fornecidas previamente devem ser supridas</p>
<p>Botão de ação: O jogador precisa apertar o botão de ação para iniciar o evento</p>
<p>Toque do Jogador: O jogador precisa tocar no evento(se movimentar ate o evento)</p>
<p>Toque do evento: O evento tocou no jogador(o jogador pode estar parado)</p>
<p>Execução automatica: O evento ocorre apos todas as codições forem supridas</p>
<p>Paralelo: Funciona de forma paralela(após ser ativo se torna continuo)</p>

## Boa pratica:
<p>Criar um mapa para armazenar todos os eventos</p>

## codigos para texto:
![codigos para texto](./imgs/Captura%20de%20tela%202024-08-21%20161738.png)