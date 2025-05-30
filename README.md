# Carceral Technology: Systematic Literature Review

The code is hosted on github at <https://github.com/drnikko/carceral-tech-systematic-review>.

To start: the `bibs` folder has all of the exports from the database searches in each database's default format.

The `data_sources.Rmd` has descriptions and file counts from each search along with the appropriate file names.

`literature_review.Rmd` is where the sources are gathered and analyzed to develop a complete list of search terms (this is recommended as part of [PRISMA](https://www.prisma-statement.org) guidelines on systematic literature reviews.

`search_terms.csv` is a result of a keyword analysis performed in `literature_review.Rmd` using litsearchr, an r packaged designed to reduce bias when conducting searches.
