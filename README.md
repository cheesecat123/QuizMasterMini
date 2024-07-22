# QuizMasterMini

This code is a smaller version of [QuizMaster](https://github.com/hermonochy/QuizMaster) for devices with less storage.

## How to Use

### Install
1. Clone this repository `git clone https://github.com/hermonochy/QuizMasterMini.git`
2. Set up a new virtual environment `python3 -m venv .`(This will take up about 60 mega bytes, but is recommended).
3. Start the environment.`source ./bin/activate`
4. Install packages in `requirements.txt`.`pip3 install -r requirements.txt`
5. Run either Quiz Creator or Quiz Game (see below).

### Quiz Creator

1. Run the script `./quizcreator` 
2. Use the Quiz Creator to manage and create quiz questions. Use the add button to add questions.
3. As it is multiple choice, you need to give a correct answer and wrong answers, seperating them with commas. Afterwards, save it. The format is json.

### Quiz Game

In a command line window, enter `./quiz`. Choose a json file and play. You can either press the number given to the answer or, if you don't have a keyboard, click on the answer. Remember, you only have 10 seconds! At the end it will tell you your score.



