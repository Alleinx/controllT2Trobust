# Controllable Data to Text

_Code repository for the EACL 2023 paper "Improving User Controlled Table-To-Text Generation Robustness"._

- **Paper url**: https://aclanthology.org/2023.findings-eacl.175/

- **Cite as:**
```
@inproceedings{hu-etal-2023-improving,
    title = "Improving User Controlled Table-To-Text Generation Robustness",
    author = "Hu, Hanxu  and
      Liu, Yunqing  and
      Yu, Zhongyi  and
      Perez-Beltrachini, Laura",
    booktitle = "Findings of the Association for Computational Linguistics: EACL 2023",
    month = may,
    year = "2023",
    address = "Dubrovnik, Croatia",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-eacl.175",
    pages = "2317--2324",
    abstract = "In this work we study user controlled table-to-text generation where users explore the content in a table by selecting cells and reading a natural language description thereof automatically produce by a natural language generator. Such generation models usually learn from carefully selected cell combinations (clean cell selections); however, in practice users may select unexpected, redundant, or incoherent cell combinations (noisy cell selections). In experiments, we find that models perform well on test sets coming from the same distribution as the train data but their performance drops when evaluated on realistic noisy user inputs. We propose a fine-tuning regime with additional user-simulated noisy cell selections. Models fine-tuned with the proposed regime gain 4.85 BLEU points on user noisy test cases and 1.4 on clean test cases; and achieve comparable state-of-the-art performance on the ToTTo dataset.",
}
```
---




