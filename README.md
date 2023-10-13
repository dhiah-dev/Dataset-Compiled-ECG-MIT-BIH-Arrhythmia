# Dataset-Compiled-ECG-MIT-BIH-Arrhythmia
Compiled MIT-BIH Arrhythmia ready for researchers and programmers

The MIT-BIH Arrhythmia Database (https://www.physionet.org/content/mitdb/1.0.0/) contains 48 half-hour excerpts of two-channel ambulatory ECG recordings, obtained from 47 subjects studied by the BIH Arrhythmia Laboratory between 1975 and 1979. This dataset is completely raw data and not compiled as the researchers need to structure data and clean it from noise before any experiemnets. This fact has resulted in unfair evaluation as researchers may use different segments with different status and features.

Compiled MIT-BIH Arrhythmia dataset is extracted from MIT-BIH Arrhythmia Database. As the recording were digitized at 360 samples per second, 3600 samples are extracted for each segment to cover 10 sec per segment. Segments are extracted with the condition no overlaping of status which mean segments have one lable one class for all signal cycles. Recodes are distributed into five classes and each class with 100 records. Classes are described in the following

Classes of ECG Compiled MIT-BIH Arrhythmia dataset:
Class N: (Non-ectopic beats) and this class includes: Normal Beats, Left bundle branch block, Right bundle branch block, Nodal (junctional) escape beat and Atrial escape beat. 100 records are extracted

Class S: (Supraventricular ectopic beats) and this class includes: Aberrated atrial premature beat, Supraventricular premature beat, Atrial premature beat, and Nodal (junctional) premature beat. 100 records are extracted

Class V: (Ventricular ectopic beats) and this class includes: Ventricular escape beat and Premature ventricular contraction. 100 records are extracted

Class F: (Fusion beats) and this class includes: Fusion of ventricular and normal beat. 100 records are extracted

Class Q: (Unkown beats ) and this class includes: Paced beat, Unclassified beat and Fusion of paced and normal beats. 100 records are extracted

Data Format:
Data are structured in two easy computer readible formats 1- Data are formated in .CSV file with 500 records and 5 classes as described above in Table 1 each recod with 3600 sample (10 sec of ECG) and class symle is added to the end 2- Data are formated in .TXT files, each file contains one ECG record with 3600 samples (10 sec ECG). Text files are distributed into five directories with 100 text files in each Directories are named by the class symble in order to recognize the ECG records class
