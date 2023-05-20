# Artificial_Neural_Network
# My "X" will be my "df" from 4 columns to columns "EstimatedSalary" almoust last, because last column will be my "y", so column "Exited"
# Now I need to encode my labels, so I import "LabelEncoder" and put into my [:,2] columns from my new "df"
# And I use "fit_transform method" on them "X[:,2] = le.fit_transform(X[:,2])"
# Then I import "ColumnTransformer" and "OneHotEncoder" and I encode my columns "Geography column", so first I prepare my "fransformer" 
# I put into my "transformer" "OneHotEncoder", then will be my [1] variable, so "Geography"
# Then I use "ColumnTransformer" all "X" wariable 
