## SIGN LANGUAGE TRANSLATION

#### Dataset Link : [https://www.kaggle.com/competitions/asl-signs/data](url)

ML_PROJECT_PHASE 1 : Transformer Model

lstm_asl : LSTM Model

dnn_model_with_hyperparameter_tuning : Ensemble Model

Real_Time_video_to_Parquet : Converts Video from your webcam in real time to parquet file using opencv
These parquet files can then be passed on to the respective model for predictions.

Best Model was Transformer with accuracy 77%
It used data augmentation, landmark and positional embedding, he_initializer, multihead attention, learning rate scheduler, dropout, weight decay callback to achieve that accuracy.

More details on pre-processing, hyperparameter tuning, etc. on all 3 models are included in the ML_PROJECT_REPORT which has also been uploaded in the repo.
