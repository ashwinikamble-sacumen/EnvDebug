# EnvDebug
Create Virtual environment

Topics:
1. Creating Virtual Environment:
   python3 -m venv name_of_env
   activate using : source name_of_env/bin/activate
2. Install packages

3. Debugging:
   The module pdb defines an interactive source code debugger for Python programs.
   This module is already installed with installing of python. So, we only need to import it into our code to use its functionality.

4.To import we simply use import pdb in our code.
  For debugging, we will use pdb.set_trace() method.

  These commands can be use :

c -> continue execution

q -> quit the debugger/execution

n -> step to next line within the same function

s -> step to next line in this function or a called function

  
   
