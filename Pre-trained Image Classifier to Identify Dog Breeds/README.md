
# Expected Outcome

When the code is completed and executed, it will print a summary of the results that can be used to answer objectives 1 and 2 of the project. The printed output will include:

- The CNN model architecture is being used.
- The overall count of images, dog images, and "not-a" dog images
- Various statistics related to the correctness of the classifications, such as the percentage of correct dogs, correct breeds, and "not-a" dog images,
Additionally, if requested, the code can also print the misclassifications of dogs and breeds.

# Checking Your Code
To visually check the correctness of the code, you can run the program and verify the following:

- The program should correctly calculate and print the statistics and counts.
- The results obtained from the code check for calculating results should match the values printed for those six statistics.
- If the two default arguments for printing misclassifications are not provided, no misclassifications should be printed.
- If the two default arguments for printing misclassifications are set to true, the misclassifications should be printed.

# Final Program Run
Once you are satisfied that the program is running properly, you can perform a final program run using batch processing. This allows you to run the program for all three CNN model architectures and compare the results with the provided final results.

To run the program using batch processing, follow these steps:

- Open a terminal window.
- Navigate to the directory where the code is located.
- Run the bash program run_models_batch.sh using the following command:
    sh run_models_batch.sh

This will execute the program for all three models and store the results in separate text files for comparison.
The command is run_models_batch_uploaded. sh can also be used to run the program using the images inside the "uploaded_images" folder.
