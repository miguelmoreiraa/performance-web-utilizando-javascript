## Carregamento 

-[x] Minificar arquivos (html,css,js)
-[x] Habilitar gzip
-[x] Lazy loading
-[x] Carregue tudo de forma assícrona
-[x] Seletores CSS
-[x] Recursos o Carregamento da página como iframes, laços de repetição
-[x] Lide com imagens com carinho
-[x] Libere logo o carregamento da página e carregue o resto(AFT) 

## Execução - Mão na massa
-[x] Main Thread
-[x] SetTimeout
-[x] RequestAnimationFrame
-[x] RequestIdleCallBack
-[x] Otimizações de CSS via GPU "thread"
-[x] Tome cuidado ao manipular o Dom (Reflow e Repaint)

## Anotaçoes
Laço de repetição trava a página
o documente.element foi usado, mas uma coisa mais pratica de ser usada foi a criação de uma variável dentro do setTimeout para que a pagina seja renderizada mais rapida.
setTimeout usado ali ele meio que agenda uma execução.
deixar as tag script abaixo do html
        
## Código de algumas alternativas usadas        
        // setTimeout(function() {
        //     let content = '';
        //     for (let i = 0; i < 1000; i++) {

        //          content += 'Fui Clicado';
        //     }
        //     $hello.innerHTML = content;
        // }, 100)

        // requestAnimationFrame(function() {
        //     let content = '';
        //     for (let i = 0; i < 1000; i++) {

        //         content += 'Fui Clicado';
        //     }
        //     $hello.innerHTML = content;
        // })

        // requestIdleCallBack(function() {
        //     let content = '';
        //     for (let i = 0; i < 1000; i++) {

        //         content += 'Fui Clicado';
        //     }
        //     $hello.innerHTML = content;
        // })