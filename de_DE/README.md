# Given names and gender

- **Sources:** [male given names](https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_weiblichen_Vornamen_Deutschlands) ([archive](https://web.archive.org/web/20240112142146/https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_m%C3%A4nnlichen_Vornamen_Deutschlands)), [female given names](https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_weiblichen_Vornamen_Deutschlands) ([archive](https://web.archive.org/web/20240112142514/https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_weiblichen_Vornamen_Deutschlands))

The lists were concatencated. A "gender" column was added to indicate whether a given name is classified as male or female.

# Last names

- **Sources:** [last names](https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_Nachnamen_Deutschlands) ([archive](https://web.archive.org/web/20240112142618/https://de.wiktionary.org/wiki/Verzeichnis:Deutsch/Namen/die_h%C3%A4ufigsten_Nachnamen_Deutschlands))

# Street names

- **Sources:** [street names, municipalities, postcodes](https://www.zeit.de/interactive/strassennamen/index.html) ([archive](https://web.archive.org/web/20240124141150/https://www.zeit.de/interactive/strassennamen/index.html))

The GeoJSON file was converted to a CSV file by creating a row for every feature.
Each feature had its street name, municipality and postcode extracted.
Features where any of these fields were empty were skipped.

The resulting CSV file was filtered by removing street names that have digits in them.
Only rows with street names that appear more than 22 times (99% quantile) were kept.
Finally, 5% of all rows were randomly selected for export to trim the size of the final CSV file.