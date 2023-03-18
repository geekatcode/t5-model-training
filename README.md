# t5 model training
Training & Fine tuning T5 base model for NLP

Base Model:
- T5 (https://huggingface.co/t5-base)

Dataset:
- WikiSQL (https://huggingface.co/datasets/viewer/?dataset=wikisql)
- Local JSON file (in data folder)

Packages to be installed (if not already):
- pip3 install numpy
- pip3 install transformers
- pip3 install datasets
- pip3 install rouge_score
- pip3 install evaluate

WikiSQL Dataset:
DatasetDict({
        test: Dataset({
            features: ['phase', 'question', 'table', 'sql'],
            num_rows: 15878
        })
        validation: Dataset({
            features: ['phase', 'question', 'table', 'sql'],
            num_rows: 8421
        })
        train: Dataset({
            features: ['phase', 'question', 'table', 'sql'],
            num_rows: 56355
        })
    })
