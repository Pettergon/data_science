# data_science

import conda environment from environment.yml
`conda env create -f environment.yml`

export current env to environment.yml
`conda env export | grep -v \"^prefix: \" > environment.yml`
