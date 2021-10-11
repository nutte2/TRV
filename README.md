# TRV
Ett samarbete mellan Trafikverket, Sweco och Umeå universitet.

I det här projektet har vi tittat på hur Artificiell intelligens kan användas för att hantera svensk text, så kallad Natural Language Processing (NLP). Man kan t ex ställa frågor på långa (över 200 A3-sidor) dokument och få svar, sortera fram olika typer av info och sammanfatta eller generera ny text.

Vill du prova lite själv har vi en server igång, vanligtvis vardagagseftermiddagar kl 12.00 - 18.00 från 20 oktober till 19 November 2021 (den används för utveckling andra tider).

Du kan nå den och testa lite via en web-applikation som finns här: https://trafikverket.anvil.app/ hoppas det är intressant! (den är inte komplett "perfekt" än, det kommer nya versioner/funktioner allteftersom)

Kontakt: kalle.prorok@gmail.com

Lite om projektet; vi använder Googles språkmodell BERT som anropas via Pythonkodbiblioteket PyTorch från Facebook/Microsoft och körs via beräkningsprogramvaran CUDA på Nvidias grafikkort (RTX A5000). Språkmodellerna har skapats av Kungliga biblioteket (KB) som använt stora delar av vad som skrivits 1940 - 2019 för att träna upp dem och de tillhandahålls via Huggingface.



