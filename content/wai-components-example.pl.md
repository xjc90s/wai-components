---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: "Opisy ilustracji w artykule Podstawowe komponenty dostępności Internetu"
nav_title: Opisy ilustracji
lang: pl  # Change "en" to the translated language shortcode
last_updated: 2024-03-26  # Put the date of this translation YYYY-MM-DD (with month in the middle)

translators: # remove from the beginning of this line and the lines below: "# " (the hash sign and the space)
- name: "Stefan Wajda"   # Replace Jan Doe with translator name
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple translators
# contributors:
# - name: "Jan Doe"   # Replace Jan Doe with contributor name, or delete this line if none
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple contributors

github:
  repository: w3c/wai-components
  path: content/wai-components-example.pl.md # Add the language shortcode to the middle of the filename, for example: content/index.fr.md

permalink: /fundamentals/components/examples/pl # Add the language shortcode to the end, with no slash at the end. For example /path/to/file/fr
ref: /fundamentals/components/examples/ # Do not change this

parent: /fundamentals/components/ # Do not change this
---

{::nomarkdown}
{% include_cached toc.html type="start" title="Treść strony" class="simple" %}
{:/}

{::options toc_levels="2" /}

-   This text will be replaced by the TOC.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

Na tej stronie opisano ilustracje w dokumencie „[[Podstawowe komponenty dostępności Internetu]](/standards/components/)” oraz prezentacji [Podstawowe komponenty dostępności Internetu](http://www.w3.org/WAI/intro/components-slides).

## Opis ilustracji przedstawiającej powiązania między komponentami {#relate}

{% include image.html src="relate.pl.png" alt="Ilustracje powiązania między komponentami" %}

Ilustracja przedstawia trzy graficznie oznaczone pola obrazujące treść i ludzi. Pośrodku na górze znajduje się pole oznaczone jako „treść” na którym są baletnica, zdjęcie dziecka, znacznik img, tekst, formularz, widżet pogody i wykres kołowy. Idąc od dołu z lewej strony, linia łączy  „twórców” z „treścią” na górze, przechodząc przez „narzędzia autorskie” i „narzędzia oceniające”. Idąc od dołu z prawej stronie, linia łączy „użytkowników” z „treścią” na górze, przechodząc przez „przeglądarki, odtwarzacze mediów” i „technologie wspomagające”.

## Opis ilustracji Gdy jeden komponent jest słaby  {#weak}

{% include image.html src="bridge.pl.png" alt="Pokazuje, co się dzieje, gdy jeden komponent jest słaby" %}

Ilustracja przedstawia trzy graficznie oznaczone pola obrazujące treść i ludzi. Pośrodku na górze znajduje się pole oznaczone jako „treść” na którym są baletnica, zdjęcie dziecka, znacznik img, tekst, formularz, widżet pogody i wykres kołowy. Idąc od dołu z lewej strony, linia łączy  „twórców” z „treścią” na górze, przechodząc przez „narzędzia autorskie”. Idąc od dołu z prawej stronie, linia łączy „użytkowników” z „treścią” na górze, przechodząc przez wiele „przeglądarek, odtwarzaczy mediów” i „technologii wspomagających”.

## Opis ilustracji Wytyczne dla różnych komponentów {#guide}

{% include image.html src="specs.pl.png" alt="Ilustracja przedstawia różne wytyczne dla różnych komponentów" %}

Ilustracja przedstawia trzy graficznie oznaczone pola obrazujące treść i ludzi. Pośrodku na górze znajduje się pole oznaczone jako „treść” na którym są baletnica, zdjęcie dziecka, znacznik img, tekst, formularz, widżet pogody i wykres kołowy. Idąc od dołu z lewej strony, linia łączy „twórców” z „treścią” na górze, przechodząc przez „narzędzia autorskie” i „narzędzia oceniające”. Idąc od dołu z prawej stronie, linia łączy „użytkowników” z „treścią” na górze, przechodząc przez „przeglądarki, odtwarzacze mediów” i „technologie wspomagające”.

Poniżej znajdują się „Wytyczne dla dostępności", które obejmują „ATAG” ze strzałką wskazującą na „narzędzia autorskie” i „narzędzia oceniające”, „WCAG” wskazujące na „treść” oraz „UAAG” wskazujące na „przeglądarki, odtwarzacze mediów” i „technologie wspomagające”. Na samym dole „Specyfikacje techniczne (HTML, ARIA, CSS, SVG, SMIL itp.)" tworzą podstawę ze strzałką wskazującą na wytyczne dla dostępności.

{% comment %}

@@ commenting out - image was used in presentation that is not on new site - leaving here in case we want to resurrect it in the future. @@

## Interdependencies Between Components, Example Illustration Description {#example-alt}

{% include image.html src="relate-example.jpg" alt="Illustration showing examples of how components relate" %}

Illustration with labeled graphics of boxes, content, and people. at the top center "content" and underneath it is a logo and a box with: `<img src="WAI-logo.png" alt="Web Accessibility Initiative logo">`. coming up from the bottom left, a line connects “developers” through “authoring tools” and “evaluation tools” to “content” at the top. between the “developer” and “authoring tools” is a dialog box titled: Image Tag Accessibility Attributes, a field titled: Alternative Text filled in with: Web Accessibility Initiative logo. coming up from the bottom right, a line connects “users” to “browsers, media players” and “assistive technologies” to “content” at the top. just up from the “user” is a speech bubble saying: Web Accessibility Initiative logo and a yellow box with: Web Accessibility Initiative logo. at the bottom is: `1.1 Provide a text equivalent for every non-text element` 

{% endcomment %}
