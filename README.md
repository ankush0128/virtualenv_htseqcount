# virtualenv_htseqcount
Vrtual environment for htseqcount in home directory on computing clusters: 
install python packages in their HOME areas. 
The virtual environment which is a clean place for you to install the particular software that you need.
Follow these instructions and it will work for you:
> cd
> module purge
> module load python3/3.7.0
> python -m venv HTSeq # if not working then
> python3 -m venv HTSeq

> source HTSeq/bin/activate
> pip3 install --upgrade pip
> pip3 install HTSeq

When you are done using is you deactivate the virtual environment by typing this into the terminal:
deactivate
Whenever you need it again you activate it again from your HOME:
> source ~/HTSeq/bin/activate
Then HTSeq commands for read counts
