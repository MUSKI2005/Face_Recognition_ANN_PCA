# Face_Recognition_ANN_PCA
## Importing all liberaries
<!-- os,numpy,matplotlib etc -->
<!-- using the helper function -->
**Using the function plot_gallery**
*plots a gallery of portraits*

<!-- plt.figure -->
<!-- Adjusting the subplots -->
<!-- showing images -->
<!-- giving titles in ANN model -->
*x ticks*
*plotting y ticks*

<!-- giving directory name -->
<!-- h=w=300 #image dimensions -->

*y=[] #labels*
*x are the features*
**target names are the class names**
<!-- person_id=0 -->

*running a loop for finding person id in directory*
<!--dir_path = os.path.join(dir_name, person_name)  -->
**inside the outer loop running inner loop for joining the directory path**
<!-- giving image path in directory -->
*reading the images*
<!-- converting the images into gray scale for reducing dimensions-->
<!-- resizing the iamges -->
<!-- appending in X after flattening the images -->
<!-- append y for person id -->

<!-- target names appending -->
<!-- incrementing person id by 1 -->

*X=np.array(X)*
*y=np.array(y)*
<!-- target_names=np.array(target_names) -->

<!-- printing the dataset size ,labels,classes ,shape -->

<!--  splitting the data into training and testing sets -->
<!-- x train, y train etc. splitting the dataset -->

<!-- normalize the data for ANN -->
<!-- X_train=X_train/255.0 -->
<!-- X_test=X_test/255.0 -->

<!-- one-hot encode the labels -->
<!-- y_train_onehot=to_categorical(y_train) -->
<!-- y_test_onehot=to_categorical(y_test) -->

<!-- from tensorflow.keras.models import Sequential #type: ignore -->




