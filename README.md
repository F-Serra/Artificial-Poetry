# Artificial-Poetry

Generating text with the LSTM for next character prediction at https://github.com/sherjilozair/char-rnn-tensorflow.  
Here are some datasets(mostly german) for training and some results from experimenting with the different sets and hyperparameters.
Click to expand.


<details> 
  <summary>Collection of german cooking recipes - input(rezepte).txt, 3.7 MB: </summary>  
    
spiegelei mit bohnen und speck:
   
eine vorsichtig eine schokolade mit dem einem holzleiten
vorsichtig auf den teig auf 4 prise salz mit dem teig stecken
und mit zucker und salz schmelzen lassen.
mit dem geschmolzen streichen. für eine weiter schälen und ca.
5 minuten gehen lassen. die masse mit salz und pfeffer würzen.
die masse schmelzen lassen. die durchmesser mit backpapier
verteilen. herausnehmen und in der pfanne rösten.  
...
</details>  


<details> 
  <summary>Collection of classical german poems - input(gedichte).txt, 1.6 MB: </summary>
   
   O wie toene, kommen bis die Glieder,     
   und alles, was ziehst du nur zur Nacht  
   und haett gebarsenen Zimmer an.-  
   Wer riecht er ins niedre Spaß.  
   Und es hat es geschleicht, veroffet er zurueck,  
   auch der Hoeflichen Rudmer reich bis auf den Korn!  
   Nun trifft es hinein ins Uhr.  
   Er pfluegt, geliebt noch enge Legenden,  
   erwaehlt’ jeder ein Maedchen allerstoenen.  
   
   Doch wer in ihren Lippen gemach und spricht  
   und knuepft, erfahrt ein Lied.  
   
   Vorbei, verwegnen sie vor, ich hoerte den Paskaphant!  
   Die Schmachsel ist ruhn, die ernste zeigt.  
   Doch bleibts, waerst ein erstes uebergessen hin offen  
   mit heitrem Nachbarschaft mit dumpfem Gott,  
   allein daheim ins Haus erprobt.  
   ...
</details>


<details> 
  <summary>Collection of "The Beatles" song lyrics - input(beatles).txt, 289 KB: </summary>
   
  Jain, love me dell  
  Believe me when I will dirt me  
  Cos I say you’re no monniss at you charks stand  
  When it seems so old creatless hear  
  She got a being yea  
  I can styes my mind and ose you down  
  Yeah when See letter to that everyone  
  I said I’m so tired I’ll day, on, you know my number three  
  you flack time  
  Yeah  
  Can’t show down to regurly (Wouh! Ha! Ovis, yeah!  
  
  Hah I save you, will ”Take good dound  
  Oh, juy it there’s gone there and their leaving with you  
  I’m down (I’m really down)  
  I’m gonna walk a stop to door  
  but it’s still I will find and let her was shilt  
  Saince of mine.  
  Love love!  
  She said shake, rume time when I tell you, be you  
  ...
</details>

<details> 
  <summary>Collection of "Eminem" song lyrics - input(eminem).txt, 2.3 MB: </summary>
   
  I know Rush, and Dr. Dre.  
  You idemed you a famouth they say they’re in the shit,  
  suparts and respect the othourucution was a little bit me  
  But the great wen, ever make you seen  
  asybacling my click of cunt, ”You’re gonna love you...  
  just lied busy motherfucker!”  
  You can send Jergerane’s  
  I got a little bike nose like Lee Jade  
  You’re hately, Fuck Trick!”  
  Be the kneess his lover  
  twice the black in your black Gurse  
  Someone’s in grass, I may cause you chick but  
  and bright out the Uperic, waitin’, fuckin’ up  
  ...
 </details>


<details> 
  <summary>The Bible (ger) - input(bibel).txt, 4.4 MB: </summary>
   
  4,10 Den Friedens werden wir zu suchen hinab vor dem, was  
  ich sie umkommen, die nach Lauten und Abgrund geboten hat  
  in den Berg und machten Rychimr. 29,14 Dem Sohn Salomo hob  
  sich von Mazedonien, (a) G atat an dem Hohenpriester an und  
  sie so die Wonne waren, im Hause von der Stammhogende des  
  HERRN auf  
  dem Hörner des Gesetzes gegen den  
  Chron. 12,59 Auch rief er in der Not, und Laum darauf lebte.  
  29,13 Und Mose schlug nicht das Gebiet Sterbplätze; Jarich aber  
  starb, einen jungen Mann wieder heim  
  von den Eimer einen jungen Stier. 7.5 (a) Und sie zogen mit ihm  
  ein Greuel, und einige Köpfe aber taten  
  ihnen und ein achtete Gold  
  ...
 </details>
 
 
<details> 
  <summary>Goethe's Faust - input(faust).txt, 484 KB: </summary>
   
  MEPHISTOPHELES (zu Graben):  
  Und quilligeWeiße dir dahin!  
  
  FAUST:  
  Eu bitten, dem Gewohn.  
  Gerankt und kann her übersprungen.  
  Wei der Hauplistchen klingt,  
  Da großes Herz, bleibt ein Fangen,  
  Häßlich kennt ihr soll dich trau;  
  Sie türfen, dieWandschlanz und Tüchtaupf  
  Aus Lust hervor an Pudel und ganze Haus,  
  Und wo sei recht!–Das ist Gebräun hinauf.  
  Die Verzärschen Feuerhalk.  
  So unterbreiten gibt.  
  Wenn du als dudend schrein.  
  Was Harn! Erlassend, was den altem Limpf  
  Nun endlich brettere,  
  Reinen öffnen in mein Geister! Soll bei.  
  ...
 </details>

