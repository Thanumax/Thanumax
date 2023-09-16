cat environment.yml | \
  grep -v -E 'nvidia|cuda' > environment-no-nvidia.yml && \
    conda env create -f environment-no-nvidia.yml
conda activate stylegan3

# On MacOS
export PYTORCH_ENABLE_MPS_FALLBACK=1environment-no-nvidia.ymlpip install -r requirements.txtrequirements.txtconda env create -f environment.yml
conda activate stylegan3environment.yml
