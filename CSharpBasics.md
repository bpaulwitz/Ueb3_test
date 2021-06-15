# C#

---

## 1. Einfuehrung

<p>C# ist eine typsichere, objektorientierte Allzweck-Programmiersprache. Historisch wurde in C# fast exklusiv für Windows entwickelt. Durch Xamarin ist es inzwischen aber auch möglich, für macOS, iOS und Android zu entwickeln. Zudem gibt es mit .NET Core auch offizielle Unterstützung für GNU/Linux und macOS [1].<p>

<p>In der normalen Betriebsart werden C#-Quelltexte in eine mist als IL bezeichnete Zwischensprache übersetzt, die (normalerweise durch einen JIT-Compiler) auf allen Plattformen ausgeführt werden kann, auf denen eine geeignete Laufzeitumgebung KAUDERWELSCH zur Verfügung steht. Darüber hinaus gibt es verschiedene Ansätze der AOT-Compilierung um plattformspezifischen Maschinencode vorab zu erzeugen.<p>

<p>Bis Version 2 war die Sprache bei ISO [2] als Standard regstriert. In der Folge erschienen regelmäßig umfangreiche Erweiterungen der Sprache durch Microsoft. Durch die Entwicklung des Referenc-Compilers als Open Source (seit 2014) sind auch Community-Beiträge möglich.<p>

## 2. Konzepts

<p>C# greift Konzepte der Programmiersprachen Java, C++, Haskell, C sowie von Delphi auf. C# zählt zu den objektorientierten Programmiersprachen und unterstützt sowohl die Entwicklung von sprachunabhängigen .NET-Komponenten als auch COM-Komponenten für den Gebrauch mit Win32-Anwendungsprogrammen.<p>

<p>Einige der Elemente von C++, die im Allgemeinen als unsicher gelten, wie beispielsweise Zeiger, werden in C# nur für sogenannten „unsicheren Code“ erlaubt, der in Zonen mit eingeschränkten Rechten (z. B. bei Programmen, die aus Webseiten heraus ausgeführt werden) ohne die Zuteilung erweiterter Rechte nicht ausgeführt wird.<p>

## 3. Entwicklungsschritte

| Jahr  | .Net version | c# version |
| ----- | ------------ | ---------- |
| 2002  | .NET 1.0     | C# 1.0     |
| 2003  | .NET 1.1     | C# 1.2     |
| 2005  | .NET 2.0     | C# 2.0     |
| 2006  | .NET 2.0     | C# 3.0     |
| 2010  | .NET 4.0     | C# 4.0     |
| 2020? |

<br>
<br>

| ![c# Logo](https://seeklogo.com/images/C/c-sharp-c-logo-02F17714BA-seeklogo.com.png) |
| :----------------------------------------------------------------------------------: |
|                        <p align = "center">Abb1. C#-Logo <p>                         |

<br>


## 4. Hello-world codebeispiel

```c#
using System;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");
    }
  }
}
```

_Referenzen_

[1] Bis hier her siehe:

- Joseph Albahari; Ben Albahari: C# 6.0 in a Nutshell. The Definitive Reference. 6. Auflage. <br> O'Reilly, Sebastopol 2016, ISBN 978-1-4919-2706-9, S. 1–6.
- Joseph Albahari; Ben Albahari: C# 6.0 Pocket Reference Instant Help for C# 6.0 Programmers.<br> O'Reilly, Sebastopol 2015,
  ISBN 978-1-4919-2741-0, S. 1.

[2] [International Organization for Standardizatio](<http://standards.iso.org/ittf/PubliclyAvailableStandards/c042926_ISO_IEC_23270_2006(E).zip>)
