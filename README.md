# woRdcomplex-3.2
R script to determine word complexity version 3.2

Run the script locally in Rstudio. Text input should be in .txt files and include orthographic transcriptions (e.g. gloss or ordinary typed English) of words, sentences, paragraphs, etc.

A Shiny app is also available at https://unccard.shinyapps.io/shiny-woRdcomplex-2/.

Word Complexity Measure (WCM) is calculated as described in Stoel-Gammon (2010), based on lookup from a database including standard syllabified transcriptions for American English (cmudict.0.6d.syl; Bartlett et al., 2009) and word frequency measures from the SUBTLEX-US dictionary (Brysbaert & New, 2009). Word frequencies are displayed in Zipf units (van Heuven et al 2014), a logarithmic scale defined as log10(word frequency in words per billion), with distribution from approximately 1 (very low frequency) to 7 (high frequency function words, articles, etc.). As of ver 3.1, also includes calculation of Word Information Measure, based on Shannon entropy, and Moving Average Type Token Ratio -5 (MATTR-5), as referenced in Cunningham and Haley (2020), as well as several readability measures provided by the koRpus library (Michalke, 2018). 

Original version by Kevin Cunningham (1.1, 2021), with updates by Lindsay Greene with automated phonetic transcription analysis (2.1, 2023) and Adam Jacks (3.1, 2023, 3.2, 2026).

An applied example of this work is found at the following link: https://go.unc.edu/j6JRz

Jacks, A., Richardson, J.D., Greene, L.G., & Haley, K.L. (2022, February). Phonetic word complexity in narratives produced 
by people with AOS of varying etiology. Poster presented at: 21st Biennial Conference on Motor Speech, 2022 February; Charleston, SC.

References:

Bartlett, S., Kondrak, G., & Cherry, C. (2009, June). On the syllabification of phonemes. In Proceedings of human language technologies: The 2009 annual conference of the north american chapter of the association for computational linguistics (pp. 308-316).

Brysbaert, M., & New, B. (2009). Moving beyond Kučera and Francis: A critical evaluation of current word frequency norms and the introduction of a new and improved word frequency measure for American English. Behavior research methods, 41(4), 977-990.

Cunningham, K. T., & Haley, K. L. (2020). Measuring Lexical Diversity for Discourse Analysis in Aphasia: Moving-Average Type-Token Ratio and Word Information Measure. Journal of Speech, Language, and Hearing Research, 1-12.

Michalke, M. (2018). koRpus: An R Package for Text Analysis (Version 0.11-5). Available from https://reaktanz.de/?c=hacking&s=koRpus

Rinker, T. W. (2020). qdap: Quantitative Discourse Analysis Package. 2.3.6. Buffalo, New York. http://github.com/trinker/qdap

Stoel-Gammon, C. (2010). The Word Complexity Measure: Description and application to developmental phonology and disorders. Clinical linguistics & phonetics, 24(4-5), 271-282.

Van Heuven, W. J., Mandera, P., Keuleers, E., & Brysbaert, M. (2014). SUBTLEX-UK: A new and improved word frequency database for British English. Quarterly journal of experimental psychology, 67(6), 1176-1190.
