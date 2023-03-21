---
external: false
title: Sózle (wordle)
description: Sózle
date: 2022-11-03
---

![Screenshot](https://abatme.s3.amazonaws.com/2022-11-03/screen-shot-2022-11-03-at-2-dc22.png)
**Wordle** júdá ataqlı sóz oyını. Bul oyında 5 háripli sóz jasırılǵan boladı. Bul sózde tabıw ushın siz birneshe imkaniyat boladı yaǵnıy siz bes háripli sózde táwekel kiritip kóresiz keyin klaviaturada háriplerdiń reńleri jasıl, sarı hám kúlreń bolıp bólinedi. Eger jasıl bolsa siz sol orında sol hárip turatuǵınlıǵın bildiredi, al sarı bolsa bul hárip sózde qollanılǵan biraq ornı almasıp turǵanın bildiredi, kúlreń bul hárip izlenip atırǵan sózde qollanılmaǵanın bildiredi.

Júdá qızıq oyın. Men usı oyındı qaraqalpaqsha variantın islemekshi bolıp júrgen edim biraq sózler bazısın taba almaǵanımnan soń qalıp ketken edi. Keshe oyıma bir pikir kelip qaldı nege endi usı oyındı oynaw dawımında sózlerdiń bazasın jıynap almaymız. Júdá qızıq kórindi nege sınap kórmeymiz dep usını islewge óttim.

Biraq bunıń bir qatar minus tárepleri bar:
- Eń dáslebinde sózler júdá az boladı hám oynaw zerigerli boladı
- Adamlar kiritken háripler kombinaciyası (sóz) haqıyqıy sózbe bunı bile almaymız
- Úlken baza jıynaw ushın kóp adam oynawı kerek edi

Bular ishinde eń tiykarǵısı bul sózlerdi validaciya etiw. Bul ushın maǵlıwmatlar bazına sózden basqa baha (score) qosıw kerek boldı. Baha (score) 0 menen 1 arasındaǵı san bolıp qansha birge jaqın bolsa sol sóz haqıyqıy ekenligin bildiriwi kerek.

Maǵlıwmatlar bazasın júdá ápiwayı túrde tómendegi tártipte isledim:
- **id** - avtomat sózge beriletuǵın sóz id’i (autoincrement primary key)
- **word** - sóz ushın kandidat 5 hárip kombinaciyası tákirarlanbas (unique)
- **score** - 0 menen 1 arasındaǵı baha (haqıyqıylıǵın belgilew ushın)

Demek qalay bahalanıp atır? Házirde táwekel etilgen sózler 0 (sebebi bul táwekel háripler kombinaciyası bolıw itimalı joqarı), al “ózim sóz qosıp oynamaqshıman” bóliminde jazılǵan sózge 0.3 (sebebi user sóz kiritiwi kútiledi) ball berilip atır.

Keyinshellik qayta bahalawdı ámelge asırıw ushın jáne usıǵan qusas sóz oyının islep shıqsaq boladı biraq ol jerde sóz kiritpesten kóplew sózlerdi teksertiw kerek. Yamasa captcha jaratıw múmkin (qalay islew múmkinligin ele bilmeymen). Biraq bular keyingi másele.

**Háziraq oynap kóriń**: [sozle.qaraqalpaq.org](https://sozle.qaraqalpaq.org)

**Maǵlıwmatlar bazasın júklep alıw**: [Júklew](https://sozle.qaraqalpaq.org/api/db)

**Source code**: [GitHub](https://github.com/dauletbaev/wordle)
