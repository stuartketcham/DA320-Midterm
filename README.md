# DA320-Midterm

<h2 align="center">DA320 - Data Acquisition & Management</h2>
<h2 align="center">Midterm</h2>
<h3 align="center">Scraping Metacritic and Reporting on the Data</h3>

<p align="center">
    <h2>Project</h2>
    <b>Purpose:</b> This project is an exercise in data gathering and reporting.<br />
    <h3>Step 1 - Gathering the Data</h3>
    <b>File:</b> <i>KetchamStuart-MetacriticToMongoDB.ipynb</i><br />
    <b>Data:</b> The source is Metacritic.com. The data gathered is all movies from the years 2000-2022 up to 11/5/2022.<br />
    <b>Gathering Method:</b> Regular expressions are used to locate valuable data amongst the HTML.<br />
    <b>Destination:</b> The gathered data is stored in MongoDB.<br />
    <br />
    <h3>Step 2 - Reporting on the Data</h3>
    <b>File:</b> <i>KetchamStuart-MetacriticGraphs.ipynb</i><br />
    <b>Data:</b> The data from Step 1 is pulled back from MongoDB<br />
    <b>Reporting Method:</b> Graphical reporting using MatPlotLib and Seaborn<br />
    <b>Content:</b> <br />
    <ul>
        <li>Average Movie Metascore by Year</li>
        <li>Score Trends by Month of the Year</li>
    </ul>
    <br />
    <h3>Conclusions</h3>
    <h4>Reporting</h4>
    The data itself show some interesting trends. 
    <ol>
    <li>It appears that Metacritic scores have been on the rise from 2000 to 2005, plateaued from 2005 to 2015, and rose sharply from 2015-2022.<br />
    There are a large number of potential reasons that could have caused this pattern, but they would all require further investigation, which is beyond the scope of this project.<br /></li>
    <li>There is also a subtle trend in the scores of movies over the course of the year.  This is mostly likely caused by the impact of Oscar award nominations and the release of big-budget movies in the summer months.
    </ol>
    
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
    <br />



</p>