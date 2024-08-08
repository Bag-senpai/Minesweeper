* {
  font-family: Roboto, sans-serif;
}

#minesweeperArea {  
  display: grid;
  grid-template-columns: repeat(10, 30px);
  grid-template-rows: repeat(10, 30px);
  gap: 5px 5px;
  grid-auto-flow: row;
  justify-content: center;
}

.square {
  padding-top: 5px;
  text-align: center;
  border: 1px solid;
  border-radius: 5px;
  background: rgba(0,0,255,0.5);
  box-shadow: 5px -15px 15px rgba(255,255,255,0.5)
}

.squareinvi {
  background: #fff;
  box-shadow: 5px -15px 15px rgba(255,255,255,0.5);
  color: #fff;
}

.square:hover{
  background: rgba(100,100,255,0.5);
  cursor: pointer;
}

.container {
  display: flex-box;
  border-radius: 20px;
  border: 2px solid #c3c6ce;
  transition: 0.5s ease-out;
  height: 500px;
  width: 450px;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
}

h2 {
  text-align: center;
}

#minesLeft {
  margin-top: -10px;
}
