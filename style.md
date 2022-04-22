
*{
    box-sizing: border-box;
    margin: 0%;
    padding-left: 5px;
    padding-right: 5px;
    justify-content: inherit;
}

:root {
    --header: #79B5B8;
    --text_colour: #40405E;
    --blue: #7392FD;
  }

/* Navbar start  */
/* ========== */
li, a, button {
    font-family: "Fira Code";
    font-weight: 500;
    font-size: 20px;
    color: var(--text_colour);
    text-decoration: none;
}

.top-nav-container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px 10px;
}

.menu-list-container{
    list-style: none;
}
.menu-list-container li {
    display: inline-block;
    padding: 0px 20px;
    color: var(--text_colour);
}

.menu-list-container li a {
    transition: all 0.3s ease 0s;
}
button.login-navbar {
    padding: 9px 25px;
    background-color: transparent;
    border-style: double;
    border-color: var(--text_colour);
    color: var(--text_colour);
    border-radius: 05px;
    cursor: pointer;
    transition: all 0.3s ease 0s;
}
.login-navbar:hover{
    color: white;
    background-color: var(--blue);
}

button.signup-navbar {
    padding: 9px 25px;
    background-color: transparent;
    border-style: double;
    border-color: var(--text_colour);
    background-color: var(--blue);
    color: var(--text_colour);
    border-radius: 05px;
    cursor: pointer;
    transition: all 0.3s ease 0s;
}
.signup-navbar:hover{
    background-color: white;
    color: rgba(69, 69, 219, 0.908);
}

.navbar {
    position: sticky;
    padding-bottom: 50px;
}

/* ========= */
/* Navbar Ends */

/* Header__text begins */
/* ======== */
.header__text {
    text-align: center;
    font-family: 'poppins';
}
.h1{
    font-size: 64px;
    text-shadow: #40405E;
}
p{
    font-weight: 500;
}
span.col {
    color: var(--header);
}
.header__{
    display: flex;
    justify-content: space-between;
}
/* ======== */
/* Header___text ends */