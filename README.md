# AsteriskCredCardTransformation
A PasswordTransformation class for replacing the first 12 digits of a credit card with Asterisks (*) . It displays the last four digitals of the card.  For use with **Android EditText**.

###To use



```

EditText cardNumber;


cardNumber = (EditText) findViewById(R.id.card_number);
cardNumber.setTransformationMethod(new AsteriskCredCardTransformation());

```


