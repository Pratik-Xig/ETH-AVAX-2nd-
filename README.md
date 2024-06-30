# Starter Next/Hardhat Project

After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

/* HomePage.css */
.container {
  text-align: center;
  margin-top: 50px;
}

.header {
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 20px;
}

.account-info {
  margin-bottom: 20px;
}

.balance {
  font-size: 20px;
  margin-bottom: 10px;
}

.buttons {
  margin-top: 20px;
}

.buttons button {
  margin-right: 10px;
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
  background-color: #007bff;
  color: #fff;
  border: none;
  border-radius: 4px;
}

.buttons button:hover {
  background-color: #0056b3;
}
