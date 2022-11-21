# Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds
Udacity's AI Programming with python first project
Classify Uploaded Images
Classifying Uploaded Images

This section will help you test your program by classifying your own images.

Your check_images.py program should now successfully classify the 40 images from the pet_images folder. In this section, you will upload 4 images to the uploaded_images folder, then run the file run_models_batch_uploaded.sh to classify those 4 images.
Directions for Finding Images and Uploading Images

Below are directions for finding images and processing them so they can be classified by the check_images.py program.

    Process the images so that:
        Images are in jpeg format with extension jpg
        Images are approximately square in shape (their height and width are approximately the same numbers of pixels).
    Find the following 3 images (or take the following 3 pictures):
        Dog Image - named Dog_01.jpg. Make sure you know the breed of dog that the image is of.
        Pet or Animal Image that's not a dog - named Animal_Name_01.jpg , where Animal_Name is the name of the animal in the picture. This name is formatted such that if more than one word makes up the animal name those words are separated by an underbar ( _ ).
            For example:
                Image of a Black Bear is named Black_bear_01.jpg
                Image of a Frog is named Frog_01.jpg
        An image of something that's not an animal - named Object_Name_01.jpg, where Object_Name is the name of the object in the picture. This name is formatted such that if more than one word makes up the object name those words are separated by an underbar ( _ ).
            For example:
                Image of a Coffee Mug is named Coffee_mug_01.jpg
                Image of a Bucket is named Bucket_01.jpg
    Create a fourth Image of a Dog using Dog_01.jpg
        Using Dog_01.jpg image horizontally flip the image and name it Dog_02.jpg. This will mean that Dog_02.jpg is a mirror image of Dog_01.jpg. If you are having difficulty with the horizontal flip alteration of Dog_01.jpg, just rotate Dog_01.jpg image by 180 degrees so that Dog_02.jpg is an upside-down version of Dog_01.jpg.

Upload all four images to the uploaded_images folder within the Project Workspace - Uploaded

    Double click on the uploaded_images folder within the Project Workspace - Uploaded.
    Next, click on the white + symbol above />home>workspace>uploaded_images text
    Next, select Upload File from the dropdown menu
    Next, select one of the four files to upload to the uploaded_images folder and click on the Open button
    Repeat the same process to upload the rest of the four files to the uploaded_images folder
    To return to the workspace folder:
        Click on the white < symbol above />home>workspace>uploaded_images text

Directions for Running check_images.py using all 3 Model Architectures

Now that you have completed coding check_images.py, you are ready to run it on all 3 models to classify the four images in the uploaded_images folder. To do this you will be calling the following shell script that will output the following results files:

    resnet_uploaded-images.txt - that contains the results using CNN model architecture ResNet
    alexnet_uploaded-images.txt - that contains the results using CNN model architecture AlexNet
    vgg_uploaded-images.txt - that contains the results using CNN model architecture VGG

To run file run_models_batch_uploaded.sh in the workspace, open a terminal window within the Project Workspace - Uploaded Images and type the following, then hit enter:

sh run_models_batch_uploaded.sh

This will run check_images.py using all three model architectures to classify the four images in the uploaded_images folder outputting their results files into the workspace.
