<h1 class="page-title">Conhecendo Python</h1></header><div class="page-body"><p id="9b18a781-fd74-4658-abdf-b9adc2c6eea8" class="">Um exercicio do curso de python na udemy do professor luiz otávio da aula 38 pedio que nós 
fazecimos um comando que pergunta-se dois numeros, e quando colocarmos ele diria qual o 
maior. No começo, quando estamos aprendendo programação parece muito dificil porque parece que não vemos de um jeito facil iqual eles veem. Mais comecei a fazer, e colocarei minha linha de raciocinio aqui.</p><p id="ec6b41cd-7079-4e21-a0e0-7355639b36b7" class="">
</p><p id="c25d2ee5-04b7-4dfe-a8d6-a9638884acc2" class="">Primeiro dividi todo o codigo com anotações, deixei as variaveis vazias, e testei se iria aparecer na tela a pergunta e se ela quardaria a resposta na variavel.</p><pre id="67d5a9b8-3020-491d-af0d-d38f97715af7" class="code"><code>#variaveis

primeiro_valor = ()
segundo_valor = ()
calculo = ()

#pergunta

pergunta = ()

#Comandos Tela
primeiro_valor = input(&#x27;Digite um valor: &#x27;)</code></pre><p id="5d7b7287-2025-4966-b177-55cef0b2b6f8" class="">Percebi que fez a pergunta então coloquei um comando para que eu pudece ver se a resposta fui quardada na variavel.</p><p id="93d65e57-1c60-4859-971c-e7d9349e41a1" class="">
</p><pre id="eb9e51de-a51a-4214-8f39-59e93c3b0f79" class="code"><code>primeiro_valor = input(&#x27;Digite um valor: &#x27;)
print(primeiro_valor)</code></pre><p id="77bbd62a-ac81-4f58-8bd5-9d231c138409" class="">É sim a variavel estava sendo guardada. </p><p id="6aaf1941-e415-4fd3-b76a-a546eeb5d888" class="">Então comecei a implementar o codigo, Vou aplicar if,elif e else.</p><p id="f2d4c088-ac37-4106-9b82-894be8c8b293" class="">Fiz uma estrutura para de if:</p><pre id="ee322557-1272-41cc-bea1-9f305ac46dd9" class="code"><code>#variaveis

primeiro_valor = ()
segundo_valor = ()
maior = (&#x27;o Primeiro valor é maior que o primeiro valor&#x27;)
menor = (&#x27;o Segundo valor é maior que o primeiro valor&#x27;)

#Estrutura da escolha

if primeiro_valor &gt; segundo_valor:
    print(maior)
elif segundo_valor &gt; primeiro_valor:
    print(menor)
else:
    print(&#x27;Os numeros são iguais!&#x27;)

#Comandos Tela
primeiro_valor = input(&#x27;Digite um valor: &#x27;)
segundo_valor = input(&#x27;Digite outro valor: &#x27;)</code></pre><p id="de403e6a-440f-4a47-8081-c2afa7cb31af" class="">O intuito era que a estrura com base na escolha das pessoas, ele colocaria ja programado qual a resposta. ‘if’ se for o primeiro valor ou ‘elif‘ se não outra resposta ou se não for nenhuma das duas
’else’ são iguais.</p><p id="7542887d-e982-477b-9f38-bacbb4458933" class="">Acabou não dando certo então continuei a pensando para acabar o obstaculo e fazendo um codigo limpo.</p><p id="faf1602d-4126-4e92-b25a-b9a3858afe4d" class="">Comecei a refazer o codigo querendo deixar o codigo limpo.</p><pre id="3bdc91ba-775c-4c84-907b-617bbd9486f8" class="code"><code>#variaveis

primeiro_valor = ()
segundo_valor = ()
maior = (&#x27;o Primeiro valor é maior que o primeiro valor&#x27;)
menor = (&#x27;o Segundo valor é maior que o primeiro valor&#x27;)

#Estrutura da escolha

if primeiro_valor &gt; segundo_valor:
    print(maior)
elif segundo_valor &gt; primeiro_valor:
    print(menor)

#Comandos Tela

primeiro_valor = input(&#x27;Digite um valor: &#x27;)
segundo_valor = input(&#x27;Digite outro valor: &#x27;)</code></pre><p id="f447d2f0-a16c-4d01-b477-f6208458eb09" class="">Acabei colocando duas variaveis um do primeiro calculo e uma do segundo calculo. Assim o if e elif saberia qual seria verdadeiro e qual seria o falso. assim apareceria na tela qual as duas opcoes e talvez o codigo ficaria mais limpo.</p><p id="0420e683-6a74-4e8a-a1b5-37f7a7b6089a" class="">Acabei notando que eu poderia colocar na varivel o ‘input’ ou perguntar, na variavel sem deixar ela vazia, isso por ser leigo em programação é um erro que aprenti.</p><p id="a24baf68-ee34-40af-ad53-617d036752eb" class="">Qualquer um que ve seu codigo funcionando mesmo sendo muito facil ja se alegra bastante.</p><p id="2d485cb5-1fe2-4058-8ff9-31bddc946500" class="">O codigo começa a funcionar mesmo sendo um codigo facil.</p><pre id="50a54f94-ae4a-4c5a-988d-2f2df8f7d2da" class="code"><code>#variaveis
primeiro_valor = input(&#x27;Digite um valor: &#x27;)
segundo_valor = input(&#x27;Digite outro valor: &#x27;)

calculo1 = (primeiro_valor &gt; segundo_valor)
calculo2 = (segundo_valor &gt; primeiro_valor)

#Estrutura da escolha

if calculo1:
    print(f&#x27;O primeiro valor = {primeiro_valor} é maior que o segundo valor = {segundo_valor}&#x27;)
elif calculo2:
    print(f&#x27;O segundo valor = {segundo_valor} é maior que o primeiro valor = {primeiro_valor}&#x27;)</code></pre><p id="75f3b19c-222c-4776-b025-105a8ba8209f" class="">
</p><p id="69f41598-d58c-4bdb-9c63-c67c164d7a87" class="">Agora e se os numeros forem iguais?</p><p id="668d44ff-66c2-4e27-908d-26910477e104" class="">Voltei a editar o codigo.</p><p id="83290fc8-fca3-4a93-aa0b-8b6e7f3bf8df" class="">Então acresentei o else no codigo esperando que se for iguais os numero o codigo colocaria na tela.</p><p id="ce2062c7-5a4b-46c8-ad36-4135a357604e" class="">Então finalmente o codigo ficou pronto e funcionando corretamente:</p><pre id="9b7c262e-1c34-4e20-b1d8-40a5fd7c0132" class="code"><code>#variaveis
primeiro_valor = input(&#x27;Digite um valor: &#x27;)
segundo_valor = input(&#x27;Digite outro valor: &#x27;)

calculo1 = (primeiro_valor &gt; segundo_valor)
calculo2 = (segundo_valor &gt; primeiro_valor)

#Estrutura da escolha

if calculo1:
    print(f&#x27;O primeiro valor = {primeiro_valor} é maior que o segundo valor = {segundo_valor}&#x27;)
elif calculo2:
    print(f&#x27;O segundo valor = {segundo_valor} é maior que o primeiro valor = {primeiro_valor}&#x27;)
else: 
    print(&#x27;Os dois valores são iguais&#x27;)</code></pre><p id="5c9e4b5f-4aec-4a29-bd2c-021b1d6bc07d" class="">As vezes falta de conhecimento não seja burise mais sim pregisa de correr atraz de mais informações.</p><p id="73fb33cd-4393-409a-a364-7cfb24cfc91f" class="">
</p></div></article></body></html>
