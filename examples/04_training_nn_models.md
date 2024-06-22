## How to 

begin: data science | data engineer / data pipeline
medium: ml engineer | ml modeling
high: tech lead | architect solution (do it)
higher/manager: senior manager / principle level (tech/dev) / solution architect  | draw diagram

```mermaid
sequenceDiagram

  participant S as Start
  participant DTA as Data
  participant DCAT as Data Category
  participant MOD as Modeling
  participant TR as Training or Finetuning
  participant EV as Evaluation
  participant ED as End

  S->>DTA: Go to kaggle, and download data
  DTA->>DCAT: Understand X (b&w) and Y (7 classes)
  DCAT->>MOD: Write pt/tf code to build the model (ViT)
  MOD->>TR: Training
  loop learning cycle
    TR->>EV: Evaluate the model / assess performance
    EV->>MOD: Update the model
    MOD->>TR: Finetuning
    TR->>EV: Evaluate the model / assess performance
  end
  EV->>ED: Finish the project
```
