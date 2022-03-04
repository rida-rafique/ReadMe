# Recipe Evolution
Pre-Requisite
<ul><li>MS Excel 
<li>Visual Web Ripper
<li>SQLiteStudio
<li>MYSQL Workbench 
About
<p>Formulating new recipes is more of an art than a science. We will create a software application that will be using a large dataset of recipes from all over the world to intelligently generate new and improved recipes having not only generated taste but will also contain required nutritional value. <p/>
**Recipe Evolution**
<p>A recipe evaluation form is an essential tool for a chef to maintain consistency within his restaurant. Without regular evaluations of existing recipes on the menu a variety of issues will crop up which will affect the consistency of your recipes and the guest's satisfaction. However, in this we will highlight what is evaluated in a meal, defining the standards and speciation of the prepared dishes.</P>
Recipe Evolution
  <p>A recipe evaluation form is an essential tool for a chef to maintain consistency within his restaurant. Without regular evaluations of existing recipes on the menu a variety of issues will crop up which will affect the consistency of your recipes and the guest's satisfaction. However, in this we will highlight what is evaluated in a meal, defining the standards and speciation of the prepared dishes.</p>
Evolution
  <p>Evolution is a process that helps individuals to adapt themselves to the constantly changing environment. An Evolutionary Algorithm, a subset of Evolutionary Computing, is a stochastic search for an optimum solution to a given problem. Due to its efficient nature and robust behavior, it has become an efficient means of the problem-solving method used for global optimization of problems.</p>
 #Issues and Challenges
  <p>Some of the listed ingredients sometimes are not able to prepare or use for cooking for some reasons:</p>
  <li>Allergies</li>
  <li>Personal preference</li>
  <li>	Or some ingredients are not available in the kitchen</li>
  <p>We try to switch ingredients that help to keep the same taste or texture. For that purpose we use different methodologies </p>
  <li>Genetic Algorithm which model genetic evolution.</li>
  <li>Genetic programming which is based on genetic algorithms, but individuals is programs (represented as trees).</li>
Activities
Documentation 
 <p>Read Different Research paper and Write summary in which tells about </p>
<li>Which is done?</li>
<li>What was the outcome?</li>
<li>Strength</li>
  <li>Weakness</li>
Extraction 
    <p>To do Extraction perform following steps</p>
    <li>Open visual web Ripper and paste website lin</li>
    <li>Now to extract data create template, selects all recipes, click new write name, click save.
    <li>Check if there are more than one page than add page navigation and change the link to page navigation. Now open the list and add content. E.g. recipe name, Cooktime, Preptime, Instructions, Ingredients and nutrition</li>
  <li>Run the Project. </li>
Transformation 
  <p>To perform Transformation on data does following steps </p>
  <li>Open SQLiteStudio and export your project internal file and close SQLiteStudio.</li>
  <li>Go to web ripper output folder and open trial file in notepad and perform some Transformation </li>
  <ul><li>	Comment Pragma foreign key with ----</ul></li>
<ul><li>Replace “ with !	</ul></li>
<ul><li>Replace [ !</ul></li>
<ul><li>Replace ] !</ul></li>
<ul><li>Replace nvarchar(4000) with text</ul></li>
<ul><li>Replace guid with char(36)</ul></li>
<li>Open Database with assigned name and password and import file.</li>
Consolidation 
<p>To perform Consolidation on data does following steps</p> 
<li>Open MySQL Workbench and create connection.</li>
<li>Click on open sql script and select file click on ok.</li>
<li>Write database name and run the query.</li>
<li>Write recipe table name and run the query.
<li>To create idid column write 3 digit id value 
<li>Remove duplicate url in temp1 
<li>Consolidate ingredients, instruction and nutrition. 
Install 
Visual Web Ripper 
Download here https://download.cnet.com/Visual-Web-Ripper/3000-2381_4-10754835.html
SQLiteStudio 
  Download here <a href="https://sqlitestudio.pl/"></a>


