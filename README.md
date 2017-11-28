# Correlation filter tracking based on Adaptive Learning rate and Location Refiner(ALLR)
This is the matlab code of ALLR. The implementation is built upon the code of [1]. The codes provided by [2,3,4,5] are also used in the implementation. 


#Instructions:
* 1) Modify the base_path in "run_tracker.m" with your own setting.
* 2) Run the "run_tracker.m" script in MATLAB.
* 3) Choose sequence.
* 4) Use the "run_ALLR.m" script in the Object Tracking Benchmark[6].


#Contact:
Jianwei Guo,
201532103023@stu.hebut.edu.cn



#Reference
[1] Yang Li, Jianke Zhu. 
	"A Scale Adaptive Kernel Correlation Filter Tracker with Feature Integration" 
	European Conference on Computer Vision, Workshop VOT2014 (ECCVW), 2014

[2] J. F. Henriques, R. Caseiro, P. Martins, J. Batista.
    "High-Speed Tracking with Kernelized Correlation Filters."
    TPAMI - IEEE Transactions on Pattern Analysis and Machine Intelligence, 2015

[3] Martin Danelljan, Fahad Shahbaz Khan, Michael Felsberg and Joost van de Weijer.
    "Adaptive Color Attributes for Real-Time Visual Tracking".
    Proceedings of IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2014.

[4] J. van de Weijer, C. Schmid, J. J. Verbeek, and D. Larlus.
    "Learning color names for real-world applications."
    TIP, 18(7):1512–1524, 2009.

[5] David Ross, Jongwoo Lim, Ruei-Sung Lin, Ming-Hsuan Yang. 
	"Incremental Learning for Robust Visual Tracking"
	In the International Journal of Computer Vision, Special Issue: Learning for Vision, 2007.

[6] Wu Y, Lim J, Yang M H. 
    Object Tracking Benchmark[J]. 
    IEEE Transactions on Pattern Analysis & Machine Intelligence, 2015, 37(9):1834-48.
