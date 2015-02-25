---
layout: page
title: Software de Excelente Qualidade
---

Muitas métricas foram criadas pela Engenharia de Software para se tentar medir qualidade em software, mas nenhuma conseguiu trazer luz nem soluções práticas aos problemas no desenvolvimento de software comercial. O Artesanato de Software traz então uma nova abordagem para a qualidade: Aprendemos com os erros de quem pratica o artesanato a mais tempo, identificando padrões e princípios a partir das soluções de diferentes problemas.

# Qualidade não tem medo do Tempo

A métrica mais simples de qualidade utilizada na Engenharia de Software é a que conta quantos dos requisitos previamente levantados foram atingidos. Mas se traçarmos um paralelo com a marcenaria, a qualidade de uma cadeira não é medida por quantas funções ela cumpre com sucesso. É medida sim pelos materiais, procedimentos, design e habilidade do marceneiro que resultam em maior durabilidade e resistência da cadeira. O nível mínimo de qualidade que se espera de um produto é que ele faça o que ele foi projetado para fazer. A métrica real de qualidade então é diretamente proporcional à quanto tempo o produto continua a atender a necessidade do usuário após a sua confecção.

# Qualidade em Software

Existe uma diferença na qualidade da cadeira e do software: a cadeira não precisa mudar com o tempo, já o software tem que ser modificado para continuar atendendo as necessidades do usuário, já que essas necessidades também mudam. Aprendemos com quem está na área a muito tempo que a única constante no desenvolvimento de software é a mudança. Essas mudanças acontecem tanto durante o desenvolvimento quanto depois, na manutenção. Software com qualidade é o software que pode ser modificado facilmente de forma a maximizar sua vida útil, ou seja aumentar o período de tempo no qual atende às necessidades e gera valor para o usuário.

# Software é Código

Software existe para atender as necessidades dos seus usuários, e só pode fazer isso quando está sendo executado. Mas o que define o comportamento sistemático do software é um documento de design altamente técnico e minuciosamente detalhado, o código fonte. O código é o material no qual o artesão trabalha para moldar um sistema, é a qualidade do código que define a qualidade do software.

# Código Ruim

Praticamente todo profissional experiente admite que já teve seu trabalho prejudicado por código ruim. Analisando os erros de experiências anteriores, podemos identificar quatro padrões de sintomas que código ruim causa no software:

## Rigidez

Um sistema rígido é um sistema difícil de ser modificado. Quando uma modificação é feita, outra é necessária para o software continuar funcionando, e quando esta outra é feita, mais outra é necessária, causando um efeito cascata. A rigidez é prejudicial pois faz com que qualquer mudança no software possua consequências imprevisíveis, tornando o planejamento de tempo e esforço impraticável.

## Fragilidade

Um sistema frágil é um sistema no qual uma modificação em um componente causa mau funcionamento em outro aparentemente não relacionado. A fragilidade também causa imprevisibilidade de consequências em qualquer mudança no software, prejudicando o planejamento. Usuários e/ou clientes percebem a fragilidade ao testar o software e podem perder a confiança na qualidade e competência do profissional, já que do seu ponto de vista se há perdido o controle sobre o software.

## Inseparabilidade

Um sistema inseparável é um sistema que não pode ser dividido em componentes reutilizáveis. Esse sintoma indica que atalhos que cruzam componentes foram tomados, provavelmente devido à pressão para entrega. Modificações são feitas do zero ao invés de reutilizar código existente, gerando duplicidade de código. A inseparabilidade prejudica o planejamento porque não se sabe quanto do código existente se pode reutilizar, e quanto terá que ser feito do zero.

## Opacidade

Um sistema opaco é um sistema cujo código é difícil de ser lido por não comunicar a intenção de quem escreveu o código. Seu código fonte é difícil de ler, de entender e de modificar. A opacidade dificulta o planejamento porque, quando não se entende o código, não se sabe quanto tempo levará a modificação, ou mesmo se ela é possível.

#Código Bom

Código bom é o que não gera os sintomas acima no software. Ele tem mais qualidade pois maximiza a vida útil do software facilitando mudanças e extensões. Aprendendo com os erros desenvolvemos Práticas e Princípios, que quando aplicados trazem as seguintes características ao código e ao software:

## Legibilidade

Código bom não é opaco. É simples e direto, pode ser lido como prosa bem escrita. Tem nomes significativos. Parece que foi escrito por alguém que se importa. Pode ser lido e melhorado por um desenvolvedor que não seja o seu autor original. Cada parte do código que você lê é bem aquilo o que você esperava.

## Robustez

Código bom não é frágil. Possui testes unitários que garantem o seu funcionamento. Possui testes de integração que garantem o uso correto de sistemas externos como bibliotecas, frameworks e bancos de dados. Possui testes de sistema que garantem que todos os componentes funcionam em conjunto.

## Flexibilidade

Código bom não é rígido. Cada artefato possui uma única razão para mudar, então uma mudança é feita apenas em um único lugar. Está sempre aberto a extensão, diminuindo mudanças em código existente quando se adicionam funcionalidades. Seus testes automatizados não são acoplados a implementação, dando liberdade para refatorar o modelo do domínio.

## Independência

Código bom não é inseparável. Pode ser dividido em componentes independentes e reutilizáveis. Todas as dependências de fronteira são invertidas, evitando dependências em sistemas externos como bibliotecas, frameworks e bancos de dados, que podem ser substituídos ou atualizados facilmente.

