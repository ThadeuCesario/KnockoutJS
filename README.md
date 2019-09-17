fonte: https://www.youtube.com/channel/UCqS-SJq909eADW2WjWu6QUw
# KnockoutJS

O que é o MVVM?
O Knockout é um padrão de projeto, criado pelo John Gossman um dos arquitetos do WPF.
O MVVM, conceitualmente é o mesmo que o MVP, a diferença é que o MVVM é específico para a arquitetura do WPF, e o MVP não tem plataforma específica.
O MVVM visa estabelecer uma separação de responsabilidade através de uma classe (ViewModel) entre o Modelo de Objetos (Model) e a interface (View) com
a qual o usuário interage.

O que é Observable?
São objetos (observáveis) JavaScript que podem notificar os assinantes (Observadores) sobre mudanças.
*Aplicam o design pattern Observer.

Veja alguns métodos abaixo:

*Lendo
 viewmodel.observable();
 
*Escrevendo
 viewmodel.observable("valor");
 
*Escrevendo(chainning)
 viewmodel.observableA("valor").observableB("valor");
 
*Inscrição em um observer
 Var_subscribe = viewmodel.observable.subscribe(function(novoValor){//Código});
 
*Cancelando uma inscrição
 _subscribe.dispose();
 
*Parametros (extends) e eventos
notify, rateLimit, change, beforeChange