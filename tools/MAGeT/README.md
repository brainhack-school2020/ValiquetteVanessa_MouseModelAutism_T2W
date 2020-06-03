# Getting started 
## Running MAGeT on a high performance computer

### Starting on compute canada
1. Create a compute canada and get sponsored by your supervisor.

2. Since the CoBraLab mainly uses Niagara, I will use Niagara for further steps.

3. Login and aim for bigger goals.... 

### Starting with MAGeT
1. [Get modules](https://github.com/CoBrALab/documentation/wiki/Getting-Started-on-Niagara) that you will need to run MAGeT on your compute canada env.
  
2. Read the [MAGeT documentation](https://github.com/CobraLab/documentation/wiki/MAGeTBrain)  
  2.1  Load modules  
  2.2  Clone MAGeT Brain pipeline to your directory  
  2.3  Create a directory structure that corresponds to the pipeline  
  2.4  Populate your directory with the corresponding files (atlas, mask, labels, brain files)        
  
Use [Globus](https://www.globus.org/) or rsync to transfer your data to your compute canada directory.      
      
```
rsync -avz /path/to/file username@niagara.computecanada.ca:/path/to/put/file (usually starts with scratch/...)
```  
    
There is atlases provided by the CoBrA Lab or you can find some other ones on the Allen brain Institue wiki.      
   * [Human Brain](https://github.com/cobralab/atlases)  
   * [Mouse Brain](https://wiki.mouseimaging.ca/display/MICePub/Mouse+Brain+Atlases)  
    
3. Do a first check run, to make sure everything is setup right  
```
mb check
```
4. Run MAGet for the first time and hope for the best. :pray:
```
mb run
```



