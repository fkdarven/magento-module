# Módulo PayPal para Magento 1
![](https://raw.githubusercontent.com/wiki/paypal/PayPal-PHP-SDK/images/homepage.jpg)

Módulo não oficial ! O objetivo é apenas torná-lo compatível com o PHP 7 e corrigir alguns bugs/erros.

Ajustado a referência de arrays, onde no PHP 5 podia ser usado {} para acessar um valor, ex $array{5}, o que foi depreciado a partir do PHP 7.4. Além disso, corrigi um bug onde os descontos oferecidos no Magento não eram interpretados pelo Paypal e o valor integral da compra era considerado, ao invés do com desconto.
