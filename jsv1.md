//initialize the board
//gather needed elements
const minesweeperArea = document.getElementById("minesweeperArea")

const printArea = (board) => {
  for(let i = 0; i < 100; i++){
    minesweeperArea.innerHTML = minesweeperArea.innerHTML + `<div class = 'square' id = 'square${i + 1}'>O</div>`;
  }
}

printArea();
