# stackblitz-starters-fund

[Edit in StackBlitz next generation editor ⚡️](https://stackblitz.com/~/github.com/yusra25cyber/stackblitz-starters-fund)


# login-Fund
Login app i learned in fundamentals 

function login () {

  const userNameInput = document.getElementById('username');
  //username being declared in index.html
  const passwordInput = document.getElementById('password');
  //password being declared in index.html
  const result = document.getElementById('result')
  //result being declared in index.html 
  // [the code above stores the information given by the user]
  
const isCorrectUsername = userNameInput.value === 'yusra'
const isCorrectPassword = passwordInput.value === 'password'
// declares "correct" username and password 

  if (isCorrectUsername && isCorrectPassword ) {
    result.innerHTML = 'welcome yusra!';
  } else if (isCorrectPassword) {
    result.innerHTML = 'wrong password';
  } else {
    result.innerHTML = 'incorrect username or password'
  }
}
