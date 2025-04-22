# Install OmniGenBench
```bash
#from source
git clone https://github.com/yangheng95/OmniGenBench
cd OmniGenBench
pip install -e .

# or from pypi
pip install omnigenome
```

# Download the data
The data is uploaded in the OGB.zip file. Please download the data from there directly.
```bash
wget https://github.com/COLA-Laboratory/ECMLPKDD_Supplementary/raw/main/OGB.zip
```

# Use baseline via AutoBench
```bash
autobench --model yangheng/PlantRNA-FM --benchmark OGB --trainer native 
```

# Upload the results
Find predictions in `prediction` folder. 
zip and upload the `prediction` folder to the competition website.

# OGB Submission Guide
[OGBSubmissionGuide.pdf](https://github.com/user-attachments/files/19833957/OGBSubmissionGuide.pdf)
