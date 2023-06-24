## Evaluation-of-ChatGPT-on-Information-Extraction
An Evaluation of ChatGPT on Information Extraction task, including Named Entity Recognition (NER), Relation Extraction (RE), Event Extraction (EE) and Aspect-based Sentiment Analysis (ABSA).



## Test with API

```
bash ./scripts/absa/eval.sh
bash ./scripts/ner/eval.sh
bash ./scripts/re/eval_rc.sh
bash ./scripts/re/eval_triplet.sh
bash ./scripts/ee/eval_trigger.sh
bash ./scripts/ee/eval_argument.sh
bash ./scripts/ee/eval_joint.sh
```
Before testing, you need to modify all ``--api_key`` and ``--result_file`` arguments in all ``*.sh `` scripts.


## Get Evaluation Metrics
```
bash ./scripts/absa/report.sh
bash ./scripts/ner/report.sh
bash ./scripts/re/report_rc.sh
bash ./scripts/re/report_triplet.sh
bash ./scripts/ee/report_trigger.sh
bash ./scripts/ee/report_argument.sh
bash ./scripts/ee/report_joint.sh
```
