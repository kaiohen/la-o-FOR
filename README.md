# declaraçãoFOR
Aprimoramente do codigo, adição CSS para a estilização da pagina. Projeto feito para aprimorar o conhecimento da declaração *"FOR"*.

~~~javascript
function howMany(selectObject) {
      var numeroSelecionadas = 0;
      for (var i = 0; i < selectObject.options.length; i++) {
        if (selectObject.options[i].selected) {
          numeroSelecionadas++;
        }
      }
      return numeroSelecionadas;
    }
    var btn = document.getElementById("btn");
    btn.addEventListener("click", function () {
      alert(
        "Total de opções selecionadas: " +
        howMany(document.selectForm.tipoMusica),
      );
    });
~~~
 Neste trecho do codigo a declaração *"FOR"* esta sendo utilizada para verificar cada opção selecionada no elemento *"select"* e para cada elemento selecionado ele incrementa na variavel *"i"*.

 
## Referências           
- https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Loops_and_iteration
- 
