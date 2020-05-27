## Wuhan Corona (COVID-19) patients dataset 

We introduce a small new dataset related to the latest family of coronavirus i.e. COVID-19. Such datasets play an important role in the domain of artificial intelligence for clinical medicine related applications. This data set contains the Computed Tomography scan (CT) slices for 89 subjects. Out of these 89 subjects, 68 were confirmed patients (positive cases) of the COVID-19 virus, and the rest 21 were found to be negative cases. The proposed dataset  “CC-19” contains 34,006 CT scan slices (images) belonging to 98 subjects out of which 28,395 CT scan slices belong to positive COVID patients. This dataset is made publically. First figure shows some 2D slices taken from CT scans of CC-19 dataset. Moreover, some selected 3D samples from the dataset are shown in Figure. The Hounsfield unit (HU) is the measurement of CT scans radiodensity as shown in Table. Usually, CT scanning devices are carefully calibrated to measure the HU units. This unit can be employed to extract the relevant information in CT Scan slices. The CT scan slices have cylindrical scanning bounds. For unknown reasons, the pixel information that lies outside this cylindrical bound was automatically discarded by the CT scanner system. But fortunately, this discarding of outer pixels eliminates some steps for preprocessing.


Collecting  dataset is a challenging task as there are many ethical and privacy concerns observed the hospitals and medical practitioners. Keeping in view these norms, this dataset was collected in the earlier days of the epidemic form various hospitals in Chengdu, the capital city of Sichuan. Initially,  the dataset was in an extremely raw form. We preprocessed the data and found many discrepancies with most of the collected CT scans. Finally, the CT scans, with discrepancies, were discarded from the proposed dataset. All the CT scans are different from each other i.e. CT scans have a different number of slices for different patients. We believe that the possible reasons behind the altering number of slices are the difference in height and body structure of the patients. Moreover, upon inspecting various literature, we found that the volume of the lungs of an adult female is, comparatively, ten to twelve percent smaller than a male of the same height and age.