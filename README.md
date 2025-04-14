# MSc Thesis Code: National Statistical Institutes (NSIs)

This repository contains the code used for analyzing documents from three National Statistical Institutes (NSIs):

- **ABS (Australia)**
- **StatCan (Canada)**
- **CBS General (Netherlands) — NL_GEN**
- **CBS Long Reads (Netherlands) — NL_LR**

## Structure

Each NSI has its own folder containing the following scripts: (where there is NSI replace with the NSI name)

- **NSI_Making_URLS.ipynb**: Generates a sitemap of available pages (only for ABS + StatCan).
- **NSI_Scraping_URLS.ipynb**: Scrapes HTML content from the sitemap links.
- **NSI_Scraping_Text.ipynb**: Extracts raw text from the HTML content.
- **NSI_H1.ipynb**: Performs descriptive statistics and visualisations relevant for **RQ1**.
- **NSI_H3.ipynb**: Performs descriptive statistics and visualisations relevant for **RQ3** (only for NL_GEN).
- **LDA_NSI.ipynb**: Performs tokenization and Latent Dirichlet Allocation for topic modeling (**RQ1** only applicable to StatCan, ABS, and CBS General).
- **H2**: Performs paired t-test and visualisations for **H2 Long Reads** (only in NL_LR).

Under the **NL_GEN Yearly_art** folder, there is an extra file showing visualisations for **H2** for CBS General called **H2_Visualisation_Gen.ipynb**.
