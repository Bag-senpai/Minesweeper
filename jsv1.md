//initialize the board
//gather needed elements
const minesweeperArea = document.getElementById("minesweeperArea")

const printArea = (board) => {
  for(let i = 0; i < 100; i++){
    minesweeperArea.innerHTML = minesweeperArea.innerHTML + `<div class = 'square' id = 'square${i + 1}'></div>`;
  }
  for (let i = 100; i < 110; i++){
    minesweeperArea.innerHTML = minesweeperArea.innerHTML + `<div class = 'squareinvi' id = 'square${i + 1}'>X</div>`;
  }
}
  
// initialize new game
const newGame = () => {
  let square = -1;
  let board = new Array(100).fill(0);
  minesweeperArea.innerHTML = "";
  printArea(board);
}

newGame();
