tool for generating supervised fine-tuning (SFT) data from arxiv papers.

```bash
python main.py scrape --query "your search query" --output_dir data --model gpt-4
python main.py train --output_dir data --model gpt-4 --fine_tuned_model your-fine-tuned-model
```

```bash
cd model-comparison-app
bun install
bun dev
```
open [http://localhost:3000](http://localhost:3000) in your browser

