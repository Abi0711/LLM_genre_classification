# LLM Genre Classification

Given an excerpt of text from a novel I have finetuned DistilBert to classify the genre of the provided texts. There are four possible genres; Horror, Science Fiction, Humour and Crime Fiction. Due to the imbalanced data, I have used F1 score to evaluate the best model.

Due to the small number of train examples, I have added a weight decay such that the model does not overfit to the data. Furthermore, I have completed a 5-fold cross-validation to determine the best hyperparameters for the model.

Completed in Document Analysis
