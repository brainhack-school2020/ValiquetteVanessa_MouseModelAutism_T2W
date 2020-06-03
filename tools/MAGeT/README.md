# Getting started 
## High performance computing and MAGeT

### Setting up 
1. Create a compute canada and get sponsored by your supervisor.
2. Since the CoBraLab mainly uses Niagara, I will use Niagara for further steps.

### MAGeT cheat sheet
1. [Get a package of modules](https://github.com/CoBrALab/documentation/wiki/Getting-Started-on-Niagara) you will need to run MAGeT.
  
2. Read the [MAGeT documentation](https://github.com/CobraLab/documentation/wiki/MAGeTBrain)  
  2.1 Load modules 
  
  2.2 Clone MAGeT Brain to your directory  
  
  2.3 Create a directory structure that corresponds to the pipeline  
  
  2.4 Populate your directory with the corresponding files (atlas, mask, labels, brain files)        
  
    Use [Globus](https://www.globus.org/) or rsync to transfer your data to your compute canada directory      
    
    ```
    rsync -avz /path/to/file username@niagara.computecanada.ca:/path/to/put/file (usually starts with scratch/...)
    ```  
    
    2.4.2 There is atlases provided by the CoBrA Lab or you get some other ones from the Allen brain Institue.      
          [Human Brain](https://github.com/cobralab/atlases)  
          [Mouse Brain](https://wiki.mouseimaging.ca/display/MICePub/Mouse+Brain+Atlases)  
    
3. Do a first check run, to make sure everything is setup right  
```
mb check
```
4.

