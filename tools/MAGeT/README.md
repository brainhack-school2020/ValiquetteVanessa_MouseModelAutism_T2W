# Getting started 
## High performance computing and MAGeT

### Setting up 
1. Create a compute canada and get sponsored by your supervisor.
2. Since the CoBraLab mainly uses Niagara, I will use Niagara for further steps.

### MAGeT
1. Setup the module you will need to run MAGeT.
        
  >The CoBrA lab has its own set of software you can use through the same "modules" system. Here's how you can get access to it:        
  ```
  cp /project/m/mchakrav/bashrc-template ~/.bashrc 
  #You may get a warning that you are overwriting a file, this is okay and expected, select yes.
  source ~/.bashrc
  ln -s $SCRATCH ~/scratch
  ```
  >Now CoBrALab modules are available for your account on Niagara. Note that you only need to do the above steps once, after that you 
  should >have access to the modules immediately after logging in.

