# Dm-Test
Dm test, a test to detect natural selection in DNA methylation using Single Methylation Polymorphisms (SMPs)

The main purpose of the Dm_test.pl script is to detect the footprint of selection force in DNA methylation using SMP data. The underlying model of the test assumes the mutation rates among the cytosine sites of a locus following a gamma distribution, and requires the alpha parameter of the gamma distribution as the input. The alpha_estimation.pl, which requires the diff_two_seq.pl script, is for estimating the alpha value. See the -man/-help options for options and data preparation of the two scripts.

Citation:
Jun Wang and Chuanzhu Fan. 2015. A neutrality test for detecting selection on DNA methylation using single methylation polymorphism frequency spectrum. Genome Biology and Evolution 7: 154-171.

