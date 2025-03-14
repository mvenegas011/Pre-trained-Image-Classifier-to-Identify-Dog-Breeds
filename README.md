# Pre-trained-Image-Classifier-to-Identify-Dog-Breeds
UDACITY PROJECT: Pre-trained Image Classifier to Identify Dog Breeds


1. Timing Code
- Criteria	Submission Requirements
- Implementing Time functions.
- Student calls the time functions before the start of main code and after the main logic has been finished.

2. Command Line arguments
- Criteria	Submission Requirements
- Question 1 Enable dir argument: adds command line argument for '--dir' uses default ='pet_images/'
- Question 2 Enable arch argument: adds command line argument for '--arch' default='vgg'
- Question 3 Enable dogfile argument: adds command line argument for '--dogfile' default='dognames.txt'

3. Pet Image Labels
- Criteria	Submission Requirements
- Dictionary returned is in the correct format: Dictionary key and label are in the correct format and retrieves 40 key-value pairs. e.g:- {'Poodle_07956.jpg': ['poodle'], 'fox_squirrel_01.jpg': ['fox squirrel'] ... }
- Correct Function Call: 'in_arg.dir' is passed as an argument inside check_images.py while calling the get_pet_labels function.

4. Classifying Images
- Criteria	Submission Requirements
- Correct Function Call: Appends images_dir to each value before making the function call. classifier(images_dir+users_key, model)
- Output Formatting: Convert the output to lower case and strip any whitespaces
- Verifies and stores results in appropriate way. Displays output when the function call is made: Appends 1 to correct label, and 0 to falsely classified values

5. Classifying Labels as Dogs
- Criteria	Submission Requirements
- Matches between Classifier and Pet Image Labels have both labels classified as "dogs" or "not dogs" as appropriate for the labels.: Check the displayed output and see if all matches are appropriately displayed.
- Non-matches between Classifier and Pet Image Labels correctly classify each label as "dogs" or "not dogs": Check the displayed output and see if all non matches are appropriately displayed