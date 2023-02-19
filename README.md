# HAXIOS_Asclepius
### This project focuses on Implementation of **Edge AI for Healthcare**.
#### The problem statement we are working on focusues on helping elders in critical time. The developed ML model can be deployed in any development boards (like STM , Arduino etc ) and also Mobile phone for live classification. If the person using our developed device feels sick, just by saying HELP, which the model detects and if the threshold is greater than certain value, will alert a user.

As of now for this project, we have developed a complete ML model and deployed it in arduino nano 33 BLE and Mobile phone. (Link to video given in repo).

>*)Edge Impulse platform is used for data acquisition from arduino nano 33 BLE.<br />
>*)The model is trained on ~100 dataset with two labels - **Noise and Help** to help discard random noise.<br />
>*)MFCC and MFC classifiers are used in processing the audio data and Keras is used for classification.
