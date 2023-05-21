# Artificial_Neural_Network
# My "X" will be my "df" from 4 columns to columns "EstimatedSalary" almoust last, because last column will be my "y", so column "Exited"
# Now I need to encode my labels, so I import "LabelEncoder" and put into my [:,2] columns from my new "df"
# And I use "fit_transform method" on them "X[:,2] = le.fit_transform(X[:,2])"
# Then I import "ColumnTransformer" and "OneHotEncoder" and I encode my columns "Geography column", so first I prepare my "fransformer" 
# I put into my "transformer" "OneHotEncoder", then will be my [1] variable, so "Geography"
# Then I use "ColumnTransformer" to transform my "X" and create arry using numpy, I save it all as new "X" "X = np.array(ct.fit_transform(X))"
# Now I can import "train_test_split" and get "train" and "test" set 
# Then I need to scale my values, so i put into my scaler "X_train, X_test"
# Now I can create my model "ann = tf.keras.models.Sequential()" 
# I put into two hidden layers with six neurons and activation "relu" and output layers with 1 neuron and activation "sigmoid"
# Then I comiple my model with classic optimizer "adam", loss "binary crossentropy", because i have binary output, and metrics will be solo "accuracy"
