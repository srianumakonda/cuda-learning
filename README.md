# cs344 exercises + notes

Notes from Udacity's cs344: Intro to Parallel Programming course. Includes exercises and attmpted problem sets (along with a couple fun exercises that I'm doing).

note: to run a .cu file, make sure that you have your CUDA drivers configured and have CUDA (and CUDA Toolkit installed). Double check this by running 
```
nvidia-smi
nvcc --version
```

in your terminal. if you get the correct CUDA version and get a proper output, then that means you're ready to run cuda code!
``` 
nvcc fileName.cu (usually will default to a.out --> specify executable name by typing nvcc -o execName.out fileName.cu)
./a.out (or whatever your executable is named).
```
