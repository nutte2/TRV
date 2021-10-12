# TRV
Ett samarbete mellan Trafikverket, Sweco och Umeå universitet.

I det här projektet har vi tittat på hur Artificiell intelligens kan användas för att hantera svensk text, så kallad Natural Language Processing (NLP). Man kan t ex ställa frågor på långa (över 200 A3-sidor) dokument och få svar, sortera fram olika typer av info och sammanfatta eller generera ny text.

Vill du prova lite själv har vi en server igång, vanligtvis vardagagseftermiddagar kl 12.00 - 18.00 från 20 oktober till 19 November 2021 (den används för utveckling andra tider).

Du kan nå den och testa lite via en web-applikation som finns här: https://trafikverket.anvil.app/ hoppas det är intressant! (den är inte komplett "perfekt" än, det kommer nya versioner/funktioner allteftersom)

Kontakt: kalle.prorok@gmail.com

Lite om projektet; vi använder Googles språkmodell BERT som anropas via Pythonkodbiblioteket PyTorch från Facebook/Microsoft för att utföra uppgifterna och körs via beräkningsprogramvaran CUDA på Nvidias GPU grafikkort (RTX A5000), tack vare det kortet går sökningarna ca 100 gånger fortare så väntetiden/dokument går ner från ca 1200 s till rimliga 12 s. Språkmodellerna har skapats av Kungliga biblioteket (KB) som använt stora delar av vad som skrivits 1940 - 2019 för att träna upp dem och de tillhandahålls via Huggingface.

Orginaldokumenten finns på https://www.trafikverket.se/nara-dig/projekt-i-flera-lan/Norrbotniabanan/
-
-
resp https://www.trafikverket.se/nara-dig/projekt-i-flera-lan/Ostlanken/
- https://www.trafikverket.se/contentassets/465639bc7e8741a7b383517d1490c88f/g_l_mkb_20191001_lu.pdf
- https://www.trafikverket.se/contentassets/18aa3b0f11d64ae785432167714a24bc/nykopings-resecentrum/faststallelse/nykrc_jarnvagsplanbeskrivning_20200331.pdf
och man kan läsa om KB-Bert på https://github.com/Kungbib/swedish-bert-models

