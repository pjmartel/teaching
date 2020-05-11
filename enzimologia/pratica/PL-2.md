
!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>MathJax example</title>
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script id="MathJax-script" async
          src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
  </script>
</head>



#### Prática Laboratorial 1

No seguinte endereço:

(http:/www.ualg.pt)

encontrará uma folha de cálculo com dados de curvas de progresso
para um dado, representando a variação da concentração do produto
ao longo do tempo,para várias concentração do substrato.
Tal como no exercício da aula 1, pretende-se estimar os parâmetros 
cinéticos do enzima, determinando primeiro as velocidades iniciais
para cada concentração e, em seguida, estimand os parâmetros cinéticos
do enizma com base na dependência da velocidade inicial com a concentração
de substrato. No entanto neste caso será comparado o método "empírico"
de determinação das velocidades iniciais (com base na estimação das
tangentes), com o método mais rigoroso baseado na forma integrada da equação de
Michaelis-Menten:

	adfasdfasdfasdf
	
note-se que as grandezas Vmax(app) e Km(app) diferem, em gera, de Km e Vmax,
só sendo numericamente iguais a estes  para o caso em que a deplecção do substrato
é o único factor a afectar a curva de progresso. Inpendentemente da forma 
matemática exacta destas grandezas aparentes, verifica-se a seguinte relação:


                    vi = Vmax(app)*[A]/(Km(app)+[A])
					
e, conhecidos os parâmetros Vmax(app) e Km(app) para cada concentração de [A],
podemos determinar a velocidade inicial correspondente.

A determinação dos parâmetros Km(aap) e Vmax(app) pode ser feita recorrendo 
à seguinte linearização da forma integrada da equação de Michaelis-Menten:

        t/ln([A]o/([A]o-[P]) = 1/Vmax(app)*p/ln([A]o/([A]o-[P])+Km(app)/Vmax(app)

$\sum$
