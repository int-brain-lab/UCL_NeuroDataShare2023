# UCL_NeuroDataShare2023
examples of scripts how to use IBL-BWM dataset

Installation:
1. Create environment :

conda create --name ibl python=3.9
conda activate ibl

2. Install IBL packages:

pip install ONE-api
pip install ibllib

3. Setting up credentials:

from one.api import ONE
one = ONE(base_url='https://openalyx.internationalbrainlab.org', password=pw, silent=True)

4. Clone BWM  git repository:

git clone https://github.com/int-brain-lab/paper-brain-wide-map.git
cd paper-brain-wide-map
pip install -e .

5. Clone git repository with examples for UCL_NeuroDataShare2023

git clone https://github.com/int-brain-lab/UCL_NeuroDataShare2023.git

Useful links:

1. ONE documentation - https://int-brain-lab.github.io/iblenv/notebooks_external/one_quickstart.html#
2. Viz website - https://viz.internationalbrainlab.org/app
3. Main website - https://www.internationalbrainlab.com
4. Task being performed by the mouse - https://doi.org/10.7554/eLife.63711
5. Neural data that has been recorded - https://int-brain-lab.github.io/iblenv/notebooks_external/data_release_repro_ephys.html
