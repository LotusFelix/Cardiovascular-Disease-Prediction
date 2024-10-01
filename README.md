# Cardiovascular-Disease-Prediction
This project expansively investigates the viability of machine learning models for cardiovascular disease prediction, focusing on developing low-cost, efficient diagnostic models. 

Using a robust dataset of over 53,000 instances, we evaluate a variety of models including Logistic Regression, Support Vector Machines, Random Forest, Gradient Boosting, Neural Networks, and Stacking Ensembles. 

## Data description

There are 3 types of input features:

Objective: factual information;

Examination: results of medical examination;

Subjective: information given by the patient.

### Features:

Age | Objective Feature | age | int (days)

Height | Objective Feature | height | int (cm) |

Weight | Objective Feature | weight | float (kg) |

Gender | Objective Feature | gender | categorical code |

Systolic blood pressure | Examination Feature | ap_hi | int |

Diastolic blood pressure | Examination Feature | ap_lo | int |

Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |

Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |

Smoking | Subjective Feature | smoke | binary |

Alcohol intake | Subjective Feature | alco | binary |

Physical activity | Subjective Feature | active | binary |

Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

All of the dataset values were collected at the moment of medical examination.

The goal is to optimize each model and compare their performance based on accuracy, precision, recall, and overall clinical viability. By implementing early stopping, hyperparameter tuning, and advanced evaluation metrics, this project seeks to identify the most reliable models for real-world medical applications. 

Savor!!!
