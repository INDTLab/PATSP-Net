# PATSP-Net
<p align="center"> 
<a href="" ><img src="https://img.shields.io/badge/HOME-IEEE TIP-blue.svg"></a>
<a href="" ><img src="https://img.shields.io/badge/HOME-Paper-important.svg"></a>
<a href="" ><img src="https://img.shields.io/badge/PDF-Paper-blueviolet.svg"></a>
<a href="" ><img src="https://img.shields.io/badge/-Poster-ff69b7.svg"></a>
<a href="" ><img src="https://img.shields.io/badge/-Video-brightgreen.svg"></a>
<a href="" ><img src="https://img.shields.io/badge/-Supplementary-green.svg"></a>
<a href="" ><img src="https://img.shields.io/badge/-WeightsFiles-blue.svg"></a>
</p>

# Architecture

![archioverall](https://github.com/INDTLab/PATSP-Net/assets/85012818/23bbdff9-b351-4646-b0ff-8afa7333514a)


# Usage
### Installation:
1. Create the environment from the <kbd>environment.yml</kbd> file:

        conda env create -f environment.yml

2. Activate the new environment:

        conda activate bmvc

3. Verify that the new environment was installed correctly:

        conda env list

You can also use <kbd>conda info --envs</kbd>.

### Configuration:
1. Reset the correct path of the data sets in <kbd>dataer.py</kbd>.
2. Reset the model in <kbd>models.py</kbd> and init it in <kbd>main.py</kbd>.
3. Ensure all the hyparameters is what you need and then:

        python main.py

You can also use command like this:

    python main.py -c <cuda.id> -e <epoch> -b <batch_size> -d <dataset> -fp <save_dir> -nn <model_name> -lr <learning_rate>

# Results



# Citation

