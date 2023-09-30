# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Neutral

- Almost White: hsl(0, 0%, 98%)
- Medium Gray: hsl(0, 0%, 41%)
- Almost Black: hsl(0, 0%, 8%)

## Typography

### Body Copy

- Font size (paragraph): 18px

### Font

- Family: [Epilogue](https://fonts.google.com/specimen/Epilogue)
- Weights: 500, 700


.box {
  display: grid;
  max-width: fit-content ;
  margin-top: 70px;
}

.transparent {
  border: none;
  background-color: white;
  color: var(--Medium-Gray);
  font-size: 13px;
  max-width: fit-content;
  padding: 12px;
}

.transparent:hover {
  color: var(--Almost-Black);
  
}

.filled-btn {
  border-radius: 13px;
  max-width: fit-content;
  padding: 10px 15px;
  font-size: 13px;
}





nav>
    <div class="nav-case">
      <div class="nav-left">
        <div class="nav-logo">
          <img src="images/logo.svg" alt="Company-logo">
        </div>
          <ul class="nav-links">
            <li>
              Features
              <img class="arrow" src="images/icon-arrow-down.svg" alt="arrow-down">
              <div class="drop-menu one">
                <p class="sub-menu"><img src="images/icon-todo.svg" alt="notepad">Todo List</p>    
                <p class="sub-menu"><img src="images/icon-calendar.svg" alt="calendar">Calendar</p>
                <p class="sub-menu"><img src="images/icon-reminders.svg" alt="">Reminders</p>
                <p class="sub-menu"><img src="images/icon-planning.svg" alt="planning">Planning</p>  
              </div>
            </li>
            <li>
              Company
              <img class="arrow" src="images/icon-arrow-down.svg" alt="arrow-down">
              <div class="drop-menu two">
                <p>History</p>
                <p>Our Team</p>
                <p>Blog</p>
              </div>
            </li>
            <li>Careers</li>
            <li>About</li>
        </ul>
      </div>
      <div class="mobile-hamburger">
        <img src="images/icon-menu.svg" alt="menu">
      </div>
      <div class="mobile-drop">
        <ul class="mobile-links">
          <li>
            <p>
              Features 
              <img src="images/icon-arrow-down.svg" alt="arrow-down">
            </p>
            <div class="drop-it">
              <p class="sub-menu"><img src="images/icon-todo.svg" alt="notepad">Todo List</p>    
              <p class="sub-menu"><img src="images/icon-calendar.svg" alt="calendar">Calendar</p>
              <p class="sub-menu"><img src="images/icon-reminders.svg" alt="">Reminders</p>
              <p class="sub-menu"><img src="images/icon-planning.svg" alt="planning">Planning</p>  
            </div>
          </li>
          <li>
            <p>
              Company 
              <img src="images/icon-arrow-down.svg" alt="arrow-down">
            </p>
            <div class="drop-it">
              <p class="sub-menu"><img src="images/icon-todo.svg" alt="notepad">Todo List</p>    
              <p class="sub-menu"><img src="images/icon-calendar.svg" alt="calendar">Calendar</p>
              <p class="sub-menu"><img src="images/icon-reminders.svg" alt="">Reminders</p>
              <p class="sub-menu"><img src="images/icon-planning.svg" alt="planning">Planning</p>  
            </div>
          </li>
          <li>Careers</li>
          <li>About</li>
        </ul>
      </div>
      <div class="nav-left">
        <button class="loginbtn">Login</button>
        <button class="registerbtn">Register</button>
      </div>
    </div>
  </nav>