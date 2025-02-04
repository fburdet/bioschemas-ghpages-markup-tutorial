One of the results of the web-app [TREC-doc-2-doc-relevance](https://github.com/zbmed-semtec/TREC-doc-2-doc-relevance) is the measure of the inter-annotator agreement on the task of document-to-document relevance assessment using Fleiss' kappa. 

This page has been created to embed schema.org and Bioschemas markup describing the [Fleiss kappa for doc-2-doc relevance assessment](https://doi.org/10.5281/zenodo.7338056) dataset and its current release deposited in Zenodo. 

<script type="application/ld+json">
  { 
    "@context": "https://schema.org", 
    "@type": "SoftwareSourceCode",
    "@id": "https://github.com/zbmed-semtec/TREC-doc-2-doc-relevance",
    "citation": "Talha M, Geist L, Fellerhof T, Ravinder R, Giraldo O, Rebholz-Schuhmann D, et al. TREC-doc-2-doc-relevance [Software source code]. GitHub; 2022.",
    "name": "TREC-doc-2-doc-relevance",
    "description": "This is the software source code facilitating the creation of a doc-2-doc relevance assessment on PMIDs used in the TREC 2005 Genomics track along with its metadata.",
    "url": "https://github.com/zbmed-semtec/TREC-doc-2-doc-relevance#",
    "targetProduct": { 
      "@id": "https://doi.org/10.5281/zenodo.7341391"
    },
    "license": {
      "@type": "CreativeWork",
      "@id": "http://spdx.org/licenses/MIT",
      "name": "MIT License", 
      "url": "https://opensource.org/license/mit/"
    },
    "author": [
      {"@id": "https://zbmed-semtec.github.io/previous_members/#muhammad-talha"},
      {"@id": "https://orcid.org/0000-0002-2910-7982"},
      {"@id": "https://orcid.org/0000-0002-8725-1317"},
      {"@id": "https://orcid.org/0009-0004-4484-6283"},
      {"@id": "https://orcid.org/0000-0003-2978-8922"},
      {"@id": "https://orcid.org/0000-0002-1018-0370"},
      {"@id": "https://orcid.org/0000-0003-3986-0510"}
    ]
  }
<7script>

<script type="application/ld+json">
  {
    "@context": "https://schema.org", 
    "@type": "Dataset",
    "@id": "https://doi.org/10.5281/zenodo.7338056",
    "conformsTo": "https://bioschemas.org/profiles/Dataset/1.1-DRAFT", 
    "identifier": "DOI:10.5281/zenodo.7338056",
    "citation": "Giraldo O, Solanki D, Rebholz-Schuhmann D, Castro LJ. Fleiss kappa for doc-2-doc relevance assessment. Zenodo; 2022. doi:10.5281/zenodo.7338056",
    "name": "Fleiss kappa for doc-2-doc relevance assessment",
    "description": "Fleiss' kappa measuring inter-annotator agreement on a document-to-document relevance assessment task. The table contains 7 columns, the first one presents the topics, 8 in total. The second column shows the \"reference articles\", represented by their PubMed-ID and organized by topic. The third column shows the Fleiss’ Kappa results. The fourth column shows the interpretation of the Fleiss' Kappa results being: i) \"Poor\" results <0.20, ii) \"Fair\" results within 0.21 - 0.40, and iii) \"Moderate\" results within 0.41 - 0.60. The fifth column shows the PubMed-IDs of evaluation articles rated by the four annotators as \"Relevant\" regarding its corresponding \"reference article\". The sixth column shows the PubMed-IDs of evaluation articles rated by the four annotators as \"Partially relevant\" regarding its corresponding \"reference article\". The seventh column shows the PubMed-IDs of evaluation articles rated by the four annotators as \"Non-relevant\" regarding its corresponding \"reference article\".",
    "keywords": "Fleiss' Kappa, Inter-annoator agreement, TREC Genomics Track 2005, relevance assessment", 
    "license": {
      "@type": "CreativeWork",
      "@id": "http://spdx.org/licenses/CC-BY-4.0",
      "name": "Creative Commons Attribution 4.0 International", 
      "alternateName": "CC BY 4.0",
      "url": "https://creativecommons.org/licenses/by/4.0/"
    },
    "url": "https://zenodo.org/record/7338056",
    "datePublished": "2022-11-19",
    "author": [                
      {"@id": "https://orcid.org/0000-0003-2978-8922"},
      {"@id": "https://orcid.org/0009-0004-1529-0095"},
      {"@id": "https://orcid.org/0000-0002-1018-0370"},
      {"@id": "https://orcid.org/0000-0003-3986-0510"}
    ]
  }
  </script>

  <script type="application/ld+json">
  { 
    "@context": "https://schema.org", 
    "@type": "SoftwareApplication",
    "@id": "https://doi.org/10.5281/zenodo.7341391",
    "http://purl.org/dc/terms/conformsTo": "https://bioschemas.org/profiles/ComputationalTool/1.0-RELEASE",
    "identifier": "DOI:10.5281/zenodo.7341391",
    "citation": "Talha M, Geist L, Fellerhof T, Ravinder R, Giraldo O, Rebholz-Schuhmann D, et al. TREC-doc-2-doc-relevance assessment interface. Zenodo; 2022. doi:10.5281/zenodo.7341391",
    "name": "TREC-doc-2-doc-relevance assessment interface",
    "description": "The code, data and docs at this release aim at facilitating the creation of a doc-2-doc relevance assessment on PMIDs used in the TREC 2005 Genomics track. A doc-2-doc relevance assessment takes one document as reference and assess a second document regarding its relevance to the reference one. This doc-2-doc collection will be used to evaluate the doc-2-doc recommendations approaches that we are working on.",
    "url": "https://zenodo.org/records/7341391",
    "softwareVersion": "1.0.0",
    "datePublished": "2022-11-21",
    "license": {
      "@type": "CreativeWork",
      "@id": "http://spdx.org/licenses/MIT",
      "name": "MIT License", 
      "url": "https://opensource.org/license/mit/"
    },
    "author": [
      {"@id": "https://zbmed-semtec.github.io/previous_members/#muhammad-talha"},
      {"@id": "https://orcid.org/0000-0002-2910-7982"},
      {"@id": "https://orcid.org/0000-0002-8725-1317"},
      {"@id": "https://orcid.org/0009-0004-4484-6283"},
      {"@id": "https://orcid.org/0000-0003-2978-8922"},
      {"@id": "https://orcid.org/0000-0002-1018-0370"},
      {"@id": "https://orcid.org/0000-0003-3986-0510"}
    ]
  }
</script>

<script type="application/ld+json">
  
  {
    "@context": "https://schema.org", 
    "@type": "Dataset",
    "@id": "https://doi.org/10.5281/zenodo.7338056",
    "conformsTo": "https://bioschemas.org/profiles/Dataset/1.1-DRAFT", 
    "identifier": "DOI:10.5281/zenodo.7338056",
    "citation": "Giraldo O, Solanki D, Rebholz-Schuhmann D, Castro LJ. Fleiss kappa for doc-2-doc relevance assessment. Zenodo; 2022. doi:10.5281/zenodo.7338056",
    "name": "Fleiss kappa for doc-2-doc relevance assessment",
    "description": "Fleiss' kappa measuring inter-annotator agreement on a document-to-document relevance assessment task. The table contains 7 columns, the first one presents the topics, 8 in total. The second column shows the \"reference articles\", represented by their PubMed-ID and organized by topic. The third column shows the Fleiss’ Kappa results. The fourth column shows the interpretation of the Fleiss' Kappa results being: i) \"Poor\" results <0.20, ii) \"Fair\" results within 0.21 - 0.40, and iii) \"Moderate\" results within 0.41 - 0.60. The fifth column shows the PubMed-IDs of evaluation articles rated by the four annotators as \"Relevant\" regarding its corresponding \"reference article\". The sixth column shows the PubMed-IDs of evaluation articles rated by the four annotators as \"Partially relevant\" regarding its corresponding \"reference article\". The seventh column shows the PubMed-IDs of evaluation articles rated by the four annotators as \"Non-relevant\" regarding its corresponding \"reference article\".",
    "keywords": "Fleiss' Kappa, Inter-annoator agreement, TREC Genomics Track 2005, relevance assessment", 
    "license": {
      "@type": "CreativeWork",
      "@id": "http://spdx.org/licenses/CC-BY-4.0",
      "name": "Creative Commons Attribution 4.0 International", 
      "alternateName": "CC BY 4.0",
      "url": "https://creativecommons.org/licenses/by/4.0/"
    },
    "url": "https://zenodo.org/record/7338056",
    "datePublished": "2022-11-19",
    "author": [                
      {"@id": "https://orcid.org/0000-0003-2978-8922"},
      {"@id": "https://orcid.org/0009-0004-1529-0095"},
      {"@id": "https://orcid.org/0000-0002-1018-0370"},
      {"@id": "https://orcid.org/0000-0003-3986-0510"}
    ]
  }
</script>
