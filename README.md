# EasyInputs
This API was not made by me it was made by @KinexDev.


Here is KinexDev GitHub: https://github.com/KinexDev


It was made from someone who deleted his repository and im simply just uploading it again!


To import the package to **Unity**, simply download it from github and then import it into Unity.


To use the API you have to do this:

    using easyInputs;

An example for use of the **EasyInputs API**:

    if(EasyInputs.GetTriggerButtonDown(EasyHand.RightHand))


## Examples


Get's If The **Grip Button** Is **Down**.

    EasyInputs.GetGripButtonDown(EasyHand easyHand);
Get's If The **Primary Button** Is **Down**.

    EasyInputs.GetTriggerButtonDown(EasyHand easyHand);
Get's If The **Primary Button** Is **Down**. Example. **A** & **X** Button On Quest

    EasyInputs.GetPrimaryButtonDown(EasyHand easyHand);
Get's If The **Primary Button** Is **Touched**. Example. **A** & **X** Button On Quest

    EasyInputs.GetPrimaryButtonTouched(EasyHand easyHand);
Get's If The **Secondary Button** Is **Down**. Example. **B** & **Y** Button On Quest

    EasyInputs.GetSecondaryButtonDown(EasyHand easyHand);
Get's If The **Secondary Button** Is **Touched**. Example. **B** & **Y** Button On Quest

    EasyInputs.GetSecondaryButtonTouched(EasyHand easyHand);
