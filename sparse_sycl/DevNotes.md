# Issues  
-  No `cusparse` equivalent calls work yet which affects to all routines in the following files:
+ `zmergecg.dp.cpp`
+ `magma_trisolve.cpp`
+ `magma_zcuspmm.cpp`
+ `magma_zcuspaxpy.cpp`
+ `magma_zmatrixtools_gpu.dp.cpp`


- For now, all `tex1Dfetch` `tex2Dfetch` ... do not work, a temp solution (for compilation) is commenting out all calls to those functions, thus `zmgesellcmmv` does not work.
