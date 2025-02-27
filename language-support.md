---

copyright:
  years: 2019, 2021
lastupdated: "2021-03-12"

subcollection: discovery-data

---

{:shortdesc: .shortdesc}
{:external: target="_blank" .external}
{:tip: .tip}
{:note: .note}
{:pre: .pre}
{:important: .important}
{:deprecated: .deprecated}
{:codeblock: .codeblock}
{:screen: .screen}
{:download: .download}
{:hide-dashboard: .hide-dashboard}
{:apikey: data-credential-placeholder='apikey'} 
{:url: data-credential-placeholder='url'}
{:curl: .ph data-hd-programlang='curl'}
{:javascript: .ph data-hd-programlang='javascript'}
{:java: .ph data-hd-programlang='java'}
{:python: .ph data-hd-programlang='python'}
{:ruby: .ph data-hd-programlang='ruby'}
{:swift: .ph data-hd-programlang='swift'}
{:go: .ph data-hd-programlang='go'}
{:external: target="_blank" .external}

# Language support
{: #language-support}

| Language | Supported features|
|:---|:---|
| Arabic (`ar`) | Parts of speech, Keywords, Entities, Document sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding |
| Bosnian (`bs`)\* | Parts of speech, Dictionary, Regular expressions |
| Chinese, simplified (`zh-CN`) | Parts of speech, Keywords, Entities, Document sentiment, Phrase sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding |
| Chinese, traditional</br> (`zh-TW`) | Parts of speech, Phrase sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding |
| Croatian (`hr`)\* | Parts of speech, Dictionary, Regular expressions|
| Czech (`cs`) | Parts of speech, Phrase sentiment, Dictionary, Regular expressions, Smart Document Understanding, Table Understanding  |
| Danish (`da`) | Parts of speech, Dictionary, Regular expressions, Smart Document Understanding, Table Understanding |
| Dutch (`nl`) |Parts of speech, Keywords, Entities, Document sentiment, Phrase sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding |
| English (`en`) | Parts of speech, Keywords, Entities, Document sentiment, Phrase sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding |
| Finnish (`fi`) | Parts of speech, Dictionary, Regular expressions, Smart Document Understanding, Table Understanding |
| French (`fr`) | Parts of speech, Keywords, Entities, Document sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding |
| German (`de`) | Parts of speech, Keywords, Entities, Document sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding |
| Hebrew (`he`) | Parts of speech, Dictionary, Regular expressions, Smart Document Understanding, Table Understanding |
| Hindi (`hi`)\* | Parts of speech, Dictionary, Regular expressions |
| Italian (`it`) | Parts of speech, Keywords, Entities, Document sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding |
| Japanese (`ja`) | Parts of speech, Keywords, Entities, Document sentiment, Phrase sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding |
| Korean (`ko`) | Parts of speech, Keywords, Entities, Document sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding |
| Norwegian (Bokma&#778;l) (`nb`) | Parts of speech, Dictionary, Regular expressions, Smart Document Understanding, Table Understanding |
| Norwegian (Nynorsk) (`nn`) | Parts of speech, Dictionary, Regular expressions, Smart Document Understanding, Table Understanding |
| Polish (`pl`) |  Parts of speech, Dictionary, Regular expressions, Smart Document Understanding, Table Understanding |
| Portuguese, Brazilian (`pt-br`) | Parts of speech, Keywords, Entities, Document sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding |
| Romanian (`ro`) | Parts of speech, Phrase sentiment, Dictionary, Regular expressions, Smart Document Understanding, Table Understanding  |
| Russian (`ru`) | Parts of speech, Phrase sentiment, Dictionary, Regular expressions, Smart Document Understanding, Table Understanding |
| Serbian (`sr`)\* | Parts of speech, Dictionary, Regular expressions|
| Slovak (`sk`) | Parts of speech, Dictionary, Regular expressions, Smart Document Understanding, Table Understanding |
| Spanish (`es`) | Parts of speech, Keywords, Entities, Document sentiment, Phrase sentiment, Dictionary, Regular expressions, Machine Learning, Advanced rule models, Smart Document Understanding, Table Understanding  |
| Swedish (`sv`) | Parts of speech, Dictionary, Regular expressions, Smart Document Understanding, Table Understanding |


\* **Optical character recognition (OCR)** is not available for Bosnian, Croatian, Hindi, and Serbian. Serbian supports Latin script only.

You can select the collection language when you create your collection. See [Creating and managing collections](/docs/discovery-data?topic=discovery-data-collections). 
{: tip}

 ![Cloud Pak for Data only](images/desktop.png) **{{site.data.keyword.icp4dfull_notm}}**: For version 2.1.2 non-English language support, you must install the optional language pack `ibm-watson-discovery-pack1-prod`. Installation instructions for `ibm-watson-discovery-pack1-prod` are available in the [Installing the optional language pack](https://www.ibm.com/support/knowledgecenter/SSQNUZ_2.5.0/cpd/svc/watson/discovery-install.html){: external} section of the {{site.data.keyword.discovery-data_long}} installation instructions. The language pack does not need to be installed separately in {{site.data.keyword.discovery-data_long}} version 2.1.3 or later.
{: note}

## English-only support
{: #feature-support}

The following features are currently supported in English only:

-  [Discovery for Content Intelligence](/docs/discovery-data?topic=discovery-data-output_schema).
-  ![IBM Cloud only](images/cloudonly.png) [Patterns enrichment (beta)](/docs/discovery-data?topic=discovery-data-create-enrichments#patterns-enrichment)