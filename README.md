# Itai's Declassified Physics Survival Guide
If you get the repository name reference...respect.

These are some (hopefully) helpful pieces of advice for university physics students expecially those who are interested in computer programming and the problems it allows yo to solve. Everything here is my opinion but I think it's general enough to be valid. Full disclosure my expertise are on the Python + machine learning + AI side of things but I know a bit of other stuff as well.

<br>

## General Advice
Before I jump into the technical stuff, I want to give some general tips that I wish I knew before I went to university. These are applicable for all students, not just physics ones.

 - #### Get a good set of tupperwares...trust me.
 - #### Never buy cheap bin bags.
 - #### Never feel you have to go out partying every night, you will meet people either way.
 - #### Talk to your lecturers; you will learn more and get inside info on things you may be able to work on.
 - #### Sautee some Peperami, add baked beans and reduce to taste...you're welcome (sorry vegie people).

<br>

 ## Advice for Those Interested in Programming

 You will probably have noticed that computer programming is a useful skill in pretty much every field of research and throughout industry. The first few sub-sections are about specific tools that I think everyone interested in programming should learn. After these, there are sub-sections about particular fields within programming.

 ### Command Line
 Being able to use the command line will allow you to move around your file system and write code more effectively than using a graphical file explorer.

 ### GitHub
 The fact that you are reading this at all, means that you have already used one of the most useful and widely used tools in the world of programming, GitHub. This is a place where programmers put their code, it is used to track the development of the code (version control). 

 ### Git
 Git is a tool use mainly on the command line to track changes to files and interface with remote code repositories (like GitHub). You should definitely learn at least the basics of Git.

 ### Text Editors
 To write code, you need a text editor. There are many on offer. Three big ones are:

  - [**VScode:**](https://code.visualstudio.com) One of the most popular text editors in the world with a huge plugin ecosystem.

  - [**Vim:**](https://www.vim.org) A command line based editor. I recommend learning how to use Vim even if you are not going to use it as your main editor as you can quickly edit files right on the command line.

  - [**NeoVim:**](https://neovim.io) An offshoot of Vim which is more actively developed. I would highly recommend NeoVim if you are fairly comfortable using the command line.

Look into these and others to decide what you want to code in.

<br>

<details>
    <summary style="font-size: 2.0rem;"> Data Science </summary>
    <p>
    Data science is about extracting useful information from data. This may be anything from basic aggregation and visualisation to predicting stock prices and making ChatGPT.
    <p>
    <h3>
    Languages:
    </h3>
    <ul style="padding-left: 20px;">
        <li>
        <strong style="color:orange;">Python</strong> is essential.
        </li>
        <li>
        Good to know the basics of a compiled language like <strong style="color:orange;">C++</strong>.
        </li>
        <li>
        <strong style="color:orange;">R</strong> is liked by some companies but not very important.
        </li>
        <li>
        languages used in web dev <strong style="color:orange;">JavaScript</strong>, <strong style="color:orange;">HTML</strong> and <strong style="color:orange;">CSS</strong> can be useful but are not essential.
        </li>
        <li>
        Worth being competent in <strong style="color: orange">MS Excel</strong>.
    </ul>
    <h3>
    Data Sciecne Things (and Tools to Do Them):
    </h3>
    <ul style="padding-left: 20px;">
        <li>
        <strong>Data Visualisation</strong> (<a href="https://matplotlib.org/stable/" target="_blank">Matplotlib</a>, <a href="https://seaborn.pydata.org" target="_blank">Seaborn</a>, <a href="https://plotly.com" target="_blank">Plotly</a>)
        </li>
        <li>
        <strong>Data Aggregation and Wrangling</strong> (<a href="https://pandas.pydata.org/docs/" target="_blank">Pandas</a>, <a href="https://pola.rs" target="_blank">Polars</a>, <a href="https://numpy.org" target="_blank">Numpy</a>)
        </li>
        <li>
        <strong>Machine Learning</strong> (<a href="https://scikit-learn.org/stable/" target="_blank">Scikit-learn</a>, <a href="https://www.statsmodels.org/stable/index.html" target="_blank">Statsmodels</a>, <a href="https://xgboost.readthedocs.io/en/stable/" target="_blank">XGBoost</a>)
        </li>
        <li>
        <strong>Deep Learning</strong> (<a href="https://pytorch.org" target="_blank">PyTorch</a>, <a href="https://www.tensorflow.org" target="_blank">TensorFlow</a>, <a href="https://keras.io" target="_blank">Keras</a>, <a href="https://jax.readthedocs.io/en/latest/" target="_blank">Jax</a>, <a href="https://docs.tinygrad.org" target="_blank">tinygrad</a>)
        </li>
    </ul>
    <details>
        <summary style="font-size: 1.2rem; font-weight: bold;"> How To Get Noticed by Employers </summary>
        <ul style="padding-left: 20px;">
        <li>
        <strong style="color: orange">Projects</strong>,  whether solo, group, private, academic or whatever else are in my opinion the most important element to getting the attention of employers. This is because nothing could be better evidence of your knowledge and ability than a GitHub repository filled with your working code. It's also a really good strategy to link questions in an interview back to things you have done before (in projects). Some ideas for begginer projects could be:
            <ul style="list-style: circle; padding-left: 20px;">
            <li style="margin-top: 0.7rem;">
            <a href="https://ankushmulkar.medium.com/complete-exploratory-data-analysis-step-by-step-guide-for-data-analyst-34a07156217a">Exploratory Data Analysis (EDA) of a dataset</a>.
            </li>
            <li>
            <a href="https://medium.com/@kaushiksimran827/house-price-prediction-a-simple-guide-with-scikit-learn-and-linear-regression-f91a27b9d650">Simple Regression Model</a>
            </li>
            <li>
            <a href="https://www.learndatasci.com/glossary/binary-classification/">Simple Binary Classification Model</a>
            </li>
            </ul>
        If you're more experienced, you may want to try:
            <ul style="list-style: circle; padding-left: 20px;">
            <li style="margin-top: 0.7rem">
            <a href="https://www.geeksforgeeks.org/implementing-web-scraping-python-beautiful-soup/">Web Scraping</a>
            </li>
            <li>
            <a href="https://www.kaggle.com/code/androbomb/using-cnn-to-classify-images-w-pytorch">Image Classication with CNN's</a>
            </li>
            <li>
            <a href="https://www.kaggle.com/code/abhishekmamidi/time-series-analysis-artificial-neural-networks">Time Series Analysis with a Neural Network</a>
            </li>
            <li>
            <a href="https://medium.com/@lokaregns/fine-tuning-transformers-with-custom-dataset-classification-task-f261579ae068">Fine-Tuning a Transformer Model</a>  
            </li>
            </ul>
        </li>
        <li style="margin-bottom: 0.7rem;">
        <strong style="color: orange">Coding Challenges and competitions</strong> are a great to show that you can not only produce good code, but can produce code which solves a problem that you didn't come up with. This is more like what you would be doing in a job. There are two main types of challenges/competitions I want to highlight:
            <ul style="list-style: circle; padding-left: 20px;">
            <li style="margin-top: 0.7rem; margin-bottom: 0.7rem">
            <a href="https://www.kaggle.com/competitions">Kaggle Competitions</a> are online competitions which are generally focused on data science and AI. There are ones which last as little as a few weeks and ones that run continuously (many have prizes for the top entries). I recommend starting with the 'playground series'. You don't need to win or even be in the top 10; taking part will teach you things and show employers your that you're genuinly interested in the field.
            </li>
            <li>
            <strong>Hackathons</strong> are relatively short, intense coding sessins which are often organised as competitions. I personally did a hackathon and later worked for the company that organised it. Hackathons often have a cash prize pool and some even pay participants for their time. I recommend just searching online for hackathons and asking peopkle in the know.
            </li>
            </ul>
        </li>
        </ul>
    </details>
</details>

 