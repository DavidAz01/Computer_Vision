# Computer_Vision

## Dataset setup

Open [01_get_datasets.ipynb](01_get_datasets.ipynb) and select the local `.venv`
Python kernel. Run the setup cells, then enable the acquisitions you need.
Notebook dependencies are listed in [requirements.txt](requirements.txt).

The notebook covers PIDray, STCray, and optional SIXray/SIXray-D from the research
presentation. It uses official sources, skips model weights, and stores archives,
extracted data, caches, and an acquisition inventory under `datasets/`.
Virtual environments and dataset contents are ignored by Git.

STCray requires Hugging Face access approval and terminal authentication.
PIDray's official Drive folder currently exposes annotations but not images;
SIXray's published direct mirror is unavailable and SIXray-D requires a request.
The notebook documents official alternatives and does not mark missing data as
ready. Extract the archives and verify images, annotations, and official splits
before training. Keep the external datasets test-only.