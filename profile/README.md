# Welcome to interactive-sonification

This is our github organization offering tools for sonification and audio coding. 

- Our packages (sc3nb, pya, pyamapping, mesonic, sonecules) are made available on PyPI, so that they can be installed by pip install package_name. 

- At the moment (September 2023), pya depends on pyaudio/portaudio which may cause installation problems via pip on some systems. Futher details can be found on https://interactive-sonification.github.io/pya/v0.5.1/#installation. Future pya releases will have pyaudio as optional dependency.

- For convenience we offer the [ison conda environment](https://raw.githubusercontent.com/interactive-sonification/.github/main/ison-conda.yml) for our sonification tool chain which should just work. To install all packages on your system, please download the ison-conda.yml linked above
- and in your shell do `conda env create -n ison --file ison-conda.yml`
- alternatively, to augment your personal conda environment 'myenv' do
    `conda env update --name myenv --file ison-conda.yml --prune`
  
