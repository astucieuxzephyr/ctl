# French version of the Max Lüscher Test of colors :
 - Author : Tanguy Bodin-Hullin.

 The psychophysiological states studied by 8 color variant of the Lüscher color test modified by L. Sobchik (method of paired comparisons)
 Sobchik, L.N., 1990, Methods of psychological diagnostic (Л. Н. Собчик)


## Changelog
 - Get original CTL program (done by Daria Titova, in russian language) on Github : in avril 23, 2013
 - New version of the program, in french, by Tanguy Bodin-Hullin, in march 2020.
 - Last update : april 2020.

## History of this program :
 - The first recovery of the Russian program was made in April 2013 on Github. A first translation has been made, and the JS program has been improved, but I lost the file by mistake some time later.
 - At the end of March 2020, a new and improved version is put online.
 This version benefits from many improvements:
   - Big Update of the JS code, based on JQuery (from version 1.7.1 to version 3.4.1)
   - Brand new interface, based on Bootstrap 4.1.
   - Added ability to easily use names by default with a selector, to facilitate the usage.
   - New results interface, that allows to easily get assessment data with a simple copy-paste.
   - Texts translated into french
   - Better documented code, added some debugging messages in the console that can be turned ON/OFF
   - Improved documentation in Markdown format, in french and english.

## Still To-do :
  - Add the ability to get the results in other languages, especially in english.
  - Add a random color positioning system
  
## Description :
It is the color test created by the swiss psychologist Max Lüscher (1923-2017), in an ultra-simplified version.
The color test is used to assess a person's emotional state at a given time, based on their color preference at the time.
This test is little known but is of high clinical interest, it is relevant and very scientific.
It is a test that relies on the relationship between the perception of wavelengths of colors, and emotions.

# Usage :
The test was used many times, worldwide, and some medical researches have been conducted with it.
Some psychologists still use the test, especially russian psychologists in the psychological support of athlets or highly skilled athlets.
For example, the test can be used to measure the stress level of people.
A french doctor is using it.

It is not for nothing that some expressions exist in the French language like: "See the world in gray" ; or: "Voir la vie en rose"...

## Taking the test :
Eight colors are presented at the same time to the person taking the test.
The colors are: blue, green, red, yellow, purple, brown, black and gray.
The subject chooses the colors one by one, according to his order of preference of the moment (and this is very important, see below the precautions for handing over).

The subject must not associate the color with an object that he likes, for example, otherwise it distorts the test. Or, if his favorite color is blue, he shouldn't take it into account.
The instructions for the book state:
> "ESPECIALLY do not try to associate this color with something else, with a dress fabric, with an interior, with a car or any other object. Simply choose the color which attracts you the more among the eight colors you have in front of you. "


The classification will allow a projection of certain components of the psychosomatic personality of the subject, at the time when he took the test.

## History of my personal interest in this program
> I discovered the color test in the early 2000s, after having come across an Internet application by chance.
I used the application several times on my own and I was very surprised by the extraordinary relevance of the results. I also passed it on to other people, and it convinced me of the strength of the test and its validity.
Having psychological difficulties at the time, I was very interested in taking the test every day for a given period. The only problem is that the program I had recovered (TESTCOUL.EXE) did not allow to record the history of the transfers, and thus to create an analyzable database. Being trained in programming from my first studies, I therefore decided to create a program using Microsoft Access software that allowed it. I advanced well in this program, and I had a functional graphical interface which made it possible to make the choice of colors.
But I did not have the exact sentences which are given in analysis results, a very precise sentence established by Max Lüscher, and I therefore tried to find a work on the subject.
I found in the Nanterre library a copy of the book which would allow me to know more, and I photocopied some of the parts which seemed to me the most essential, but I had other things to do and I put the program on standby.
Some time later, in March 2008, when I was a psychology student at the University of Paris Descartes, I noticed in the catalog that there was another work on the test of colors, more recent than the one that I had photocopied in Nanterre. But the book was in the library of the University of Toulouse. Fortunately, there is a loan service between libraries (PEB) which allowed me to order the work and consult it in Paris. Again, I photocopied the book, because I couldn't keep it for as long as I wanted.
>
> -- <cite>Tanguy Bodin-Hullin, clinical psychologist, mars 2020</cite>

## Warning :
Only a psychologist can provide a reliable analysis of your mental and emotional health. Every psychological test requires human validation, and its result can be legitimized by people close to you, who have coexistence and knowledge of your personality.

## Other interesting programs.
  - Several programs have been developed for the mobile phone (under Android)

## Files :

  - `luscher_test_russian.html` : the original version of the program
  - `lusher.html` : the new version, in french, using bootstrap and jQuery
  - `assets/css/styles.css` : the stylesheet
  - `LISEZMOI.md` : complete documentation in french language (Markdown format)
  - `README.md` : documentation in english (Markdown format)

## About Max Lüscher :
Max Lüscher is a Swiss psychologist and philosopher, professor of psychology.
He is considered the father of color psychology.
- Read more about [Max Lüscher on Wikipédia](https://en.wikipedia.org/wiki/Max_L%C3%BCscher)

### A correspondance between colors and incouscious state of a person
Max Lüscher has explored the hypothesis of a correspondence between colors and inconscious state of a personality.
He was applying that the attraction for colors being based on unconscious processes, the test
would show how the person is and feels in reality as opposed to how they could
be, could imagine she is or even how she would like to be.

### Marketing :
His research has confirmed that using the right color on packaging can have a hypnotic effect on the buyer. Likewise the coloring of objects can influence their commercial success (for example the Volkswagen Beetle should give him a share of his success).

## The Lüscher test
The test consists of ordering colored boxes from the most loved to the least loved colors,
in other words, in order of preference *of the moment*. This means that the test can give different results depending on the moment it was taken. For example, if a person takes the test on a certain day and time, and gets a certain result, she could get a different result if she takes the test some hours later, on the same day, and all the more as time passes.

# Different forms of the test
The Lüscher test exists in several forms:
- the complete test (full test) using a large color chart, available only in German,
- a simplified test (short test) using six (6) colors cardboard cubes.
- a programmatic, software version, presenting height (8) colors on "cards", and giving a deep analysis of the psychological state of the subject.
- the program of Russian origin which is offered on this GitHub repository is similar to the software version, since it presents the 8 colored cards, but it delivers clearly more succinct and simplified information, and offers another analysis. (See the details in the paragraph "Results delivered by the program").

# When is the colours test usefull ?
The colours test is commonly used to assess the psycho-physiological state of the person, their ability to manage stress, his activity and his communication skills.

### A powerful and fast-to-perform tool
Among the deep tests in Psychology, the Lüscher Color Test is the fastest to perform and, despite its simplicity of application, it is a powerful tool for revealing physical and psychological stress sources, anxieties, repressed personality traits and so much more.

### Interpretation of the test :
It is complex and documented on the [official website : Lüscher Color Diagnostik]

## Simple_interpretation :
According to the [Auriol website presenting their usage of the test](http://cabinet.auriol.free.fr/psychologie/luscher.htm), a simple interpretation of this test consists in looking if a color is classified among the favorites (the first four) or the least liked (the last four).
> This test is little known but is of some clinical interest. It (Zirilli G., 1967), is widely used by certain specialists in personnel recruitment.

### Nota :
Test results may vary depending on age.
(a color quotient was created by firm Auriol which makes it possible to evaluate a kind of emotional age via the Lüscher test).
People who have energy, creativity, success would have this test at a very young age compared to their real age..

## References :

### in French :
- Lüscher M., (1981). Le Color test de Max Lüscher. Votre personnalité révélée par les couleurs, Avignon, Aubanel, coll. Encycl. de sciences humaines et de psychologie pratique.
- Lüscher M., (1992). Le nouveau test des couleurs. une méthode scientifique et facile, Paris, Solar.
- [Canivet N. Le test de Lüscher](https://www.persee.fr/doc/clini_0373-6261_1964_num_17_1_1217). In: Bulletin de la Société française du Rorschach et des méthodes projectives, n°17-18, 1964. (pp. 57-61).
- [Dounovetz A., Durand de Bousingen R. Utilisation en psychologie clinique du test de choix de couleurs (Luscher)](https://www.persee.fr/doc/clini_0373-6261_1969_num_23_1_1293). In: Bulletin de la Société française du Rorschach et des méthodes projectives, n°23, 1969. Psycholinguistique et techniques projectives. (pp. 95-98).
### in German :
- Lüscher M., (1992). Die Lüscher-Würfel : zur Selbsterfahrung und Personlichkeitsbeurteilung.
### in English / Italian
- Zirilli G., Applications of the colored "(Koch) tree (drawing) test" in psychiatry.
- Sobchik, L.N., 1990, Methods of psychological diagnostic (Л. Н. Собчик)
### in Italian :
- Zirilli G., Applications of the colored "tree test" in psychiatry.
Translation in italian : Applicazioni del Koch "test ad albero" colorato in psichiatria
Acta Neurol. (Napoli). 1967 Sep-Oct;22(5):619-43. Italian.
No abstract available.

### Web links :
 - [Max Lüscher on Wikipédia (in french)](https://fr.wikipedia.org/wiki/Max_L%C3%BCscher)
 - [Lüscher Color Diagnostik (official website)](https://www.luscher-color.ch/) : multilingual website on the Lüscher's system. A video of Max Lüscher is available, with many explanations.
 - [Auriol website présenting their usage of the test](http://cabinet.auriol.free.fr/psychologie/luscher.htm)
On this website, you can [download the old program of the Lüscher test (for Windows version < 10)](http://cabinet.auriol.free.fr/psychologie/COLORTST.EXE)
