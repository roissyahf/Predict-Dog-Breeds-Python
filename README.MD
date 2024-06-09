# Identify Dog Breeds with Python

In this project, I was given a task to create image classifier to identify dog breeds. In this case, I focus on Python not on the actual classifier. Big task will be divided into smaller chucks, included:
1. Identify which pet images are of dogs correctly (even if the breed is misclassified) and which pet images aren't of dogs.  
2. Classify the breed of dog correctly, for the images that are of dogs.  
3. Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve objectives 1 and 2.  
4. Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms takes to run.

File explanation:
* `check_images.py` used to achieve the four objectives above.
* `get_input_args.py` used to write user-friendly command-line interfaces.
* `get_pet_labels.py` used to create the labels for the pet images, using the filenames of the pet images in the pet_images folder. The written function will return results dictionary that will contain the pet image filenames and labels.
* `classify_images.py` contains a function to create the classifier labels and then compares the classifier labels to the pet image labels.
* `classifier.py` will classify your images using CNNs.
* `test_classifier.py` it demonstrates how to use the classifier function, to test the environment.
* `adjust_results4_isadog.py` will result a dictionary of lists, with the pet image filename as the key and the value will be a list for all 40 pet images in the pet_image folder.
* `calculates_results_stats.py` will result the statistics dictionary, statistic's name as the key and the value will simply be the statistic's numeric value.
* `print_results.py` will be inputting the results dictionary and the results statistics dictionary to print a summary of the results.

**Note**

This project was part of UDACITY: AI Programming with Python Course, pushed to personal repository in purpose of showing ability in creating function. 
