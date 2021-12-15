## Code for Dependency Parsing as an Upstream Task for Logical Reasoning
Below is an overview on each nodebook, showcasing different methods in the project:
- `00_dependency_parser.ipynb` - Parses input data into standard dependency tree format
- `01_baseline_models.ipynb` - Trains BERT and RoBERTa models on exclusively ReClor
- `02_roberta_with_dependency.ipynb` - Appends context and question dependency trees to input
- `03_roberta_with_dependency_and_bert.ipynb` - Modifies BERT attention mask to include dependency trees

Download ReClor data and extract to `data/` directory. Make sure to run `00_dependency_parser.ipynb` first to create the dependency trees then the notebooks can be run in any order.