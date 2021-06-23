let humanScore = 0;
let computerScore = 0;
let currentRoundNumber = 1;

// Write your code below:

// Task 3: Generate Target

const generateTarget = () => {
  return Math.floor(Math.random() * 10);
};

// Calculate absolute distance

let humanGuess = 0;
let computerGuess = 0;
let targetNumbers = generateTarget();

const getAbsoluteDistance = (guess, target) =>
Math.floor(target - guess)

// Task 4: Compare Guesses  

const compareGuesses = (humanGuess, computerGuess, targetNumbers) => 
  getAbsoluteDistance(humanGuess, targetNumbers) <= getAbsoluteDistance(computerGuess, target) ? true : false;

// Task 5: Update Score 

let updateScore = (winner) => 
  winner === 'human' ?
   humanScore++ : computerScore++;
   
// Task 6: Advance Round   
      
let advanceRound = () => {
  return currentRoundNumber++;
};

