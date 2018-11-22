# Template für schriftliche Arbeiten

## Installation

1.  Install latex
2.  Install packages
3.  Compile


## Editing

1.  Set Title, Name and other required properties in title.tex
2.  Add and replace the example pages with your apges in index.tex in the document folder
3.  Add references in the literature.tex

```latex
\newcommand{\worktitle}{Vorlage}
\newcommand{\short}{Latex-DHGE-Vorlage}
\assignTitle{Entwurf einer Latex-Vorlage für Projektarbeiten}

\newcommand\MyDate{23. März 2018}
\newcommand{\Index}{IV}
\newcommand{\secTitle}{Vorlage V}

%Autor Name und Matrikelnummer
\newcommand{\writer}{Max Mustermann}
\newcommand{\matrikel}{G111111PI}
\newcommand{\kurs}{PI}
\newcommand{\kursBeschreibung}{Praktische Informatik}
\newcommand{\school}{Duale-Hochschule-Gera-Eisenach}
\newcommand{\Campus}{Gera}
\newcommand{\Section}{Technik}

%Anschrift
\newcommand{\myStreet}{Am Waldrand 13}
\newcommand{\myCity}{00000 Nirgendwo}

%Company
\newcommand{\myCompany}{Praxispartner}
\newcommand{\myCompanyStreet}{Unter dem Radar 7}
\newcommand{\myCompanyCity}{00000 auch Nirgendwo}

\newcommand{\mySupervisor}{Findet Dori}
\newcommand{\mySupervisorGrade}{Dipl. Doktorfisch}

%Farbpalette
\primaryColor{21}{33}{71}
\secondaryColor{2}{143}{209}
```
