---
layout: post
title:  "Förkompilerad CSS"
date:   2017-11-18 15:08:01 +0000
categories: precompilation css
---

Att förkompilera css har definitivt sina fördelar, även om det kan ta sin
lilla tid att förstå sig på hur det fungerar, eller ja, hur programvaran
fungerar.

Till skillnad från vanlig css, är förkompilerad css en liten aning mera som
ett programspråk. Exempelvis stödjes nästling av koden, och på så vis
slipper man börja på ett nytt block css-kod varje gång man, från att ha
stilsatt ett förälderelement, vill stilsätta en ättling till detta.

Variabler är en annan finess. I stället för att exempelvis skriva ut
rgb-värdet varje gång man vill definiera en färg, kan man definiera en
variabel med ett bra namn, och använda detta variabelnamn när man vill
använda den färgen.

I mina partials, d.v.s. moduler, har jag definierat ett antal
färgvariabler, vilka jag har använt när jag satt färg på elementen. När
jag har använt pseudoklasser, har jag nästlat dessa, vilket gör koden
mindre stökig. Funktioner är också en finess med förkompilerad css,
men för det har jag inte fått någon användning.

En nackdel med förkompilerad css, är att alla måste vara med på på noterna.
Eftersom det faktiskt skapas en vanlig css-fil vid kompileringen, kan
det hända att någon försöker ändra stilen i denna, vilket vid nästa
kompilering innebär bortkastat arbete. På grund av filändelsen i Sass,
som är väldigt lik den vanliga css-ändelsen, kan detta mycket väl hända
även för den invigde.






