<p align="center">
<a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience" target="_blank">
<img src="https://insidesherpa-assets.s3-ap-southeast-2.amazonaws.com/icons/jpmorgan/github+repo+images/jpmc+github+img.png">
	</a>
</p>

<p align="center"> 
	<b><a href="#task">Task Overview</a></b>
	|
	<b><a href="#installation">Installation Instructions</a></b>
	| 
	<b><a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/88AisH7iuw3L5N5ig" target="_blank">Link to Module 2</a></b>

<h1> Introduction</h1> 
<b> Experience Technology at JP Morgan Chase </b>
<p>Try out what real work is like in the technology team JP Morgan Chase. Fast track to the tech team with your work.</p>

<h2 id="task"> Module 2 Task Overview </h2>
<p>Use JP Morgan Chase's frameworks and tools
Implement JP Morgan Chase’s Perspective open source code in preparation for data visualization</p>
<p> <b>Aim:</b>Take an incomplete setup of Perspective, i.e. a graph that updates manually, and make it work with the code from Task 1 such that it now updates automatically by continuously requesting from the server application</p>

<h2 id="installation" >Set up / Installation</h2>
<p>In order to get the server and client application code working on your machine, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m2_v8.pdf">follow the setup here</a></p>

<p><b>Note</b>:This is the version of the JPM 2 exercise that uses Python 3. The Python 2.7 version is in <a href="https://github.com/insidesherpa/JPMC-tech-task-2">this other repo</a></p>

<h2>How to Run</h2>

<p>Similar to Task 1, start the data feed server by running the python server.</p> 
<p>Make sure your terminal / command line is in the repository first before doing any of this.</p>
<p>If you are using Windows, make sure to run your terminal/command prompt as administrator.</p>

<code> python datafeed/server3.py </code>

If you encounter an issue with `datautil.parser`, run this command: 

	pip install python-dateutil

If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run <code>npm install && npm start</code> to start the React application.

It's okay to have audit warnings when installing/running the app.

If you don't have `npm` (although you should if you followed the set up / installation part), you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

The recommended version are node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.

