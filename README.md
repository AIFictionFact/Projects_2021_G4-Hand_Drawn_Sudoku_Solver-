# Projects_2021_G4-Hand_Drawn_Sudoku_Solver-
Group 4 -- Aiden Sullivan , Sam Avis, Jimmy Schaffer, Dolan Clahan, Spencer Webb

Our group takes the AICrowd challenge as described here ==> https://www.aicrowd.com/challenges/ai-for-good-ai-blitz-3/problems/sudoku

This project is about using computer vision as learned in lab 2 of this course to read and solve a generic hand-written sudoku puzzle.
Our goal was to use the provided 10001 sudoku images to train and validate a Neural Network to recognize numbers as they come in the puzzles, and use the "read" puzzles 
to input into a sudoku solving algorithm.

Resources used:
\n-- Pre-made sudoku solver, downloaded in py/ipynb file using ==> !pip3 install py-sudoku
\n-- Testing and training data downloaded from this page ==> https://www.aicrowd.com/challenges/ai-for-good-ai-blitz-3/problems/sudoku/dataset_files
\n-- MNIST dataset to train NN using strategies from lab 2 to recognize hand-drawn digits
     
HOW TO RUN THE PROJECT:
1   Go to these shared google drive links and create shortcuts in your drive ("/content/drive/My Drive/<file>") to access these folders of the test/train sample datasets 
            sample_test: https://drive.google.com/drive/folders/1WqU0jS_kkHLUy1CDgp0EpLcOqaykfspS?usp=sharing
            sample_train: https://drive.google.com/drive/folders/1kR32hRSEDyhMIWK3gsvmwGoyFv7DLOMq?usp=sharing
            demo_test: https://drive.google.com/drive/folders/1oteMYFSnwMYx2fMlnOvvX2WuyBqbcuF0?usp=sharing 
    OR
    download testing and training data from the page ==> https://www.aicrowd.com/challenges/ai-for-good-ai-blitz-3/problems/sudoku/dataset_files
    and add data to personal google drive folders sample_test, sample_train and demo_test
2   download \*.ipynb file from this github repo and run, training the model on MNIST dataset will take ~10 minutes
