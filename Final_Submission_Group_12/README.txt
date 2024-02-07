Final Project for CBSD 2023-2024

Group Members: Nour Al Housseini, Sofia Trogu, Fairouz Baz Radwan
Group Number: 12

Paper: SemEval-2012 Task 2: Measuring Degrees of Relational Similarity

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Description of Folders and Files in zip file:

> paper

Contains PDF of test paper, SemEval-2012 Task 2: Measuring Degrees of Relational Similarity

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

> raw_answers

Contains folder of Llama 2 responses to Maxdiff questions for each subcategory

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

> results
 
code: folder containing Perl scripts provided by authors and additional python file for determining significance of Spearman correlations. 

Maxdiff-llama-scores: folder containing output of perl script score_maxdiff.pl that generates MaxDiff accuracy score between llama answers and Turker Phase 2 Answers in each subcategory.

results.xslx: excel of final MaxDiff scores and Spearman correlations across all established systems and Llama for each subcategory.

Scaled-llama-answers: folder containing output of perl script maxdiff_to_scale.pl that produces a prototypicality rating per word pair from the Llama answers file for each subcategory.

Spearman-llama: folder containing output of perl script score_scale.pl that generates a Spearman correlation between the scaled Llama files and the Turker Gold Ratings files for each subcategory.

Turker_GoldRatings: folder containing output of perl script maxdiff_to_scale.pl for Turker's answers from Phase 2 for each subcategory.

Turker_Phase2Answers: folder containing Turker's responses to MaxDiff questions for each subcategory.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
