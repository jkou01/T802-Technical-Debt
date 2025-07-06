<h1>Introduction</h1>
This repsotiry contains raw data concerning tecnical debt. The data has been collected from 41 open-source project repositories from the Apache and Eclipse Foundations. These repositories are (functionally) primarily written in Python as per the nature of the research this data is collected for.

<h1>Data organisation</h1>
The complete data set is available in the <code>/data_collection</code> directory.
<br><br>
Each repository's (filename referred to as <code>&lt;repo&gt;</code>) data is divided into 3 files:
<ul>
  <li>Raw SonarQube debt data (<code>&lt;repo&gt;.csv</code>)</li>
  <li>SonarQube analysis metadata (<code>&lt;repo&gt;_analysis_meta.csv</code>)</li>
  <li>Git commit history change summary data (<code>&lt;repo&gt;_git_changes.csv</code>)</li>
</ul>
Each file is a UTF-8 encoded CSV with standard comma delimitation. <strong>Please note</strong> that some files may be broken into smaller fragments due to the large amount of data within. In this case they will be numbered (e.g. <code>&lt;repo&gt;_git_changes_1.csv</code>, <code>&lt;repo&gt;_git_changes_2.csv</code> etc.). 
