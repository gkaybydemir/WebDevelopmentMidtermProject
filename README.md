# WebDevelopmentMidtermProject
Midterm Project
![midterm_project_photo](https://github.com/gkaybydemir/WebDevelopmentMidtermProject/assets/109183248/3b4f7d1b-b974-4500-9584-bdbd3959165d)

## Midterm Project

## Explanation
This project contains a simple HTML and CSS file and looks like a homepage for a bank.

## Use
- Download or copy files.
- Open the HTML file in your browser or review/edit it by opening it with a text editor.

## Structure
- `index.html`: Basic HTML structure
- `index.css`: Basic CSS styles

## Example

	************(HTML)These are navbar codes for my project************
     <nav>
        <div id="flex-container_navbar">
        </div>

        <div class="elements_nav_left">
          
            <a href="#" class="home">Home</a>
            <a href="#" class="about">About</a>
            <a href="#" class="cards">Cards</a>
            <a href="#" class="loan">Loan</a>
            <a href="#" class="deposit">Deposit</a>
            
        </div>
        <div class="elements_nav_right">
            <a href="#">Settings</a>
            <a href="#">Quit</a>
           
        </div>
        
        
    </nav>

	************(CSS) These are navbar codes for my project************
	nav{
    display: flex;
    flex-direction: row;   
    height: 3.125rem;
    background-color: #090606;
    
}
/* Home About Cards Loan Deposit */
nav .elements_nav_left{
    padding: 0.625em;
    display: flex;
    justify-content: space-around;
    width: 60%;
        
}
nav .elements_nav_left  a{
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 15px;
    width: 5rem;
    border: 2px solid #FAA305;
    border-radius: 1rem; 
    background-color: #FAA305;
    color: white;
    text-decoration: none;    
}
.elements_nav_left a:hover{
    transition: 1s;
    background-color: black;
    color: #FAA305;
}
/* Settings Quit */
.elements_nav_right{
    margin-left: 60rem;
    padding: 10px;
    display: flex;
    justify-content: space-around;
    flex-direction: row;
    width: 35%;    
}
.elements_nav_right a{
    display:flex;
    align-items: center;
    justify-content: center;
    width: 5rem;
    padding: 15px;
    border: 2px solid #FAA305;
    border-radius: 1rem;
    background-color: #FAA305;
    color: white;
    text-decoration: none;
}
.elements_nav_right a:hover{
    transition: 1s;
    background-color: black;
    color: #FAA305;
}


## Dependencies
- GoogleChrome


## Communication
For your questions or feedback
email: gokaybaydemir@posta.mu.edu.tr
