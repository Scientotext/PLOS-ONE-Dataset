### Data from ISSI paper:
# Highly cited references in PLOS ONE and their in-text usage over time
* **authors:** Wolfgang Otto, Behnam Ghavimi, Philipp Mayr, RajeshPiryani, Vivek Kumar Singh
* (**link to preprint**)[https://arxiv.org/pdf/1903.11693.pdf]

## Description
### Contexts and Metadata of referenced Publications (**sciento_text_666.zip**)
#### Citation contexts:
 * **File:** contexts_ref_gt_100.json
 * **Description:** contains all relevant contexts citing the top 666 referenced publications
 * **Sample:**
```json
[{
"filename": "PMC4769282.nxml",
"sentence":
 "Epidemiological and experimental studies have shown that the 
inflammatory microenvironment is an indispensable participant in the 
neoplastic process, including development, proliferation, survival, and 
migration of many cancers [1].", 
"relative_position": 0.005681818181818182,
"section_title": "Introduction",
"sentence_nr": 0,
"section_nr": 0,
"sentence_in_paper": 0, 
"paragraph_nr": 0,
"ref_concrete": "pone.0149897.ref001", 
"doi": "10.1371/journal.pone.0149897",
"references": ["pone.0149897.ref001"],
"ref_pmid": 12490959
}, …]
```

#### Metadata of referenced Object:
* **File:** metadata_references_gt_100.csv
* **Fields:** pubmed,article_title,year,authors,volume,issue,fpage,lpage,page_range

* **Sample:**
```csv
388439,Electrophoretic transfer of proteins from polyacrylamide gels to nitrocellulose sheets: procedure and some applications. ,1979,"[{""given-names"": ""H"", ""surname"": ""Towbin""}, {""given-names"": ""T"", ""surname"": ""Staehelin""}, {""given-names"": ""J"", ""surname"": ""Gordon""}]",76,9,4350,4354,
```

### Metadata of citing Objects (**metadata.zip**)
  * **Sample:**
```csv
filename,doi,pmc,
pmid,publisher-id,has_relevant_contexts,
article_title,year,abstract,
wos_keyword,mas_title_kw,mas_abstract_kw,
mas_num_kw_found,mas_num_matched_kw,
mas_discipline,pone_discipline,
pone_categories,wos_citationcount,
cluster_topic_modeling
```













