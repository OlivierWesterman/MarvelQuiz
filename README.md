# MarvelQuiz
## Description
This app was made to find trivia questions about Marvel from this API: https://the-trivia-api.com/.
During play, you will be asked 10 questions which you can answer by simply clicking on the correct answer.
After 10 questions the game will display the score of the player in the Highscore Window.

To that end this App has some large seperate parts:
- Two class libraries (QuestionsLibrary and ScoreboardLibrary) containing the Question, Answer, PlayerScore and Scoreboard classes.
- A console application to demonstrate the basic usage of the QuestionsLibrary.
- A graphical WPF application to allow the user to do a Marvel quiz. 

## Author
This App was made by Olivier Westerman while studying at Vives Brugge in Spring 2024.

## Screenshots
### Console Demo App
![ConsoleDemoSelection](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/4f1ad93a-d12f-4ff2-85d0-035261ec8914)
![ConsoleDemoOriginalFractions](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/eb3ae74b-fd02-48b9-8772-b9d02f66db7e)

![ConsoleDemoOriginalFractionsSolutions](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/ee3107a6-7a97-4944-a286-f8e8e04c2930)
![ConsoleDemoRandomFractionsSolutions](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/b2b5715c-7b84-42b4-bc91-abf668fa771e)

### Unit Tests
![UnitTests](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/2663e098-998e-442c-a8f6-f155a96ac2f3)

### WPF Application
![StartupWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/33808c5b-f9b6-4ea2-9ee2-a167fb5c0342)
![StartTabWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/cae196f6-9eb0-4e96-a9a7-2c83a44928f2)
![OperatorsTabEmptyWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/6557e233-3df3-4547-b948-90991e5f4ea5)
![OperatorsTabActionWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/2a06b241-5889-4b2c-b54d-0ecb27a8a5fa)
![ManipulatorsTabEmptyWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/a80971fd-360c-421c-81e4-fa62e719df91)
![ManipulatorsTabActionWPF](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/0e59df37-d673-4b40-9347-3b1ccc67c376)

## Setup
To set up and use the App effectively, you'll need to make sure you have Microsoft Visual Studio installed as well as install or update the NuGet packages from Newtonsoft.Json (version 13.0.3 or higher).
It is also important to make sure you are working in a .NET 6 or higher environment.
You can find a step-by-step guide for installing these packages here:
- Visual Studio Community edition by following this [link](https://learn.microsoft.com/en-us/visualstudio/install/install-visual-studio?view=vs-2022).
- Newtonsoft.Json by following this [link](https://www.nuget.org/packages/Newtonsoft.Json/).
- .Net by following this [link](https://dotnet.microsoft.com/en-us/download/dotnet-framework).

Once everything is installed, open the project solution named 'MarvelQuiz.sln'. Then, build the solution to ensure all dependencies are resolved. 
At the top of your window, select which project you want to run with the dropdown and the click on the play button next to it to run.
![RunningProgram](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/74dbbb2b-fbe2-4001-870e-06ce6338deac)

## UML diagram
The following is the UML diagram for the Library as well as the other projects that it connects to.\
The UML of the Fraction class would only be the blue class.
![UML diagram](https://github.com/OlivierWesterman/FractionCalculator/assets/145467433/0ee281cc-5494-4e63-a24e-7e36ec2fb8fb)

This [link](https://lucid.app/lucidchart/719c3ac3-6d12-45f4-9c02-9b0dc1dd661d/edit?viewport_loc=-2167%2C-39%2C3216%2C1221%2CHWEp-vi-RSFO&invitationId=inv_b5f2439a-9d1e-47bd-999a-76f4c800788b) also leads to a diagram version that can be zoomed in on but you do need to sign in with a Lucid account for that.

## Future Improvements
- Left pictures out of the design because that was not a requirement, could add it later.
- I'm also sure there is a more powerful way to code the WPF-application by breaking the code into smaller methods.
- In term of variety, I could have made a few extra options and allow the player to choose what topic they would like to be quizzed on by manipulating the API GET link in TriviaApiLibrary.



