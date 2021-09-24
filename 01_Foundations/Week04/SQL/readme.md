<h1>SQL in action</h1>

<h3>Query</h3>
<p>A request for data or information from a database.</p>



<img src='https://i.imgur.com/XPyZIGy.png'>

<p>Every programming language, including SQL, follows a unique set of guidelines known as syntax. 
  
  Syntax is the predetermined structure of a language that includes all required words, symbols, and punctuation, as well as their proper placement.</p>


<ul>
  <li>Use <b>SELECT</b> to choose the columns you want to return.</li>
  <li>Use <b>FROM</b> to choose the tables where the columns you want are located.</li>
  <li>Use <b>WHERE</b> to filter for certain information.</li>
  </ul>


<h2><b>Example of a query</b></h2>

<img src='https://i.imgur.com/K9sxnVn.png'>

<p>The above query uses three commands to locate customers with the first name Tony: </p>

<ol>
  <li><b>SELECT</b> the column named <b>first_name</b></li>
  <li><b>FROM</b> a table named <b>customer_name</b> (in a dataset named <b>customer_data</b>)
    
(The dataset name is always followed by a dot, and then the table name.)</li>
  <li>But only return the data <b>WHERE</b> the first_name is <b>Tony</b></li>
  </ol>
  
  
  
 <p>If you are requesting multiple data fields from a table, you need to include these columns in your SELECT command. Each column is separated by a comma as shown below:</p>

<img src='https://i.imgur.com/DUZtgJe.png'>

<p>Here is an example of how it would appear in BigQuery:</p>

<img src='https://i.imgur.com/BWmklJp.png'>


<p>The above query uses three commands to locate customers with the first name Tony.</p>

<ol>
  <li><b>SELECT</b> the columns named <b>customer_id, first_name,</b> and <b>last_name</b></li>
  <li>FROM a table named customer_name (in a dataset named customer_data)
(The dataset name is always followed by a dot, and then the table name.)</li>
  <li>But only return the data WHERE the first_name is Tony</li>
</ol>

<p> The only difference between this query and the previous one is that more data columns are selected.</p>

<p>If you have multiple conditions in your WHERE clause, they may be written like this:</p>

<img src="https://i.imgur.com/w10NAvf.png">

<p>Notice that unlike the SELECT command that uses a comma to separate fields/variables/parameters, the WHERE command uses the AND statement to connect conditions.</p>
