# Progetto di Data Mining and Organization

Il data set contiene 454 record relativi a studenti di 7 coorti del CdS Informatica della Scuola di SMFN. 
Ogni record ha i seguenti attributi: Coorte, Genere, Voto_test, Crediti_totali, Crediti_convoto, Voto_medio,
Scuola_provenienza,	ASD, data_ASD, ARC, data_ARC, PRG, data_PRG, AN1, data_AN1, MDL, data_MDL, ING, data_ING

In particolare, per ogni coorte si hanno i risultati della produttivita' fino a dicembre dell'anno successivo all'anno di immatricolazione:

immatricolati coorte 2010 - produttivita' fino a dicembre 2011
immatricolati coorte 2011 - produttivita' fino a dicembre 2012
immatricolati coorte 2012 - produttivita' fino a dicembre 2013
immatricolati coorte 2013 - produttivita' fino a dicembre 2014
immatricolati coorte 2014 - produttivita' fino a dicembre 2015
immatricolati coorte 2015 - produttivita' fino a dicembre 2016
immatricolati coorte 2016 - produttivita' fino a dicembre 2017

Nota sui crediti:
I Crediti_convoto sono crediti che corrispondono ad esami con attribuzione di voto, eventualmente anche riconoscimenti da altri CdS.
I Crediti_totali comprendono i crediti con voto, quelli di esami per i quali non e' previsto un voto e quelli di eventuali 
riconoscimenti da altri CdS senza riattribuzione del voto.

Nota sul test:
- negli anni 2010-2015, il test di autovalutazione della Scuola di SMFN era costituito da un questionario con 25 domande: 
ogni risposta corretta era valutata 1 e ogni risposta sbagliata o non data era valutata 0; il test risultava superato con un punteggio >=12.
- dal 2016, il test di autovalutazione della Scuola di Scienze e' costituito da un questionario con 20 domande:
ogni risposta corretta viene pesata con valore 1 mentre ogni risposta sbagliata o non data con -0.25; il test risulta superato con punteggio >=8.

Legenda per Scuola_provenienza

LS = Liceo Scientifico
LC = Liceo Classico
IT = Istituto Tecnico Industriale
TC = Istituto Tecnico Commerciale
IP = Istituto Professionale
AL, XX, etc = Altro

Legenda per esami primo anno Informatica

ASD Algoritmi e Strutture Dati
ARC Architetture degli elaboratori
An1 Analisi I: Calcolo Differenziale ed Integrale
ING Inglese
MDL Matematica Discreta e Logica
PRG Programmazione
