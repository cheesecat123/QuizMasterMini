# QuizMasterMini

This code is a smaller version of [QuizMaster](https://github.com/hermonochy/QuizMaster) for devices with less storage.

## How to Use

### Install
1. Clone this repository `git clone https://github.com/hermonochy/QuizMasterMini.git`
2. Set up a new virtual environment `python3 -m venv .`(This will take up about 60 mega byte, but is recommended).
3. Start the environment.`source ./bin/activate`
4. Install packages in `requirements.txt`.`pip3 install -r requirements.txt`
5. Run either Quiz Creator or Quiz Game (see below).

### Quiz Creator

1. Run the script `./quizcreator` 
2. Use it to manage and create quiz questions.The add button you can add questions. As it is multiple choice, you need to give a correct awnser and wrong awnsers, seperating them with commas.Afterwards, save it. Format is json.

### Quiz Game

In a command line window, enter `./quiz`. Choose a json file and play.You can either press the number given to the awnser or, if you don't have a keyboard, click on the awnser. Remember, you only have 10 seconds! At the end it will tell you your score.



