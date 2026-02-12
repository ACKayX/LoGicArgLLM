### UNZIP data.zip before utilisation.

### Utilisation 
./go.sh : 
Run the web UI

./run.sh : 
Fetch data for a single dataset; once completed, you can use ./go.sh to perform reasoning on the data

### Folder
- configs: Stores prompts
- data: Stores datasets and the generated arguments; each run reads the latest res for storage/reasoning
- result: Stores the results of a dataset, from which condition/semantic weights are computed
structures them into JSON.
