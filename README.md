# Aesop a tháinig go h-Éirinn
A public domain version of Aesop's Fables in Irish.  

## Aim
Take Peadar Ua Laoghaire translation of Aesiop's Fables to Irish and convert it to modern orthography. Modern spelling. Modern word usage where needed. Create Audio Files of it. And have similar English translation for it as well. 

## Links
[Wikisource of the book](https://wikisource.org/wiki/Aesop_a_th%C3%A1inig_go_h-%C3%89irinn/An_Frog_agus_an_Mada_Rua)

[Audio for 8 stories](https://corkirish.wordpress.com/audio-files-on-this-site/)
[Youtube of more stories](https://www.youtube.com/watch?v=zyi70tG68UM&t=1s) by John Farrell
## Tasks

Story | Have Text | Orthography | Spelling | Words | Audio | English | Words checked 
--- | --- | --- | --- |--- |--- |--- |--- 
An Frog agus an Mada Rua | Y | N | N | N | N | N | N 
An Coileach agus an Mada Rua | Y | N | N | N | N | N | N  
An Giorfhiadh agus an Gealún
An Ḟuiseóg agus a h-Ál
An t-Asal agus an Bia
Na Machtírí agus na Caoíre 
An León agus na Cheithre Tairbh
Na Frogana a’ Lorg Rígh
An Mac agus a Mháthair
An Mada Ruadh sa Tobar
An t-Aṫair Níṁe agus an Portán
An Sealgaire agus an Colúr
An Fear agus a Chlann Mhac
An t-Aodhre agus an Fharge
An Machtíre i gCroicean na Caorach
An Machtíre agus an t-Uan agus an Gabhar
An Luch Tuatha agus Luch an Bhaile Mhóir
An Fhiolar agus an Mada Ruadh
An Frog agus an Luch
An Dá Fhrog
An León, an Beithir, a’s an Mada Ruadh
Geallamhna an Fhir Bhreóite
An Capal agus an t-Asal
An Cromán agus na Colúra
Iupiter agus an Bheach
An Ghráinneóg agus na h-Aithreacha Nimhe
An Sean Phoc agus an Laogh
An León agus an Machtíre agus an Mada Ruadh
An Mada Ruadh agus an Machtíre
Na Giorfhithe agus na Frogana agus an Ghaoith
Bean na Circe
An Áinle agus na h-Éin Eile
An Sgiathán Leathair agus an Eas
An Príochán agus an Chaora
An Sean Duine agus an Bás
An Corcán agus an Crúsca
An tSaint agus an Formad
Fuar agus Teith
An Cat agus an t-Óigfhear
An t-Úcaire agus an Gualadóir
An Gadhar agus an Machtíre
An Capal agus an Fiadh 
An t-Iasgaire agus an Ceól 
Cogar an Bheithir 
An Mada Ruadh Maol
Ciall Cheanaig
An Príochán agus an Crúsca
An Sliabh i dTeinneas
An Dórnán Slat
An tSeilg

## Conversion code
In old Irish before An Caighdeán Oifigiúil had an overdot. that in modern usage adds a lentition h after the letter. 

Ḃḃ Ċċ Ḋḋ Ḟḟ Ġġ Ṁṁ Ṗṗ Ṡṡ Ṫṫ

test_str = """Ḃḃ Ċċ Ḋḋ Ḟḟ Ġġ Ṁṁ Ṗṗ Ṡṡ Ṫṫ Put actual string in here"""

test_str =test_str.replace("Ḃ","Bh")

test_str =test_str.replace("ḃ","bh")

test_str =test_str.replace("Ċ","Ch")

test_str =test_str.replace("ċ","ch")

test_str =test_str.replace("Ḋ","Dh")

test_str =test_str.replace("ḋ","dh")

test_str =test_str.replace("Ḟ","Fh")

test_str =test_str.replace("ḟ","fh")

test_str =test_str.replace("Ġ","Gh")

test_str =test_str.replace("ġ","gh")

test_str =test_str.replace("Ṁ","Mh")

test_str =test_str.replace("ṁ","mh")

test_str =test_str.replace("Ṗ","Ph")

test_str =test_str.replace("ṗ","ph")

test_str =test_str.replace("Ṡ","Sh")

test_str =test_str.replace("ṡ","sh")

test_str =test_str.replace("Ṫ","Th")

test_str =test_str.replace("ṫ","th")

print(test_str)
