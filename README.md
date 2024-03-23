body {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f0f0f0;
}

#game-container {
    position: relative;
}

canvas {
    border: 1px solid #000;
    background-color: #fff;
}

#score {
    position: absolute;
    top: 10px;
    left: 10px;
    font-size: 20px;
}

#gameOver {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 40px;
    display: none;
}

#restartButton {
    position: absolute;
    top: 60%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 20px;
    display: none;
}
