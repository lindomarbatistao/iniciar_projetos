=>Português

Para rodar o código

- Entre no repositório desejado
- Vá no botão verde (Code) e copie o endereço do repositório (duas folhinhas)
- Crie uma pasta no seu computador
- Acesse essa pasta
Exemplo: 
C:\Users\SeuCPF\Desktop\temp>

- Dê um git clone:
Exemplo: 
C:\Users\SeuCPF\Desktop\temp>git clone https://github.com/lindomarbatistao/2DS13.git

- Entre na pasta:
C:\Users\SeuCPF\Desktop\temp>cd 2DS13
C:\Users\SeuCPF\Desktop\temp\2DS13>

$$$$$$ BACKEND $$$$$$$$$$$$$$$$$$$$$$$$$$$$
- Entre na pasta back:
C:\Users\SeuCPF\Desktop\temp\2DS13>cd back
C:\Users\SeuCPF\Desktop\temp\2DS13\back>

- Teste o comando "py" se não funcionar tente "python", se não funcionar também siga:
############ Caso não funcione o python ou py ##########################################################
1- dê o comando "where python", se existir o Python instalado ele irá mostrar o caminho, dai basta coloca-lo nas variáveis de ambiente que ele funciona.
2- Caso não exista, baixe e instale o python, observe o caminho em que ele instala e coloque-o nas variáveis de ambiente.
3- Lembre-se que qualquer alteração no Sistema Operacional, deve-se desconsiderar os prompts e abrir novos.
########################################################################################################

- Atualize o pip:
C:\Users\SeuCPF\Desktop\temp\2DS13\back>python.exe -m pip install --upgrade pip

- Crie o ambiente virtual:
C:\Users\SeuCPF\Desktop\temp\2DS13\back>py -m venv env

- Ative esse ambiente:
C:\Users\SeuCPF\Desktop\temp\2DS13\back>env\Scripts\Activate
(env) C:\Users\SeuCPF\Desktop\temp\2DS13\back>

- Instale todos os pacotes necessários:
(env) C:\Users\SeuCPF\Desktop\temp\2DS13\back>pip install -r requirements.txt

- Inicie o servidor:
(env) C:\Users\SeuCPF\Desktop\temp\2DS13\back>py manage.py runserver

- Resultado:
	Watching for file changes with StatReloader
	Performing system checks...

	System check identified no issues (0 silenced).
	March 25, 2025 - 20:43:13
	Django version 5.1.5, using settings 'cadastro.settings'
	Starting development server at http://127.0.0.1:8000/
	Quit the server with CTRL-BREAK.

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

************* FRONTEND *************************

- Entre na pasta front:
C:\Users\SeuCPF\Desktop\temp\2DS13> cd front
C:\Users\SeuCPF\Desktop\temp\2DS13\fornt>

- Dê o comando "yarn", se não existir "npm install"
C:\Users\SeuCPF\Desktop\temp\2DS13\fornt>yarn

########################################################################################################
- Caso não exista nenhum dos 2, verifique no Windows em aplicativos instalados se o NodeJS está lá.
- Caso não esteja, instale-o e tente novamente.
- O comando para testar o NodeJS é "npm" (Node Packet Manager)
- Dê os seguintes comandos:
	npm install -g npm
	npm install -g yarn
- Normalmente tudo fica instalado em C:\Users\SeuUsuario\AppData\Roaming\npm e o ideal é coloca-lo nas variáveis de ambiente para que o yarn também possa ser utilizado.
########################################################################################################
- C:\Users\SeuCPF\Desktop\temp\2DS13\fornt>yarn

- Para iniciar o front é:
C:\Users\SeuCPF\Desktop\temp\2DS13\fornt>yarn dev
ou
C:\Users\SeuCPF\Desktop\temp\2DS13\fornt>npm run dev





=> English

To run the code:

Enter the desired repository.
Go to the green button (Code) and copy the repository URL (two sheets).
Create a folder on your computer.
Access this folder. 
Example: C:\Users\YourUser\Desktop\temp>
Run a git clone: 
Example: 
C:\Users\YourCPF\Desktop\temp>git clone https://github.com/lindomarbatistao/2DS13.git

Enter the folder: 
C:\Users\YourCPF\Desktop\temp>cd 2DS13 C:\Users\YourCPF\Desktop\temp\2DS13>

$$$$$$ BACKEND $$$$$$$$$$$$$$$$$$$$$$$$$$$$

Enter the back folder: 
C:\Users\YourCPF\Desktop\temp\2DS13>cd back C:\Users\YourCPF\Desktop\temp\2DS13\back>

Test the "py" command. If it doesn't work, try "python". If neither work, follow the steps below:
############ If python or py doesn't work ########################################################## 
1- Run the command "where python". If Python is installed, it will show the path. You can then add it to your environment variables for it to work. 
2- If it’s not there, download and install Python, note the installation path, and add it to the environment variables. 
3- Remember that any changes to the operating system require you to disregard previous prompts and open new ones. 
########################################################################################################

Update pip: 
C:\Users\YourCPF\Desktop\temp\2DS13\back>python.exe -m pip install --upgrade pip

Create the virtual environment: 
C:\Users\YourCPF\Desktop\temp\2DS13\back>py -m venv env

Activate the environment: 
C:\Users\YourCPF\Desktop\temp\2DS13\back>env\Scripts\Activate 
(env) C:\Users\YourCPF\Desktop\temp\2DS13\back>

Install all the required packages: 
(env) C:\Users\YourCPF\Desktop\temp\2DS13\back>pip install -r requirements.txt

Start the server: 
(env) C:\Users\YourCPF\Desktop\temp\2DS13\back>py manage.py runserver

Result: Watching for file changes with StatReloader Performing system checks...

System check identified no issues (0 silenced). March 25, 2025 - 20:43:13 Django version 5.1.5, using settings 'cadastro.settings' Starting development server at http://127.0.0.1:8000/ Quit the server with CTRL-BREAK.

************* FRONTEND ************************* 
- Enter the front folder:
- C:\Users\YourCPF\Desktop\temp\2DS13> cd front
- C:\Users\YourCPF\Desktop\temp\2DS13\front>

- Run the "yarn" command, if it doesn't exist, run "npm install":
- C:\Users\YourCPF\Desktop\temp\2DS13\front>yarn

######################################################################################################## 
- If neither of them exist, check in Windows under installed applications if NodeJS is there.
- If it's not there, install it and try again.
- The command to test NodeJS is "npm" (Node Packet Manager).
- Run the following commands: npm install -g npm
- npm install -g yarn
- Normally, everything is installed in C:\Users\YourUser\AppData\Roaming\npm, and it's ideal to add it to environment variables so that yarn can also be used.
########################################################################################################
- C:\Users\YourCPF\Desktop\temp\2DS13\front>yarn
- To start the front, use:
  C:\Users\YourCPF\Desktop\temp\2DS13\front>yarn dev
- or
  C:\Users\YourCPF\Desktop\temp\2DS13\front>npm run dev
