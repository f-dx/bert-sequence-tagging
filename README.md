Sequence labeling based on BERT

Jacob's work, Jacob, said he is not prepared to release the code for the sequence tag, but you can see the discussion of Jacob's participation in the issue.

The Repo is not directly executable, but if you really need this implementation, you should understand it to a large extent.

Sequence tagging can be used in many places, NER, POS, etc. Maybe the recent Tianchi Ruijin game can also be tried. Kaggle's latest text classification game can also be tried, but Kaggle's new game directly using Jacob's published code should not be needed. Modify a lot of places.

Based on the google-bert source code, write the sequence tagging module and make a preliminary test on the CGED data of IJCNLP. The experimental results are shown in the figure below.

Among them, the top picture is the result of the code C++ released by a group of Harbin Institute of Technology in 2017; the middle picture is the result I reproduced with Tensorflow; the figure below is a result obtained by fine-tuning based on BERT.

From the results, it seems that there is no problem in the implementation.
