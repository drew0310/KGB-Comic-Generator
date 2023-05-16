# KGBCU (KGB COMIC UNIVERSE)
# Comic Generation Application - A team project by me, [jeevesh2002](https://github.com/jeevesh2002) and [bhuvnesh1871](https://github.com/bhuvnesh1871).  


## Introduction
An application designed to help users create their own comic image stories. Takes in the premise of the plot and a set of plot keywords from the user, generates a prompt for GPT-3 to write a random textual outline of the story using the given keywords, and generates comic illustrations from the text using DALL-E 2. Consists of Python back-end APIs connecting to the OpenAI APIs and a front-end website for user interaction.  




## How it Works
1. User inputs keywords related to the comic they want to generate.
2. The platform performs a quantum random walk ([Bose Hubbard Model](https://en.wikipedia.org/wiki/Bose%E2%80%93Hubbard_model)) on the given input.  
3. A unique comic is generated and displayed to the user.  

## Steps to Run the Application
1. Download the application as a zip file and extract it to the desired target folder.  
2. Make sure you have everything specified in requirements.txt installed in your system. If not, type "pip install -r requirements.txt" in your terminal or command prompt.    3. In the terminal or command prompt, move to the application folder and type "flask run". The application will start running on port 5000 in the local computer.  
4. Type the username as user1 and password as pass1 to login.  
5. Generate your comic by providing input keywords and comic image style description (set number of qubits to 12 and type as Ideal). The generated storyline text will be appended to responses.txt in the results folder, and the generated comic images will be stored in PNG format in the same folder.
