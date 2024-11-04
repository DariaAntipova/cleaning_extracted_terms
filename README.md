# cleaning_extracted_terms

This notebook is one stage in the process of automatically updating glossaries. It processes terms extracted from source text that have no matches in the client glossaries. To ensure the quality of auto-updated glossaries, a formal cleaning stage was introduced, including:

1.	Removing named entities
Named entities are removed to ensure that humans handle these additions, as they require special care.
2.	Filtering out overly long terms and terms with uncommon symbols
Terms that are too long or contain symbols not typically found in manually created glossaries are excluded.
3.	Removing terms without original language letters or all uppercase terms
Terms without letters from the source language or composed solely of uppercase letters are excluded.

This filtering step aims to ensure the glossary remains relevant and clear.
