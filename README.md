# Autopreis

Wenn man ein Auto verkaufen will, ist es wichtig zu wissen, was das Auto noch Wert ist bzw. welchen Preis man für das Fahrzeug noch verlangen kann. Da viele Menschen aufgrund persönlicher Erlebnisse ihrem Fahrzeug den Wert falsch einschätzen, ist es wichtig, das Fahrzeug objektiv zu bewerten und beispielsweise mit einer Marktanalyse den Wert festzulegen.


Genau dies wurde in diesem Machine-Learning-Projekts zum Ziel gemacht.
Es wird ein Learner programmiert, der den Verkaufspreis von Gebrauchtwagen aufgrund von objektiven Merkmalen wie  Tachostand, Alter etc. auf Basis von Marktdaten bestimmt. Dabei handelt es sich um eine klassische Regressionsaufgabe. Als Prädiktoren dienen die Merkmale des zu bewertenden Fahrzeugs (km-Stand, Treibstoff, Erstzulassung, etc.); die daraus zu bestimmende nummerische Zielgrösse stellt der Verkaufspreis (Wert) dar.$^1$ 

Der in diesem Projekt verwendete Datensatz stammt von Kaggle und beinhaltet die Daten und Preise von über 370'000 Fahrzeugen, die über die Plattform ebay-kleinanzeigen.de angeboten wurden. Der Datensatz kann unter folgendem Link heruntergeladen werden: <br>
https://www.kaggle.com/orgesleka/used-cars-database#autos.csv <br>


**Hinweis:** Der Datensatz  stammt aus dem Jahr 2016. Die vorhergesagten Verkauspreise beziehen sich deshalb auch auf das Jahr 2016.
