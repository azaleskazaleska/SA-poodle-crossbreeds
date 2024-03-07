# Analiza wzrostu zainteresowania mieszańcami pudla na przestrzeni lat 2004-2023 na podstawie danych z Twitter
Aleksandra Załęska, 06.2023r.


## Dlaczego wzrost zainteresowania jest problemem?
Według FCI (Fédération Cynologique Internationale), czyli Międzynarodowego Związku Kynologicznego rasy te nie są uznawane, co skutkuje brakiem możliwości zare jestrowania dane j hodowli.
Zarejestrowanie hodowli i przestrzeganie wymogów hodowlanych pomaga w utrzymaniu wysokiego standardu rasy i poprawia genetyczną różnorodność psów. Ponadto, zare jestrowane hodowle są zazwycza j regularnie sprawdzane pod kątem zdrowia psów i przestrzegania reguł, co pozwala na szybszą reakcję w przypadku jakichkolwiek problemów.
Wzrost popularności ras psów nieuznanych przez FCI oraz brak możliwości re jestracji hodowli przyczynia się w konsekwencji do wzrostu liczby pseudohodowli i pozbawionych skrupułów hodowców, dla których zysk jest ważnie jszy niż dobro psów. Hodowcy często stosu ją złe praktyki hodowlane i nie przeprowadza ją odpowiednie j soc jalizac ji i opieki nad szczeniętami, co prowadzi do problemów zdrowotnych i behawioralnych w późnie jszym życiu .

## Nasilony trend
Odwrócenie trendu obecnie stanowi wyzwanie ze względu na wysokie zainteresowanie tymi rasami szczególnie wśród in fluencerów i celebrytów.

## Obszar analizy
Analiza będzie obejmowała najpopularniejsze obecnie typy mieszańców t j. Cavapoo, Goldendoodle, Maltipoo, Cockapoo, Labradoodle, Bernedoodle, Cavoodle oraz Shih-Poo.
Analiza ta jest tworzona w oparciu o dane z serwisu społecznościowego Twitter i używanych w postach hashtagów.

## Pozyskanie postów
Do pozyskania zbioru danych niezbędnych do naszej analizy wykorzystano bibliotekę snscrape. Poniżej kod umożliwiający scrapowanie treści tweetów zaawierających konkretny hashtag wraz z dokładną datą i godziną zamieszczenia posta.
