# Project 3: 
Chinese Autonomous-Driving Research Rapidly Expands Its Presence in VLA and VLM

## Aim and Findings
In Project 3, I analyzed academic papers on autonomous driving. My aim was to examine China's impact on this field because I already knew that China was very strong in this area. I found that Chinese companies and universities have a significant influence, especially in the fields of VLMs and VLAs.

## Data Sources
| Data | Source | URL |
| --- | --- | --- |
| arXiv preprint data | arXiv API | [Link](https://info.arxiv.org/help/api/index.html) |
| Reference data | Semantic Scholar API | [Link](https://www.semanticscholar.org/product/api) |
| Language and country data | OpenAlex API | [Link](https://developers.openalex.org/) |

## Overview of the Data Collection Process
1. **General access**  
   I accessed the arXiv API and collected papers that included "autonomous driving" in their abstracts.
2. **Reference research**  
   I accessed the Semantic Scholar API and searched for reference information for each paper.
3. **Country research**  
   I accessed the OpenAlex API and searched for language and country information. Some papers had no data available in OpenAlex, so I collected the information manually.

## New Skills and Approaches
- **pandas** — general analysis of CSV data and creation of charts
- **API access** — retrieving recall data, although this did not work well
- **Scraping** — scraping with XPath

## Things I Wanted to Do but Could Not
I think there is a better way to represent the connections between papers. Some of the data was collected manually, so there is a possibility of errors.