# 🕵🏼‍♂️ Die Akte Raphael S.

Im November 2023 hat mutmaßlich Raphael S. einen DMCA-Takedown Antrag
gegen das Repostitory von Trickest bei
[Github](https://github.com/trickest/zip/tree/main)
gestellt. Dieses Repository ist die Quelle für meine Zip-Domain-Adlist. Wegen diesem
Antrag ist das Repo nicht mehr öffentlich zugänglich.

## DMCA-Takedown Antrag

S. führt als Gründe für den Antrag an:

> This is crawling and storing an old version of it without my consent to copy the content, and listing it on a shame imposing repository that is directed at all owners of zip domains, alleging that the domain itself is a problem, when the behavior of pieces of software that deals with links are. [1]

Meiner Meinung nach sind hier zwei verschiedene Dinge in einen Topf geworfen worden und
unrechtmäßiger Weise ein DMCA-Takedown Antrag gestellt worden:

1. >This is crawling and storing an old version of it without my consent to copy the content [...]

Ok, hierzu kann ich nicht genau sagen wie es sich mit Webseiten-Crawlern und
Urheberrecht verhält (bin kein Anwalt), meiner Meinung nach sind die Inhalte frei im
Internet verfügbar und dadurch dürften Screenshots zum Nutze eines Zitats
([§51 UrhG](https://www.gesetze-im-internet.de/urhg/__51.html)) verwendet werden, was
meiner Meinung nach hier vorliegt, sofern wir von Deutschland ausgehen. Zudem gelten
für Forschungszwecke nochmals zusätzliche erlaubte Nutzungen. In den USA
gelten andere Urheberrechtsgesetze, dort nennt es sich *Fair use* nach dem ebenfalls
urheberrechtlich geschütztes Material unter bestimmten Bedingungen verwendet werden
darf.

2. >[...] and listing it on a *shame imposing* repository that is directed at all owners of zip domains, alleging that the domain itself is a problem, when the behavior of pieces of software that deals with links are.

Diese Passage stört mich. Einerseits hat S. Recht: Nicht die *.zip-Domain* ist
das Problem, sondern Webseiten, die die Domain für schädliche Zwecke (Phishing,
Malware, etc.) ausnutzen. Andererseits ist die Aussage "[...] *shame imposing*
repository [...]" falsch. Das Repository von Trickest erweckt nicht den Eindruck, dass
dort Webseiten bloßgestellt werden sollen.

## Das Trickest-Repository

>Welcome to our project dedicated to providing up-to-date data on newly registered .zip domains. With the recent introduction of the [.zip top-level domain (TLD)](https://domains.google/tld/zip/) by Google, [concerns have arisen](https://medium.com/@bobbyrsec/the-dangers-of-googles-zip-tld-5e1e675e59a5) within the community regarding potential attack vectors associated with this TLD. To address these concerns and ensure the safety of internet users, we have initiated this workflow aimed at gathering comprehensive information about .zip domains as they are registered. [2]

Dieser Text stammt aus dem Readme des Repositorys als Einleitung. Das Repo ist eine
Sammlung von Webseiten, diem unter der *.zip-Domain* online gegangen sind. Der Grund
für die Sammlung ist es, Daten über Webseiten zu sammeln, die unter dieser speziellen
TLD online gehen. Der verlinkte Artikel von [Medium](https://medium.com/@bobbyrsec/the-dangers-of-googles-zip-tld-5e1e675e59a5) ist durchaus lesenswert: Es wird
aufgezeigt, wie die TLD für schädliche Zwecke verwendet werden kann.

Weiter im Repository unter *Objective* heißt es:

>Our mission is to provide a reliable and regularly updated dataset that contains valuable insights into newly registered .zip domains. By systematically collecting and analyzing information, we *aim to shed light on potential risks* and help the community make informed decisions when interacting with these domains. Our project *focuses on promoting online security and mitigating any potential threats associated with the .zip TLD*. [2]

Die Verwendung des Wortes *potential* ist hier von großer Bedeutung. In keinem Satz
wird pauschal gesagt, dass jede *.zip-Domain* schädlich sei. Außerdem liegt der Fokus
auf der "Steigerung der Online-Sicherheit und der Verringerung potenzieller Bedrohungen im Zusammenhang mit der TLD .zip" [2].

Unter *Disclaimer* heißt es:

>While we strive to provide accurate and up-to-date information, it is important to note that our project serves as a supplementary resource and *should not be considered a definitive indicator of the security status of any .zip domain.* It is crucial for users to exercise their own judgment and employ additional security measures when *interacting with any domain*, *including those under the .zip TLD*. [2]

Trickest schreibt selbst, dass ihr Repo nicht als einen sicheren Indikator für die
(Un)schädlichkeit einer *.zip-Domain* gilt. Es handelt sich um eine wertfreie Sammlung
aller, bzw. aller entdeckten *.zip-Domains*.

## Meinung

Mit der Liste, die im Repo von Trickest veröffentlicht wurde, biete ich selbst eine
Adliste für Pihole an. Gleichzeitig habe ich eine [Liste](allowed-zip.txt) von
Webseiten, die ich persönlich als sicher erachte. Dazu zählt jetzt auch die von
Raphael S., da es sich nur um eine persönliche Webseite über Raphael S. handelt.

Es ist verständlich, dass man sich ärgert unter Generalverdacht zu stehen, aber
darauf mit einem DMCA-Takedown zu reagieren ist meiner Meinung nach kein gutes Mittel.
Vor allem nicht, wenn es sich um ein informatives Repo handelt, welches wertfrei über
*.zip-Domains* berichtet. Die Tatsache, dass die TLD der Webseite von S. auf *.zip*
endet ist unabhängig vom Seiteninhalt, welcher jetzt missbräuchlich als Mittel zur
Zensur verwendet wird.

Dazu kommt die Aussage "[...] *shame imposing* repository [...]" [1], welche den Eindruck
erweckt, dass sich Raphael S. nicht genau mit dem Repository von Trickest befasst hat.
Ein Repo, welches die TLD *.zip*, genau wie ich, als kritisch betrachtet wird von einer
Person angegriffen, welche sich selbst angegriffen fühlt. Dabei sind Betreiber von
*.zip-Domains* nicht per se kriminell oder sie verbreiten Schadsoftware, die
Domainendung ist nunmal problematisch. Außerdem könnte man überlegen, ob es nicht
vielleicht sogar positiv ist, wenn die eigene Webseite mit Screenshot in der Datenbank
erscheint, weil man auf den ersten Blick erkennen kann, dass es sich um eine private
Webseite handelt. Die einzige Frage ist, was mit "old version of [my personal website]"
[1] gemeint ist.

---

Quellen:

* [1] [DMCA Antrag vom 13.11.2023](https://github.com/github/dmca/blob/master/2023/11/2023-11-10-source-image.md)
* [2] Readme (Stand 16.06.2023) des Repositorys (am 27.12.2023 nicht öffentlich einsehbar)

---

[**Zurück**](/)