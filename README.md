# BachelorThesis_seizure_detecion_device
This is a 1:1 copy of the virtual environment created for the seizure detection device as part of Bachelor Thesis. The following contents of the virtual environment are customary to this artifact: 

<ul>
  <li><h5>Epilepsy Dataset:</h5>Original data set by Villar et al. sampled at the University Oviedo (Villar et al., 2016; Villar, n.d.-a).</li>
  <li><h5>imu.py</h5>Main module that includes the classification algorithm. It is also executed as a service on the SDD.</li>
  <li><h5>preprocessing.py</h5>Module to preprocess the data set by Villar et al. </li>
  <li><h5>sampling.py</h5>Module to sample and integrate new data in the data set. </li>
  <li><h5>TimeSeries_DataFrame.csv</h5> CSV file of the processed data set.</li>
  <li><h5>ConfusionMatrix.png</h5> The in imu.py computed confusion matrix.</li>
</ul>
Note: Citation.cff served the purpose of citing the repository in the thesis and is not part of the virtual environment!
<h3>References</h3>
Villar, J. R. (n.d.-a). Dataset: Epilepsy. Time Series Classification. [Data set]. https://www.timeseriesclassification.com/description.php?Dataset=Epilepsy <br>
Villar, J. R., Vergara, P., Menéndez, M., de la Cal, E., González, V. M., & Sedano, J. (2016). Generalized Models for the Classification of Abnormal Movements in Daily Life and its Applicability to Epilepsy Convulsion Recognition. Scopus. https://doi.org/10.1142/S0129065716500374
