# To use with vs code as a template:

1. **Create a Virtual Environment:**
   Open a terminal or command prompt and navigate to the directory where you want to create the virtual environment. Then run the following commands:

   ```sh
   python -m venv myenv
   ```

   This will create a new virtual environment named `myenv`.

2. **Activate the Virtual Environment:**
   - On Windows:
     ```sh
     myenv\Scripts\activate
     ```
   - On macOS and Linux:
     ```sh
     source myenv/bin/activate
     ```

3. **Install Jupyter and Matplotlib in the Virtual Environment:**
   With the virtual environment activated, install Jupyter and Matplotlib:

   ```sh
   pip install jupyter matplotlib
   ```

4. **Open the Notebook in VS Code:**
   - Open a workspace in Vs Code, use the folder where the virtual environment is located.
   - Install the Jupyter extension for VS Code if you haven't already. You can do this by searching for "Jupyter" in the Extensions view (`Ctrl+Shift+X`).
   - Open the `.ipynb` file you created (e.g., `College_Algebra_Notebook_Template.ipynb`).
   - Ensure the kernel selected in VS Code is the one from your virtual environment. You can select the kernel from the top-right corner of the notebook interface in VS Code.

5. **Run the Notebook:**
   - Execute the cells with python code in the notebook to verify that everything is working correctly.

By following these steps, you can ensure that Matplotlib and any other necessary packages are installed in the virtual environment, and you can run your Jupyter Notebook within that environment.
