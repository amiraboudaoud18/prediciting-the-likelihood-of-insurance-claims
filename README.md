# Predictive Modeling for Insurance Claims on Imbalanced Data

## Description
This project aims to develop a predictive model that accurately identifies the likelihood of insurance claims using an imbalanced dataset. In the insurance industry, such predictions are vital for effective risk assessment and policy pricing. However, the inherent class imbalance—where non-claims significantly outnumber claims—can bias models towards the majority class, leading to poor performance in predicting actual claims.

## Dataset
The dataset contains various features that contribute to predicting insurance claims, including:
- **policy_id**: Unique identifier for the insurance policy.
- **subscription_length**: Duration of the policy.
- **customer_age**: Age of the policyholder.
- **vehicle_age**: Age of the insured vehicle.
- **model**: Vehicle model.
- **fuel_type**: Type of fuel used by the vehicle.
- **max_torque**, **max_power**: Engine performance characteristics.
- **engine_type**, **displacement**, **cylinder**: Specifications related to engine size and construction.
- **region_code**, **region_density**: Geographical region and population density of the policyholder.
- **airbags**, **is_esc**, **is_adjustable_steering**, **is_tpms**: Vehicle safety features.
- **is_parking_sensors**, **is_parking_camera**: Parking aids.
- **rear_brakes_type**, **steering_type**, **turning_radius**, **length**, **width**, **gross_weight**: Vehicle characteristics.
- **claim_status**: The target variable indicating whether a claim was made (1) or not (0).

## Conclusion
The model developed in this project effectively handles the class imbalance in the dataset and demonstrates good predictive performance on both the majority and minority classes, ensuring that insurers can better assess risk and allocate resources efficiently.
