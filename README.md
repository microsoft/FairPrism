# FairPrism

This repository contains the FairPrism dataset, introduced in "FairPrism: Evaluating Fairness-Related Harms in Text Generation." The dataset consists of 5,000 examples of AI-generated text annotated for the harms that the text can cause.

To request dataset access, please email fairprism@microsoft.com with your name, affiliation, and a brief description of your use case.

Specifically, please address:
- **Will FairPrism be used as part of training data for mitigation methods?**
Directly using FairPrism to train classifiers for mitigating fairness-related harms prevents it from being
useful as a measurement instrument.

- **Will FairPrism be used as a benchmark to be beaten?**
If AI systems are repeatedly trained to improve on any single aggregate metric calculated using FairPrism, this will result in overfitting to the dataset, which will make the dataset less useful for measurement and may also result in a false sense of complete coverage.

- **Are there specific applications you are considering?**
FairPrism contains examples of text generated in both reply scenarios and continuation scenarios. Its efficacy will therefore lesson for applications that are further removed from these scenarios and applications that are highly specific. FairPrism is also less well suited to measuring harms relating to demographic groups other than those based on gender and sexuality, specific to countries other than the U.S. and Canada, and in languages other than English.

Any additional details you could provide would be helpful.

For further information about privacy and this dataset, please see the Microsoft Privacy Statement: https://go.microsoft.com/fwlink/?LinkId=521839

To cite this dataset, please use:

@inproceedings{fleisig-etal-2023-fairprism,

  title = "{FairPrism}: Evaluating Fairness-Related Harms in Text Generation",

  author = "Fleisig, Eve and

    Amstutz, Audrie and

    Atalla, Chad and

    Blodgett, Su Lin and

    Daum{\'e} III, Hal and

    Olteanu, Alexandra and

    Sheng, Emily and

    Vann, Dan and

    Wallach, Hanna",

    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics",

    month = jul,
    
    year = "2023",

    address = "Toronto, Canada",

    publisher = "Association for Computational Linguistics",

    url = "https://github.com/microsoft/FairPrism/blob/main/FairPrism_paper.pdf"
}
