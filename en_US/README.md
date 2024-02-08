# Given names, gender and ethnicity

- File name: [given-name-gender-ethnicity.csv](given-name-gender-ethnicity.csv)

## Sources

- [NYC Open Data on popular baby names](https://catalog.data.gov/dataset/popular-baby-names/resource/02e8f55e-2157-4cb2-961a-2aabb75cbc8b) ([archive](https://web.archive.org/web/20240125074306/https://catalog.data.gov/dataset/popular-baby-names/resource/02e8f55e-2157-4cb2-961a-2aabb75cbc8b))

## Modifications

- values of gender column mapped into new column `gender_code` with `m` for male and `f` for female
- values of ethnicity column mapped into new column `ethnicity_code` with `h` for "Hispanic", `w` for "White, non-Hispanic", `a` for "Asian and Pacific islander" and `b` for "Black, non-Hispanic"
- renamed `Child's First Name` into `given_name`
- capitalized values of `given_name`
 
# Last names

- File name: [last-name.csv](last-name.csv)

## Sources

- [United States 2010 Census most common last names](https://www.census.gov/topics/population/genealogy/data/2010_surnames.html) ([archive](https://web.archive.org/web/20240125075316/https://www.census.gov/topics/population/genealogy/data/2010_surnames.html))

## Modifications

- renamed `name` into `last_name`
- capitalized values of `last_name`