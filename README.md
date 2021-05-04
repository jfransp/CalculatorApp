# CalculatorApp
Calculator app developed in MVVM using LiveData and DataBinding.

To solve the mathematical expressions I've used a personal implementation of the shunting-yard algorithm, adapted as an android library.
(it can be found here: https://github.com/jfransp/ExpressionParserUtil-Android-Library).

The ViewModel communicates directly to the layout xml file through DataBinding, removing the necessity for multiple click
listeners and/or observers that would make the code unnecessarily large given the ammount of buttons and textviews on the screen.
