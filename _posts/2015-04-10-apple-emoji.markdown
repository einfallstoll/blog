---
layout: post
title:  "Neue Emojis in iOS 8.3"
date:   2015-04-10
---

<p class="intro"><span class="dropcap">I</span>m Netz ist es ein grosses Thema: die neuen Emojis in iOS 8 aber was steckt dahinter?</p>

Endlich sind sie da: die neuen Emojis von Apple. Seit langer Zeit wird darüber diskutiert, dass in die Emojis mehr Farbe rein soll und nun wurden sie endlich veröffentlicht.

In den vergangenen Tagen und Wochen las ich wiederholt, dass die neuen Emojis hässlich sind und die Farben den Leuten nicht gefallen, doch Apple kann da eigentlich nur bedingt etwas dafür.

## Wer ist dafür verantwortlich?

Verantwortlich für die Emojis sind zwei Herren: Mark Davis von Google und Peter Edberg von Apple. Sie haben den Entwurf für die Unicode Emojis ausgearbeitet und auch für die verschiedenen Hautfarben.

Der Entwurf soll Mitte 2015 abgeschlossen und als offizieller Standard eingesetzt werden.

## Was für ein Standard?

Veröffentlicht wird dies im sogenannten [Unicode](http://de.wikipedia.org/wiki/Unicode)-Standard. Dies ist ein internationaler Standard in dem langfristig verschiedene Symbole und Textzeichen festgelegt werden.

Der Unicode-Standard gibt vor, wie die Buchstaben, Symbole und Emojis auszusehen haben.

Unicode Emojis findet man hier: <http://www.unicode.org/reports/tr51/>

## Wieso diese Hautfarben?

Die Hautfarben wurden nach [Fitzpatrick Skin Types](http://www.arpansa.gov.au/pubs/RadiationProtection/FitzpatrickSkinType.pdf) festgelegt.

Im Unicode-Standard werden nur 5 Hautfarben erwähnt, da Skin Type I und Skin Type II zusammengelegt wurden.

## Wie funktionieren Emojis?

Hinter jedem Textzeichen verbirgt sich ein Code aus dem Standard, sowohl für alle Buchstaben, die ich hier verwende, als auch für alle Emojis. Die Emojis bestehen aus einem einzelnen Code und die Farbe wird als zusätzlicher Code angefügt.

Man kann sich das ungefährt so vorstellen: "EmojiXY + Farbe1", "EmojiABC + Farbe2", usw. sollte ein System diese Farbunterscheidung nicht machen können, wird das Emoji einfach normal dargestellt und die Farbe ignoriert. So wird die sogenannte Rückwärtskompatibilität sichergestellt. Ein normales Emoji ist also ein einzelner Code, ein Emoji mit Hautfarbe sind zwei Codes. 

Der Standard gibt also die Emojis vor und welche mit einer Farbe versehen werden können. Ausserdem gibt der Standard vor, welche Farbe das Emoji haben soll, wenn dieser Farbcode nicht angegeben ist, und zwar Gelb.

* 👍 (1 Code für das Emoji)
* 👍🏻 (1 Code für das Emoji, 1 Code für Skin Type I-II)
* 👍🏼 (1 Code für das Emoji, 1 Code für Skin Type III)
* 👍🏽 (1 Code für das Emoji, 1 Code für Skin Type IV)
* 👍🏾 (1 Code für das Emoji, 1 Code für Skin Type V)
* 👍🏿 (1 Code für das Emoji, 1 Code für Skin Type VI)

## Welche Emojis werden unterstützt?

Der Standard gibt 26 Emojis vor, die mehrfarbig unterstützt werden müssen, sowie 97 zusätzliche, die optional auch unterstützt werden können.

### Minimal Set (26 code points)

👦 👧  👨 👩  👴  👵  👶 👱 👮 👲 👳 👷 👸 💂🙇 🎅 👼💆 💇 👰 🙍 🙎 🙅 🙆 💁 🙋

### Optional Set (97 code points)

☺ ☹ 🙁 🙂 😀 😁 😂 😃 😄  😅  😆  😉  😊 😋 😌 😍 😎 😏 😐 😑 😒 😓 😔 😕 😖 😗 😘 😙 😚 😛 😜  😝  😞 😟 😠 😡 😢 😣 😤 😥 😦 😧 😨 😩 😪 😫 😬 😭 😮 😯 😰 😱 😲 😳 😴 😵 😶 😷 😇 😈 👿 🙌  🙏 🚶 🏃 💃 👈 👉 ☝ 👆 🖕  👇 ✌ 🖖  ✊  ✋  👊 👋 👌 👍 👎 👏 👐 ✍ 🖐 💅  💪 👂 👃 🚴 🚵 🚣 🛀 🏂 🏄 🏇 🏊

## Mr. Spock Emoji

Interessanterweise findet man das Mr. Spock Emoji nicht in der Emoji-Liste von Apple, jedoch wird es unterstützt: 🖖 🖖🏻 🖖🏼 🖖🏽 🖖🏾 🖖🏿 (*Der offizielle Name ist übrigens "RAISED HAND WITH PART BETWEEN MIDDLE AND RING FINGERS"*) 