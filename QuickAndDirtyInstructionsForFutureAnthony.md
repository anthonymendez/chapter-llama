1. Clone this repo.
2. Download and install Anaconda.
3. Activate the environment:
```bash
conda activate chapter-llama
```
4. Make sure to agree with Llama 3.1 license on Hugging Face. https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct
5. Download the model:
```bash
python tools/download/models.py "captions_asr-10k" --local_dir "."
python tools/download/models.py "asr-10k" --local_dir "."
```
6. Download captions model.
```bash
sudo bash ./tools/download/captions.sh
```
7. Download the ASR and chapter dataset.
```bash
sudo bash ./tools/download/docs.sh full
```
Now it should be ready for usage. Pending on approval for meta.