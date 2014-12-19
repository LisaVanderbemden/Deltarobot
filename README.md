#Deltarobot

##Servomotoren aansturen zonder complexe wiskunde: 

**Main.vi** = Aansturen van 4 servomotoren d.m.v. een PWM signaal (maakt gebruik van subVI Servo berekening). 

**Servo berekening.vi** = Berekening van de dutycycle en frequentie.Deze subVI wordt aangeroepen in Main.VI.

**Demo =** http://youtu.be/dF81HX-Wyzg?list=UUNbzHYhRnnWQ4kQRG5y_mZA


##Servomotoren aansturen met wiskunde: 

**test.vi** = Grenzen van deltarobot testen (maximum, minimum en nulwaarde).

**berekeningdutycycle.vi** = Graden omzetten naar dutycycle. 

**wiskunde.vi** = Programma met wiskunde geïmplementeerd.(Nog niet getest)

**inv kin.vi** = Deze subVI wordt gebruikt om de gegevens van de Deltarobot in te voeren(lange arm, korte arm, platform,...).
