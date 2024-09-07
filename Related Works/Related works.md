# Fault Detection / Diagnosis

# Anomaly detection


CWRU (Case Wester Reserve Univ.) bearing dataset 

Why DNN? 
- Higher performance than ML
- Intelligent system
- Expectation from the investors / market


Several surveys regarding the likelihood of induction machine failures conducted by the IEEE Industry Application Society (IEEE-IAS) [4]–[6] and the Japan Electrical Manufacturers’ Association (JEMA) [7] reveal that The associate editor coordinating the review of this manuscript and bearing fault is the most common fault type and is responsible for 30% to 40% of all the machine failures.

Sensing modalities that have been explored include vibration [9], [10], acoustic noise [11], [12], stator current [13], [14], thermal-imaging [15], and multiple sensor fusion [16], among which vibration analysis is the most dominant.

Frequency analysis has also been widely done - characteristic of fault frequencies 

fault frequency is directly proportional to the motor speed

there may exist many unique features or patterns hidden in the data themselves that can potentially reveal a bearing fault, and it is almost impossible for humans to identify these convoluted features through manual observation or interpretation.

Most of the literature applying these ML algorithms report satisfactory results with classification accuracy over 90%.

 technique may encounter many challenges that ultimately affect the classification accuracy.
1) Sliding: The fault frequency is based on the assumption
that no sliding occurs between the rolling element and
the bearing raceway, i.e., these rolling elements will
only roll on the raceway. Nevertheless, this is seldom
the case in reality, as the rolling element often undergoes a combination of rolling and sliding movement.
As a consequence, the calculated frequency may deviate from the real fault frequency and make this manually determined feature less informative of a bearing
defect.
2) Frequency Interplay: If multiple types of bearing faults
occur simultaneously, these faults will interact and the
resultant characteristic frequencies can add or subtract due to a complicated electro-mechanical process,
thereby obfuscating the informative frequencies.
External Vibration: There is also the possibility of
interference induced from additional sources of vibration, i.e. bearing looseness and environment vibration,
which can obscure the useful features.
4) Observability: Some faults, such as the bearing lubrication and general roughness related faults, do not
even manifest themselves as a characteristic cyclic frequency, which makes them very hard to detect with the
traditional model-based spectral analysis or classical
data-driven ML methods.
5) Sensitivity: The sensitivity of various features that are
characteristic of bearing defect may vary considerably
at different operating conditions. A very thorough and
systematic ‘‘learning stage’’ is typically required to test
the sensitivity of these frequencies on any desirable
operating condition before it can be actually put into
use with the traditional approach.

