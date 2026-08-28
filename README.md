> **Context:** THE 6TH VIETNAM SCHOOL OF EARTH OBSERVATION
SATELLITE ALTIMETRY - A TOOL FOR CONTINENTAL WATER MONITORING - September 07–12, 2026 at ICISE in Quy Nhon, Vietnam


# VSEO-6 Training Session : Flood case study

Practical sessions exploring how SWOT PIXC and RiverSP observations can be used to monitor flooding events.

## Access the notebooks

### Local with windows
1. Install git for windows: https://git-scm.com/install/windows
2. Install conda for windows: https://docs.conda.io/en/latest/miniconda.html
3. From a terminal from « Windows PowerShell », run the same command as for linux

### Local with linux
From a terminal, run the following commands:
```sh
git clone https://github.com/sertit/swot-flood-case-study.git
cd swot-flood-case-study
conda env create -f environment.yml
conda activate swot-flood
python -m ipykernel install --user --name=swot-flood --display-name="swot-flood"
jupyter notebook
```

### Online
1. Go to: https://mybinder.org/

2. Fill in the following fields:
- **GitHub:** https://github.com/sertit/swot-flood-case-study
- **Launch** OR copy the resulting url in another web tab