# Given names and gender

## Sources 

- [Wiktionary's most common male given names in Germany](https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_m%C3%A4nnlichen_Vornamen_Deutschlands) ([archive](https://web.archive.org/web/20240112142146/https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_m%C3%A4nnlichen_Vornamen_Deutschlands))
- [Wiktionary's most common female given names in Germany](https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_weiblichen_Vornamen_Deutschlands) ([archive](https://web.archive.org/web/20240112142514/https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_weiblichen_Vornamen_Deutschlands))

## Modifications

- lists were concatenated
- gender column added depending on whether name is from list of female (`f`) or male (`m`) list

# Last names

## Sources 

- [Wiktionary's most common last names in Germany](https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_Nachnamen_Deutschlands) ([archive](https://web.archive.org/web/20240112142618/https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_Nachnamen_Deutschlands))

# Street names

## Sources

-  [Zeit Online interactive street name analysis](https://www.zeit.de/interactive/strassennamen/index.html) ([archive](https://web.archive.org/web/20240124141150/https://www.zeit.de/interactive/strassennamen/index.html))

## Modifications

- GeoJSON features "NAME" (street name), "GEMEINDE" (municipality) and "PLZ" (postcode) extracted and converted into table (empty features were skipped)
- dropped all street names with digits in them
- dropped all street names with less than 23 occurrences (<99% quantile)
- selected 5% of all street names at random