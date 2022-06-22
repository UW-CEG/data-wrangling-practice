# data-wrangling-practice

This github template repo contains labs to help you practice R Markdown notation, data wrangling, data reshaping, and data cleaning. The labs and data herein are borrowed from the [SISBID Data Wrangling Workshop](https://github.com/SISBID/Data-Wrangling).

Below is the list of the labs, the content covered, and the relevant [Statistical Inference via Data Science (“ModernDive”)](https://moderndive.com/index.html) chapter (where applicable):

| **Lab(s)**                                                          | **Description**                                                                                                                            | **Relevant SIDS (ModernDive) Chapter**                                                                                                                                                                                                                                                         |
|------------------|---------------------------|----------------------------|
| 0-rmarkdown-lab.Rmd                                                 | Quick intro to markdown text formatting, and its use in RStudio                                                                            | NA...refer to [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/) if you need help, but the lab is fairly self-contained.                                                                                                                                                |
| 1-data-subsetting-lab-part1.Rmd, 1-data-subsetting-lab-part2.Rmd    | Explore subsetting dataframes into smaller chunks using: \`filter()\`, \`arrange()\`, \`mutate()\`, pipe operator (\`%\>%\`), \`rename()\` | 3                                                                                                                                                                                                                                                                                              |
| 2-data-summarization-lab.Rmd                                        | Explore summarizing the contents of a dataframe using: \`read_csv()\`, \`mutate()\`, \`summarize()\`, \`group_by()\`, \`arrange()\`        | 3, 4 (but only because of \`read_csv\`)                                                                                                                                                                                                                                                        |
| 3-merging-lab.Rmd                                                   | Explore combining dataframes in various ways using: \`read_csv()\`, \`join()\`                                                             | 3, 4 (but only because of \`read_csv\`)                                                                                                                                                                                                                                                        |
| 4-data-io-lab-part1.Rmd, 4-data-io-lab-part2.Rmd                    | Explore getting data in and out or R using: \`read_csv()\`, \`read_delim()\`, \`read_excel()\`                                             | 4                                                                                                                                                                                                                                                                                              |
| 5-data-reshaping-lab(20201112).Rmd(ignore 5-data-reshaping-lab.Rmd) | Explore methods of formatting dataframes for statistical analyses using: \`pivot_wider()\`, \`pivot_longer()\`                             | 4                                                                                                                                                                                                                                                                                              |
| 6-data-cleaning-lab.Rmd                                             | Explore methods of standardizing a data set and removing missing values using: \`rename()\`, the \`stringr\` functions                     | NA...this topic is covered in “[R for Data Science](https://r4ds.had.co.nz/)” (see [5: Data Transformation](https://r4ds.had.co.nz/transform.html), [14: Strings](https://r4ds.had.co.nz/strings.html)). The [RegexOne tutorial](https://regexone.com/) on regular expressions will also help! |
