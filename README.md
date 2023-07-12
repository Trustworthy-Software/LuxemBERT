# LuxemBERT

LuxemBERT is a BERT model for the Luxembourgish language created in collaboration between the TruX research group at SnT and BGL BNP Paribas. 

The model was trained using 6.1 million Luxembourgish sentences from various sources including the Luxembourgish Wikipedia, the Leipzig Corpora Collection and rtl.lu. In addition, we partially translated 6.1 million sentences from the German Wikipedia from German to Luxembourgish as means of data augmentation. This gave us a dataset of 12.2 million sentences we used to train our LuxemBERT model.
For more information, we invite you to read our paper: https://aclanthology.org/2022.lrec-1.543/

LuxemBERT is available on Huggingface at https://huggingface.co/lothritz/LuxemBERT

In addition to the model, we created multiple datasets for evaluation purposes.
These tasks include Part-of-Speech tagging, Named Entity Recognition, News Classification, and a Luxembourgish version of the Winograd Natural Language Inference task. (https://cs.nyu.edu/~davise/papers/WinogradSchemas/WS.html)

We make the WNLI dataset publically available. If you would like to access the POS, NER, or News Classification datasets, please send a request to cedric.lothritz [at] uni.lu

If you would like to use the LuxemBERT model or any of the datasets, please cite our paper:

```
@inproceedings{lothritz-etal-2022-luxembert,
    title = "{L}uxem{BERT}: Simple and Practical Data Augmentation in Language Model Pre-Training for {L}uxembourgish",
    author = "Lothritz, Cedric  and
      Lebichot, Bertrand  and
      Allix, Kevin  and
      Veiber, Lisa  and
      Bissyande, Tegawende  and
      Klein, Jacques  and
      Boytsov, Andrey  and
      Lefebvre, Cl{\'e}ment  and
      Goujon, Anne",
    booktitle = "Proceedings of the Thirteenth Language Resources and Evaluation Conference",
    month = jun,
    year = "2022",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "https://aclanthology.org/2022.lrec-1.543",
    pages = "5080--5089",
    abstract = "Pre-trained Language Models such as BERT have become ubiquitous in NLP where they have achieved state-of-the-art performance in most NLP tasks. While these models are readily available for English and other widely spoken languages, they remain scarce for low-resource languages such as Luxembourgish. In this paper, we present LuxemBERT, a BERT model for the Luxembourgish language that we create using the following approach: we augment the pre-training dataset by considering text data from a closely related language that we partially translate using a simple and straightforward method. We are then able to produce the LuxemBERT model, which we show to be effective for various NLP tasks: it outperforms a simple baseline built with the available Luxembourgish text data as well the multilingual mBERT model, which is currently the only option for transformer-based language models in Luxembourgish. Furthermore, we present datasets for various downstream NLP tasks that we created for this study and will make available to researchers on request.",
}
```
Additionally, if you would like to use wither the L-SST2, L-RTE, or Sentence Negation datasets,
 please cite our following paper:

 [reference forthcoming]
