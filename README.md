Spring 2017

# Regex Vocabulary

The program implements a vocabulary class that allows you to quickly search for subsets of words that match the query. A query is a sequence of characters that can contain a special symbol ? corresponding to any, but exactly one letter. The corresponding data structure is a set of nodes, each of which corresponds to a subset of words responding to a certain query, and if two different requests match the same subset of words, then the same node responds both of these requests. Links between nodes correspond to the specifics of letters in queries, ie, for example, if there is a node responding to the query ?a?, then the specification b of the first letter should lead to the node responding to the query ba?
