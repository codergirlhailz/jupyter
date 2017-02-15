# jupyter

####Set up
`pip3 install jupyter`

####Start it
1. Command line- `jupyter notebook`
2. Jupyter will start up in your browser!
3. Make a new folder called 'jupyter' and then click into it
4. Click on 'new' in the upper right corner, and select Python 3 Notebook
Your notebook is ready to go!

####Adding code and running it
Write your code in the empty cell. Your output will be displayed in a cell underneath it by selecting Run All under Cells in the toolbar. You can try this out with something as simple as `print("Hello world")`

Conveniently, you can separate your code into multiple cells. This allows you to test the output of specific parts of the code without having to run everything each time. You use the Insert button in the toolbar for this. 

####Git
Save your notebook with a name. It will appear as a .ipynb file. You can add these notebooks to git just as you would a regular .py file.

1. Navigate to your 'jupyter' directory in your command line
2. `git init`
3. `git status` you should see your .ipynb file ready to be added
4. `git add filename.ipynb`
5. `git commit -m "first commit"`
6. `git push`
