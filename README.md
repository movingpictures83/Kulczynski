# Kulczynski
# Language: R
# Input: CSV (abundances)
# Output: CSV (dissimilarities)
# Tested with: PluMA 1.1, R 4.0.0
# Dependency: vegan_2.5.6

PluMA plugin to compute dissimilarity, using Kulczynski's method (Kulczynski, 1927).
The plugin accepts input in the form of a CSV file, with rows representing samples and columns
representing community members.  Entry (i, j) then contains the abundances of member j in sample i.

The plugin then produces an output file of dissimilarities, also in CSV format, with both
rows and columns representing samples and entry (i, j) is the dissimilarity between sample i and sample j.
