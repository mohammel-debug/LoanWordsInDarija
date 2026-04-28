# Loanword Extraction in Moroccan Darija (DODa)

This project focuses on the identification and extraction of non-Arabic loanwords from the **Darija Open Dataset (DODa)**. Using an iterative approach combined with Unix-based automated extraction, we expanded a small seed list of borrowings into a broader lexicon of unique loanword tokens.

## Results Summary
Through four rounds of iterative extraction, we processed 3,995 sentences and identified **487 unique loanword tokens**.

<img width="374" height="330" alt="image" src="https://github.com/user-attachments/assets/ee2242ad-15ab-49d4-a2e0-fa268910de40" />

## Methodology
The project follows the theoretical framework established by **Heath (1989)**, distinguishing between spontaneous code-switching and integrated borrowings.

The extraction pipeline uses Unix stream processing:
1. **Initial Annotation:** Manual identification of loans in a subset of DODa.
2. **Expansion:** Using `grep` with whole-word matching to identify known loans in the remaining corpus.
3. **Deduplication:** Comparing vocabularies across rounds to isolate new lexical entries.

## References
* Heath, J. (1989). *From Code-Switching to Borrowing: Foreign and Diglossic Mixing in Moroccan Arabic*.
* DODa (Darija Open Dataset) Corpus.

## Author
**Mohammed El khamlichi**
