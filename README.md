# nerve-fibers-analysis
CellProfiler pipelines for determination and morphometric description of nerve fibers

Pipeline optimized to detect axon and myelin sheath from digital images. Pipeline was designed for semithin sections of rat sciatic nerve, stained with Toluidine Blue, scanned at 40x magnification. After artifacts removal, double CLAHE adjustment and 8-bit grayscale coversion was done. Such images are uploaded to CellProfiler. 
Axon detection sensitivity (vs 3 independent researchers who manually marked nerve fibers) - 80,4%, PPV - 68%
Area coverage vs manual - 91%, Myelin sheath coverage vs manual 92%
