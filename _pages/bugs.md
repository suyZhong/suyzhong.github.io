---
layout: page
permalink: /bugs/
title: Found Bugs
description: Found bugs in DBMS systems.
nav: true
---
<div class="bombs">


<div class="container">
<br/>
<h2 id="dbms">Database Management Systems (247 bugs)</h2>
<h3>CrateDB (48 bugs)</h3>
<details>
<summary>Unexpected result when using CASE statement</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15029">https://github.com/crate/crate/issues/15029</a> <br />
</details>
<details>
<summary>Unexpected Results when Using AND Operator</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15050">https://github.com/crate/crate/issues/15050</a> <br />
</details>
<details>
<summary>Unexpected Results when Using Concat Operator</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15083">https://github.com/crate/crate/issues/15083</a> <br />
</details>
<details>
<summary>Unexpected Results Using Boolean</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15120">https://github.com/crate/crate/issues/15120</a> <br />
</details>
<details>
<summary>Unexpected Results Using NULLIF</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15121">https://github.com/crate/crate/issues/15121</a> <br />
</details>
<details>
<summary>Unexpected result when using BETWEEN AND</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15201">https://github.com/crate/crate/issues/15201</a> <br />
</details>
<details>
<summary>Unexpected result when Concatenating NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15202">https://github.com/crate/crate/issues/15202</a> <br />
</details>
<details>
<summary>Unexpected Result when using IS NOT NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15265">https://github.com/crate/crate/issues/15265</a> <br />
</details>
<details>
<summary>Unexpected Result when using LEFT JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15324">https://github.com/crate/crate/issues/15324</a> <br />
</details>
<details>
<summary>Unexpected Results Using NULLIF with VARCHAR</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15325">https://github.com/crate/crate/issues/15325</a> <br />
</details>
<details>
<summary>Unexpected Result when using IN</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15326">https://github.com/crate/crate/issues/15326</a> <br />
</details>
<details>
<summary>Unexpected result when using string comparison AND IS NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15395">https://github.com/crate/crate/issues/15395</a> <br />
</details>
<details>
<summary>Unexpected results when using AND</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15458">https://github.com/crate/crate/issues/15458</a> <br />
</details>
<details>
<summary>Unexpected result when using CONCAT_WS containing NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15459">https://github.com/crate/crate/issues/15459</a> <br />
</details>
<details>
<summary>Unexpected result when using % with NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15500">https://github.com/crate/crate/issues/15500</a> <br />
</details>
<details>
<summary>Unexpected result when using LTRIM with NULL as second argument</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15527">https://github.com/crate/crate/issues/15527</a> <br />
</details>
<details>
<summary>Unexpected result when casting integer as boolean</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15537">https://github.com/crate/crate/issues/15537</a> <br />
</details>
<details>
<summary>Weird string substitution when using JDBC</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15566">https://github.com/crate/crate/issues/15566</a> <br />
</details>
<details>
<summary>Unexpected result when using OR</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15592">https://github.com/crate/crate/issues/15592</a> <br />
</details>
<details>
<summary>Unexpected result when using INNER JOIN and CASE in filter</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15613">https://github.com/crate/crate/issues/15613</a> <br />
</details>
<details>
<summary>Unexpected result when using LIKE</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/15743">https://github.com/crate/crate/issues/15743</a> <br />
</details>
<details>
<summary>Unexpected results when using system information functions</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16026">https://github.com/crate/crate/issues/16026</a> <br />
</details>
<details>
<summary>Unexpected result when using CURRENT_SETTING</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16062">https://github.com/crate/crate/issues/16062</a> <br />
</details>
<details>
<summary>Unexpected result when using PG_GET_PARTKEYDEF</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16172">https://github.com/crate/crate/issues/16172</a> <br />
</details>
<details>
<summary>Unexpected result when using DEFAULT during creating table</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16173">https://github.com/crate/crate/issues/16173</a> <br />
</details>
<details>
<summary>Unexpected result when querying with boolean comparisons</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16227">https://github.com/crate/crate/issues/16227</a> <br />
</details>
<details>
<summary>Unexpected result when using FORMAT_TYPE</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16225">https://github.com/crate/crate/issues/16225</a> <br />
</details>
<details>
<summary>Unexpected result when using escape character in LIKE</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16350">https://github.com/crate/crate/issues/16350</a> <br />
</details>
<details>
<summary>Unexpected result when using empty OBJECT literal</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16476">https://github.com/crate/crate/issues/16476</a> <br />
</details>
<details>
<summary>Unexpected results when using OBJECT nulls</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16556">https://github.com/crate/crate/issues/16556</a> <br />
</details>
<details>
<summary>Unexpected results when matching empty string with indexing disabled</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16567">https://github.com/crate/crate/issues/16567</a> <br />
</details>
<details>
<summary>Unexpected result when querying partitioned table with null values</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16577">https://github.com/crate/crate/issues/16577</a> <br />
</details>
<details>
<summary>Unexpected result when using bigint in ORDER BY</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16615">https://github.com/crate/crate/issues/16615</a> <br />
</details>
<details>
<summary>Unexpected result when querying partitioned table with CASE WHEN</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16614">https://github.com/crate/crate/issues/16614</a> <br />
</details>
<details>
<summary>Unexpected result when using ARRAY(TEXT) in IN</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16652">https://github.com/crate/crate/issues/16652</a> <br />
</details>
<details>
<summary>OutOfMemory when creating table with large replicas</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16668">https://github.com/crate/crate/issues/16668</a> <br />
</details>
<details>
<summary>Unexpected result when comparing CHAR with ''</summary>
Status: confirmed<br />
Link: <a href="https://github.com/crate/crate/issues/16689">https://github.com/crate/crate/issues/16689</a> <br />
</details>
<details>
<summary>Unexpected result when comparing IP</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16690">https://github.com/crate/crate/issues/16690</a> <br />
</details>
<details>
<summary>Unexpected result when RIGHT JOIN a subquery</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16951">https://github.com/crate/crate/issues/16951</a> <br />
</details>
<details>
<summary>Potential hang when LEFT JOIN a subquery with EXP</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16952">https://github.com/crate/crate/issues/16952</a> <br />
</details>
<details>
<summary>Unexpected result when using multiple RIGHT JOIN</summary>
Status: confirmed<br />
Link: <a href="https://github.com/crate/crate/issues/17089">https://github.com/crate/crate/issues/17089</a> <br />
</details>
<details>
<summary>Potential hang when LEFT JOIN a subquery with EXP</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/16952">https://github.com/crate/crate/issues/16952</a> <br />
</details>
<details>
<summary>Unexpected results when using LEFT JOIN with a subquery</summary>
Status: confirmed<br />
Link: <a href="https://github.com/crate/crate/issues/17380">https://github.com/crate/crate/issues/17380</a> <br />
</details>
<details>
<summary>Unexpected results when querying BOOLEAN values</summary>
Status: confirmed<br />
Link: <a href="https://github.com/crate/crate/issues/17379">https://github.com/crate/crate/issues/17379</a> <br />
</details>
<details>
<summary>Unexpected results when using ARRAY_POSITION</summary>
Status: confirmed<br />
Link: <a href="https://github.com/crate/crate/issues/17378">https://github.com/crate/crate/issues/17378</a> <br />
</details>
<details>
<summary>Unexpected result when using IP addresses</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/17764">https://github.com/crate/crate/issues/17764</a> <br />
</details>
<details>
<summary>Unexpected result when comparing CHAR values with newline</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/17765">https://github.com/crate/crate/issues/17765</a> <br />
</details>
<details>
<summary>Unexpected result when querying a partitioned table by a BOOLEAN column</summary>
Status: fixed<br />
Link: <a href="https://github.com/crate/crate/issues/17766">https://github.com/crate/crate/issues/17766</a> <br />
</details>
<h3>MonetDB (47 bugs)</h3>
<details>
<summary>Unexpected result for INNER JOIN with IS NOT NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7426">https://github.com/MonetDB/MonetDB/issues/7426</a> <br />
</details>
<details>
<summary>Unexpected result when using AND and IS NOT NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7430">https://github.com/MonetDB/MonetDB/issues/7430</a> <br />
</details>
<details>
<summary>Unexpected result when using CASE WHEN</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7429">https://github.com/MonetDB/MonetDB/issues/7429</a> <br />
</details>
<details>
<summary>Unexpected result when using BETWEEN operator</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7428">https://github.com/MonetDB/MonetDB/issues/7428</a> <br />
</details>
<details>
<summary>Unexpected result when using AND/OR chain</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7448">https://github.com/MonetDB/MonetDB/issues/7448</a> <br />
</details>
<details>
<summary>Unexpected result when using BETWEEN in INNER JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7447">https://github.com/MonetDB/MonetDB/issues/7447</a> <br />
</details>
<details>
<summary>Unexpected result when using BETWEEN and CAST</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7451">https://github.com/MonetDB/MonetDB/issues/7451</a> <br />
</details>
<details>
<summary>Unexpected result when CREATE VIEW with WHERE NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7450">https://github.com/MonetDB/MonetDB/issues/7450</a> <br />
</details>
<details>
<summary>Unexpected result when using BETWEEN with BOOLEAN values</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7455">https://github.com/MonetDB/MonetDB/issues/7455</a> <br />
</details>
<details>
<summary>Crash when INNER JOIN with VIEW</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7456">https://github.com/MonetDB/MonetDB/issues/7456</a> <br />
</details>
<details>
<summary>Unexpected result when using AND with INTEGER</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7457">https://github.com/MonetDB/MonetDB/issues/7457</a> <br />
</details>
<details>
<summary>Unexpected result when using SIGN</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7458">https://github.com/MonetDB/MonetDB/issues/7458</a> <br />
</details>
<details>
<summary>Crash when using CONTAINS in ORDER BY clause</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7459">https://github.com/MonetDB/MonetDB/issues/7459</a> <br />
</details>
<details>
<summary>Crash when using CAST and BETWEEN AND</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7460">https://github.com/MonetDB/MonetDB/issues/7460</a> <br />
</details>
<details>
<summary>Crash by potentially use of bad escape characters</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7461">https://github.com/MonetDB/MonetDB/issues/7461</a> <br />
</details>
<details>
<summary>Unexpected result when using CONTAINS and type casting</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7463">https://github.com/MonetDB/MonetDB/issues/7463</a> <br />
</details>
<details>
<summary>Crash when using BETWEEN AND</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7462">https://github.com/MonetDB/MonetDB/issues/7462</a> <br />
</details>
<details>
<summary>Crash when INNER JOIN with CONTAINS</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7466">https://github.com/MonetDB/MonetDB/issues/7466</a> <br />
</details>
<details>
<summary>Unexpected result when using NULL in BETWEEN</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7465">https://github.com/MonetDB/MonetDB/issues/7465</a> <br />
</details>
<details>
<summary>Unexpected result when using IFNULL with large numbers</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7468">https://github.com/MonetDB/MonetDB/issues/7468</a> <br />
</details>
<details>
<summary>Crash when using CONTAINS</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7469">https://github.com/MonetDB/MonetDB/issues/7469</a> <br />
</details>
<details>
<summary>Unexpected result when using IS DISTINCT FROM</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7521">https://github.com/MonetDB/MonetDB/issues/7521</a> <br />
</details>
<details>
<summary>Assertion failure when using CONTAINS</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7523">https://github.com/MonetDB/MonetDB/issues/7523</a> <br />
</details>
<details>
<summary>Crash when creating view with HAVING</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7522">https://github.com/MonetDB/MonetDB/issues/7522</a> <br />
</details>
<details>
<summary>Unexpected error when using NATURAL RIGHT JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7524">https://github.com/MonetDB/MonetDB/issues/7524</a> <br />
</details>
<details>
<summary>Unexpected result when using IS DISTINCT FROM with RIGHT JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7527">https://github.com/MonetDB/MonetDB/issues/7527</a> <br />
</details>
<details>
<summary>Assertion failure when using JAROWINKLER in ORDER BY clause</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7528">https://github.com/MonetDB/MonetDB/issues/7528</a> <br />
</details>
<details>
<summary>Assertion failure when using JAROWINKLER with empty string</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7530">https://github.com/MonetDB/MonetDB/issues/7530</a> <br />
</details>
<details>
<summary>Unexpected result when using IS DISTINCT FROM with AND</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7534">https://github.com/MonetDB/MonetDB/issues/7534</a> <br />
</details>
<details>
<summary>Assertion failure when using GROUP BY when CREATE VIEW</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7535">https://github.com/MonetDB/MonetDB/issues/7535</a> <br />
</details>
<details>
<summary>Crash when using IS DISTINCT FROM with SIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7539">https://github.com/MonetDB/MonetDB/issues/7539</a> <br />
</details>
<details>
<summary>Assertion failure when using STARTSWITH</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7540">https://github.com/MonetDB/MonetDB/issues/7540</a> <br />
</details>
<details>
<summary>Unexpected result when using LEVENSHTEIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7541">https://github.com/MonetDB/MonetDB/issues/7541</a> <br />
</details>
<details>
<summary>Unexpected result when using IS DISTINCT FROM with constants</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7543">https://github.com/MonetDB/MonetDB/issues/7543</a> <br />
</details>
<details>
<summary>Unexpected result when using STARTSWITH</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7544">https://github.com/MonetDB/MonetDB/issues/7544</a> <br />
</details>
<details>
<summary>Crash when creating view with GROUP BY</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7545">https://github.com/MonetDB/MonetDB/issues/7545</a> <br />
</details>
<details>
<summary>Assertion failure when using INNER JOIN on STARTSWITH</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7553">https://github.com/MonetDB/MonetDB/issues/7553</a> <br />
</details>
<details>
<summary>Unexpected result when using NULL constant in comparison</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7552">https://github.com/MonetDB/MonetDB/issues/7552</a> <br />
</details>
<details>
<summary>Unexpected result when using range comparison with NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7554">https://github.com/MonetDB/MonetDB/issues/7554</a> <br />
</details>
<details>
<summary>Unexpected result when casting integer to boolean in comparison</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7555">https://github.com/MonetDB/MonetDB/issues/7555</a> <br />
</details>
<details>
<summary>Assertion failure when using STARTSWITH with view</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7556">https://github.com/MonetDB/MonetDB/issues/7556</a> <br />
</details>
<details>
<summary>Assertion failure when comparing INTERVAL value</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7562">https://github.com/MonetDB/MonetDB/issues/7562</a> <br />
</details>
<details>
<summary>Unexpected result when using IS DISTINCT FROM in VIEW</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7563">https://github.com/MonetDB/MonetDB/issues/7563</a> <br />
</details>
<details>
<summary>Crash when integer overflow in ORDER BY</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7571">https://github.com/MonetDB/MonetDB/issues/7571</a> <br />
</details>
<details>
<summary>Crash at strcpy_len ()</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7573">https://github.com/MonetDB/MonetDB/issues/7573</a> <br />
</details>
<details>
<summary>Assertion failure at rel2bin_select when using STARTSWITH</summary>
Status: confirmed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7574">https://github.com/MonetDB/MonetDB/issues/7574</a> <br />
</details>
<details>
<summary>Crash when using CHECK constraint</summary>
Status: fixed<br />
Link: <a href="https://github.com/MonetDB/MonetDB/issues/7577">https://github.com/MonetDB/MonetDB/issues/7577</a> <br />
</details>
<h3>Umbra (46 bugs)</h3>
<details>
<summary>Unexpected Results when Comparing Boolean Values</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Potential Issue in BETWEEN operator</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Potential Issue in NULLIF function</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Potential Issue about boolean pruning in filter</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Potential Issue about UNIQUE INDEX</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Potential Issue when Dropping table</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Segmentation fault when Using NATURAL LEFT JOIN</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Potential issue when Using Boolean values and BETWEEN Operator</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Potential issue handling Boolean values after INDEX</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected results after triggering an index scan</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Potential Issue when Using CONCAT with overflow integers</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Segmentation fault when Using Between Operator</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected Results When Using Between Operator and String Concatenation</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Segmentation fault when Using Between Operator and integer</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected results when Using BETWEEN Operator and Comparison</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected results when LEFT JOIN a view</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected results when Using UNION ALL for JOIN</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected results when Mod negative number with View</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Segmentation fault when Using NATURAL FULL JOIN</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected results when Using IN expression With INDEX</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected results when Using BETWEEN With VIEW</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected Results when Using NOT IN expression</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected Results when Using IS NULL with empty VIEW</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected Results when Using CAST</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected Results when Using IN and BETWEEN AND for VIEW</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>FATAL ERROR when Using NATURAL FULL JOIN</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected Results when Using IN and BETWEEN AND for VIEW</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Segmentation fault when Using NATURAL FULL JOIN</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected Results when Using Multiple Comparison</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected Results when Using LEFT JOIN with VIEW on IS NOT NULL</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Assertion failure when using UNION ALL</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected Abort</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected results when Using COS and IN expression</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Assertion failure when using NATURAL JOIN</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected results when Casting to VARCHAR</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected results when using NATURAL RIGHT JOIN with INDEX</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>ERROR: AddressSanitizer: stack-buffer-overflow</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Assertion failure when using COT and BETWEEN AND</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Crash when using BETWEEN operator and large integer</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>ERROR: AddressSanitizer: use-after-poison</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Assertion failure when using COALESCE and CASE WHEN</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Crash when using INNER JOIN</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected result when using LEFT JOIN and VIEW</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected result when using NULLIF and CAST in VIEW</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected result when using LEFT JOIN and NULL values</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected results when using logical operator in VIEW</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<h3>Dolt (28 bugs)</h3>
<details>
<summary>Unexpected Results when Using '%' operator</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7006">https://github.com/dolthub/dolt/issues/7006</a> <br />
</details>
<details>
<summary>Unexpected Results about Floating-point Type Casting</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7018">https://github.com/dolthub/dolt/issues/7018</a> <br />
</details>
<details>
<summary>Unexpected Results when Querying with NULL values</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7025">https://github.com/dolthub/dolt/issues/7025</a> <br />
</details>
<details>
<summary>Crashing by Division Operators</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7026">https://github.com/dolthub/dolt/issues/7026</a> <br />
</details>
<details>
<summary>Unexpected Results about Decimal-Boolean Casting in Filters</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7038">https://github.com/dolthub/dolt/issues/7038</a> <br />
</details>
<details>
<summary>Crash by Function DAYNAME</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7039">https://github.com/dolthub/dolt/issues/7039</a> <br />
</details>
<details>
<summary>Crash by ACOS</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7046">https://github.com/dolthub/dolt/issues/7046</a> <br />
</details>
<details>
<summary>Crash by Time Functions</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7056">https://github.com/dolthub/dolt/issues/7056</a> <br />
</details>
<details>
<summary>Crash by SQRT</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7060">https://github.com/dolthub/dolt/issues/7060</a> <br />
</details>
<details>
<summary>Unexpected Results when Querying with COT</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7072">https://github.com/dolthub/dolt/issues/7072</a> <br />
</details>
<details>
<summary>Potential Issue Using ROUND</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7073">https://github.com/dolthub/dolt/issues/7073</a> <br />
</details>
<details>
<summary>Unexpected Results when Using IN for Floating-Point</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7120">https://github.com/dolthub/dolt/issues/7120</a> <br />
</details>
<details>
<summary>Unexpected Results of In expressions</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7147">https://github.com/dolthub/dolt/issues/7147</a> <br />
</details>
<details>
<summary>Panic when Using BETWEEN and CASE WHEN</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7154">https://github.com/dolthub/dolt/issues/7154</a> <br />
</details>
<details>
<summary>Unexpected Results when Using IN after Creating Index</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7155">https://github.com/dolthub/dolt/issues/7155</a> <br />
</details>
<details>
<summary>Panic when Using BETWEEN AND</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7216">https://github.com/dolthub/dolt/issues/7216</a> <br />
</details>
<details>
<summary>Unexpected Results when Using ROUND()</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7222">https://github.com/dolthub/dolt/issues/7222</a> <br />
</details>
<details>
<summary>Unexpected Results when Using BETWEEN and LEFT JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7229">https://github.com/dolthub/dolt/issues/7229</a> <br />
</details>
<details>
<summary>Panic when Using INNER JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7235">https://github.com/dolthub/dolt/issues/7235</a> <br />
</details>
<details>
<summary>Unexpected Result when Using -'' in IN</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected Results when Using BETWEEN AND after CREATE INDEX</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7260">https://github.com/dolthub/dolt/issues/7260</a> <br />
</details>
<details>
<summary>Unexpected Result when Querying with CONCAT</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7261">https://github.com/dolthub/dolt/issues/7261</a> <br />
</details>
<details>
<summary>Panic when Using INNER JOIN with String in IN</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7262">https://github.com/dolthub/dolt/issues/7262</a> <br />
</details>
<details>
<summary>Unexpected results when comparing with empty string</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7323">https://github.com/dolthub/dolt/issues/7323</a> <br />
</details>
<details>
<summary>Unexpected result when using Boolean in IN</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7338">https://github.com/dolthub/dolt/issues/7338</a> <br />
</details>
<details>
<summary>Crash by INNER JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7371">https://github.com/dolthub/dolt/issues/7371</a> <br />
</details>
<details>
<summary>Unexpected results when comparing string with type conversion</summary>
Status: confirmed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7372">https://github.com/dolthub/dolt/issues/7372</a> <br />
</details>
<details>
<summary>Crash by IF and CHAR</summary>
Status: fixed<br />
Link: <a href="https://github.com/dolthub/dolt/issues/7515">https://github.com/dolthub/dolt/issues/7515</a> <br />
</details>
<h3>DuckDB (26 bugs)</h3>
<details>
<summary>Unexpected Results when using IS NOT NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/9806">https://github.com/duckdb/duckdb/issues/9806</a> <br />
</details>
<details>
<summary>Missing Results when using Floating-point in BETWEEN</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/9825">https://github.com/duckdb/duckdb/issues/9825</a> <br />
</details>
<details>
<summary>Internal Error: Calling StringValue::Get on a NULL value</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/9870">https://github.com/duckdb/duckdb/issues/9870</a> <br />
</details>
<details>
<summary>INTERNAL Error: Failed to bind column reference "" [1.2] (bindings: [1.1])</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/10087">https://github.com/duckdb/duckdb/issues/10087</a> <br />
</details>
<details>
<summary>Unexpected Result When Using `IS DISTINCT FROM` and `CASE WHEN` in a JOIN clause</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/12181">https://github.com/duckdb/duckdb/issues/12181</a> <br />
</details>
<details>
<summary>Unexpected result when using IN with DATE values</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/13380">https://github.com/duckdb/duckdb/issues/13380</a> <br />
</details>
<details>
<summary>Unexpected result when casting negative integer to BIT</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/13506">https://github.com/duckdb/duckdb/issues/13506</a> <br />
</details>
<details>
<summary>Unexpected result after creating index on varchar column</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/13785">https://github.com/duckdb/duckdb/issues/13785</a> <br />
</details>
<details>
<summary>Unexpected result when using IN with TIME values</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/13813">https://github.com/duckdb/duckdb/issues/13813</a> <br />
</details>
<details>
<summary>Unexpected result after creating index on DATE column</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/13842">https://github.com/duckdb/duckdb/issues/13842</a> <br />
</details>
<details>
<summary>Inconsistent results when casting BIT and VARBINARY</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/13905">https://github.com/duckdb/duckdb/issues/13905</a> <br />
</details>
<details>
<summary>Unexpected result when comparing STRUCT with INET</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/13924">https://github.com/duckdb/duckdb/issues/13924</a> <br />
</details>
<details>
<summary>INTERNAL Error: Attempted to dereference unique_ptr that is NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/13938">https://github.com/duckdb/duckdb/issues/13938</a> <br />
</details>
<details>
<summary>Unexpected result when casting TIMESTAMP_S to TIME</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/14026">https://github.com/duckdb/duckdb/issues/14026</a> <br />
</details>
<details>
<summary>Unexpected result of comparison of nested types containing NULL</summary>
Status: confirmed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected result when comparing BLOB</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/14567">https://github.com/duckdb/duckdb/issues/14567</a> <br />
</details>
<details>
<summary>Unexpected result when using INTERVAL and INNER JOIN subquery</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/14834">https://github.com/duckdb/duckdb/issues/14834</a> <br />
</details>
<details>
<summary>INTERNAL Error: Attempted to access index 0 within vector of size 0</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/15005">https://github.com/duckdb/duckdb/issues/15005</a> <br />
</details>
<details>
<summary>INTERNAL Error: ConstantFilter constant cannot be NULL - use IsNullFilter instead</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/15479">https://github.com/duckdb/duckdb/issues/15479</a> <br />
</details>
<details>
<summary>INTERNAL Error: Failed to bind column reference </summary>
Status: confirmed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/15586">https://github.com/duckdb/duckdb/issues/15586</a> <br />
</details>
<details>
<summary>INTERNAL Error: Vector::Reference used on vector of different type</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/15584">https://github.com/duckdb/duckdb/issues/15584</a> <br />
</details>
<details>
<summary>Unexpected result when using BETWEEN and CASE WHEN</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/15602">https://github.com/duckdb/duckdb/issues/15602</a> <br />
</details>
<details>
<summary>Unexpected results after indexing a column with multiple rows</summary>
Status: confirmed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/16074">https://github.com/duckdb/duckdb/issues/16074</a> <br />
</details>
<details>
<summary>Unexpected result when RIGHT JOIN with a subquery</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/16863">https://github.com/duckdb/duckdb/issues/16863</a> <br />
</details>
<details>
<summary>Unexpected result when using LEFT JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/17042">https://github.com/duckdb/duckdb/issues/17042</a> <br />
</details>
<details>
<summary>Unexpected results when comparing NULL values</summary>
Status: confirmed<br />
Link: <a href="https://github.com/duckdb/duckdb/issues/17257">https://github.com/duckdb/duckdb/issues/17257</a> <br />
</details>
<h3>Virtuoso (10 bugs)</h3>
<details>
<summary>Unexpected results when Using Trigonometric functions</summary>
Status: fixed<br />
Link: <a href="https://github.com/openlink/virtuoso-opensource/issues/1213">https://github.com/openlink/virtuoso-opensource/issues/1213</a> <br />
</details>
<details>
<summary>Unexpected results when Using RIGHT JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/openlink/virtuoso-opensource/issues/1214">https://github.com/openlink/virtuoso-opensource/issues/1214</a> <br />
</details>
<details>
<summary>Unexpected results when using trigonometric functions</summary>
Status: fixed<br />
Link: <a href="https://github.com/openlink/virtuoso-opensource/issues/1213">https://github.com/openlink/virtuoso-opensource/issues/1213</a> <br />
</details>
<details>
<summary>Unexpected Results when using LEFT JOIN with NULL</summary>
Status: fixed<br />
Link: <a href="https://github.com/openlink/virtuoso-opensource/issues/1236">https://github.com/openlink/virtuoso-opensource/issues/1236</a> <br />
</details>
<details>
<summary>Unexpected results when using LEFT JOIN with NULL as predicate</summary>
Status: fixed<br />
Link: <a href="https://github.com/openlink/virtuoso-opensource/issues/1238">https://github.com/openlink/virtuoso-opensource/issues/1238</a> <br />
</details>
<details>
<summary>Crash by CASE WHEN and unknown identifier</summary>
Status: fixed<br />
Link: <a href="https://github.com/openlink/virtuoso-opensource/issues/1239">https://github.com/openlink/virtuoso-opensource/issues/1239</a> <br />
</details>
<details>
<summary>Unexpected results when using ORDER BY</summary>
Status: fixed<br />
Link: <a href="https://github.com/openlink/virtuoso-opensource/issues/1241">https://github.com/openlink/virtuoso-opensource/issues/1241</a> <br />
</details>
<details>
<summary>Crash by CASE WHEN</summary>
Status: fixed<br />
Link: <a href="https://github.com/openlink/virtuoso-opensource/issues/1249">https://github.com/openlink/virtuoso-opensource/issues/1249</a> <br />
</details>
<details>
<summary>Unexpected results when using LEFT JOIN and UNION</summary>
Status: fixed<br />
Link: <a href="https://github.com/openlink/virtuoso-opensource/issues/1250">https://github.com/openlink/virtuoso-opensource/issues/1250</a> <br />
</details>
<details>
<summary>Unexpected results when using INNER JOIN and UNION</summary>
Status: fixed<br />
Link: <a href="https://github.com/openlink/virtuoso-opensource/issues/1251">https://github.com/openlink/virtuoso-opensource/issues/1251</a> <br />
</details>
<h3>TiDB (9 bugs)</h3>
<details>
<summary>Unexpected Results of IN expression With NATURAL RIGHT JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/pingcap/tidb/issues/49476">https://github.com/pingcap/tidb/issues/49476</a> <br />
</details>
<details>
<summary>Runtime error when using overflow integers</summary>
Status: confirmed<br />
Link: <a href="https://github.com/pingcap/tidb/issues/50489">https://github.com/pingcap/tidb/issues/50489</a> <br />
</details>
<details>
<summary>Unexpected Result with NATURAL RIGHT JOIN and Bitwise NOT</summary>
Status: confirmed<br />
Link: <a href="https://github.com/pingcap/tidb/issues/53506">https://github.com/pingcap/tidb/issues/53506</a> <br />
</details>
<details>
<summary>runtime error: index out of range [0] with length 0 by RAND()</summary>
Status: fixed<br />
Link: <a href="https://github.com/pingcap/tidb/issues/56270">https://github.com/pingcap/tidb/issues/56270</a> <br />
</details>
<details>
<summary>Unexpected result when using JSON_VALID</summary>
Status: fixed<br />
Link: <a href="https://github.com/pingcap/tidb/issues/56293">https://github.com/pingcap/tidb/issues/56293</a> <br />
</details>
<details>
<summary>Unexpected result when comparing TIMESTAMP null values</summary>
Status: confirmed<br />
Link: <a href="https://github.com/pingcap/tidb/issues/56294">https://github.com/pingcap/tidb/issues/56294</a> <br />
</details>
<details>
<summary>runtime error: invalid memory address or nil pointer dereference with JSON_EXTRACT</summary>
Status: confirmed<br />
Link: <a href="https://github.com/pingcap/tidb/issues/56300">https://github.com/pingcap/tidb/issues/56300</a> <br />
</details>
<details>
<summary>Unexpected result when using BIT_OR in RIGHT JOIN</summary>
Status: confirmed<br />
Link: <a href="https://github.com/pingcap/tidb/issues/57284">https://github.com/pingcap/tidb/issues/57284</a> <br />
</details>
<details>
<summary>Unexpected result when using BIT_OR in RIGHT JOIN</summary>
Status: confirmed<br />
Link: <a href="https://github.com/pingcap/tidb/issues/57284">https://github.com/pingcap/tidb/issues/57284</a> <br />
</details>
<h3>Firebird (9 bugs)</h3>
<details>
<summary>Crash potentially caused by BETWEEN Operator</summary>
Status: fixed<br />
Link: <a href="https://github.com/FirebirdSQL/firebird/issues/7860">https://github.com/FirebirdSQL/firebird/issues/7860</a> <br />
</details>
<details>
<summary>Unexpected Results when Using Natural Right Join</summary>
Status: fixed<br />
Link: <a href="https://github.com/FirebirdSQL/firebird/issues/7879">https://github.com/FirebirdSQL/firebird/issues/7879</a> <br />
</details>
<details>
<summary>Unexpected Results when Using CASE-WHEN with LEFT JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/FirebirdSQL/firebird/issues/7903">https://github.com/FirebirdSQL/firebird/issues/7903</a> <br />
</details>
<details>
<summary>Unexpected results when the join condition contains the OR predicate</summary>
Status: fixed<br />
Link: <a href="https://github.com/FirebirdSQL/firebird/issues/7908">https://github.com/FirebirdSQL/firebird/issues/7908</a> <br />
</details>
<details>
<summary>Unexpected results when using CASE WHEN with RIGHT JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/FirebirdSQL/firebird/issues/7993">https://github.com/FirebirdSQL/firebird/issues/7993</a> <br />
</details>
<details>
<summary>Unexpected results after creating partial index</summary>
Status: fixed<br />
Link: <a href="https://github.com/FirebirdSQL/firebird/issues/7995">https://github.com/FirebirdSQL/firebird/issues/7995</a> <br />
</details>
<details>
<summary>Unexpected results when using string concatenation for INTEGER</summary>
Status: fixed<br />
Link: <a href="https://github.com/FirebirdSQL/firebird/issues/7997">https://github.com/FirebirdSQL/firebird/issues/7997</a> <br />
</details>
<details>
<summary>Unexpected error and crash after creating a partial index</summary>
Status: fixed<br />
Link: <a href="https://github.com/FirebirdSQL/firebird/issues/7998">https://github.com/FirebirdSQL/firebird/issues/7998</a> <br />
</details>
<details>
<summary>Unexpected results when using LIKE with boolean values</summary>
Status: confirmed<br />
Link: <a href="https://github.com/FirebirdSQL/firebird/issues/8132">https://github.com/FirebirdSQL/firebird/issues/8132</a> <br />
</details>
<h3>CedarDB (5 bugs)</h3>
<details>
<summary>Unexpected result when using BETWEEN with BYTEA type</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Unexpected result after UPDATE the column with PK</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Crash by ALTER TABLE DROP COLUMN</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Crash by IS DISTINCT FROM</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<details>
<summary>Crash by LIKE operator</summary>
Status: fixed<br />
Link: <a href="None">None</a> <br />
</details>
<h3>risingwave (4 bugs)</h3>
<details>
<summary>Unexpected Results when Inserting NULL to PK column</summary>
Status: fixed<br />
Link: <a href="https://github.com/risingwavelabs/risingwave/issues/13497">https://github.com/risingwavelabs/risingwave/issues/13497</a> <br />
</details>
<details>
<summary>Unexpected Results when Using NATURAL LEFT JOIN</summary>
Status: fixed<br />
Link: <a href="https://github.com/risingwavelabs/risingwave/issues/13572">https://github.com/risingwavelabs/risingwave/issues/13572</a> <br />
</details>
<details>
<summary>Unexpected Results when Comparing with Bigint</summary>
Status: fixed<br />
Link: <a href="https://github.com/risingwavelabs/risingwave/issues/13601">https://github.com/risingwavelabs/risingwave/issues/13601</a> <br />
</details>
<details>
<summary>Panicked: byte index 1024 is not a char boundary</summary>
Status: fixed<br />
Link: <a href="https://github.com/risingwavelabs/risingwave/issues/14283">https://github.com/risingwavelabs/risingwave/issues/14283</a> <br />
</details>
<h3>Vitess (3 bugs)</h3>
<details>
<summary>Bug Report: Unexpected result when using bit-wise inversion and logical OR</summary>
Status: fixed<br />
Link: <a href="https://github.com/vitessio/vitess/issues/16590">https://github.com/vitessio/vitess/issues/16590</a> <br />
</details>
<details>
<summary>Bug Report: Unexpected result when comparing BIT with VARCHAR</summary>
Status: confirmed<br />
Link: <a href="https://github.com/vitessio/vitess/issues/16832">https://github.com/vitessio/vitess/issues/16832</a> <br />
</details>
<details>
<summary>Bug Report: Unexpected result when using LIKE operator</summary>
Status: fixed<br />
Link: <a href="https://github.com/vitessio/vitess/issues/16831">https://github.com/vitessio/vitess/issues/16831</a> <br />
</details>
<h3>SQLite (3 bugs)</h3>
<details>
<summary>Unexpected results when using `REPLACE` function</summary>
Status: fixed<br />
Link: <a href="https://sqlite.org/forum/forumpost/3776b48e71">https://sqlite.org/forum/forumpost/3776b48e71</a> <br />
</details>
<details>
<summary>Unexpected result when using multiple joins with view</summary>
Status: fixed<br />
Link: <a href="https://sqlite.org/forum/forumpost/3f676b1196">https://sqlite.org/forum/forumpost/3f676b1196</a> <br />
</details>
<details>
<summary>Unexpected result when using multiple joins and subqueries</summary>
Status: fixed<br />
Link: <a href="https://sqlite.org/forum/forumpost/5c8a069d233fdc4dd4aa813d38af3dafd06795fb018c1427c5073ee312b3cacb">https://sqlite.org/forum/forumpost/5c8a069d233fdc4dd4aa813d38af3dafd06795fb018c1427c5073ee312b3cacb</a> <br />
</details>
<h3>MySQL (2 bugs)</h3>
<details>
<summary>Unexpected Results when Using Math Function SIN</summary>
Status: confirmed<br />
Link: <a href="https://bugs.mysql.com/bug.php?id=113180">https://bugs.mysql.com/bug.php?id=113180</a> <br />
</details>
<details>
<summary>Unexpected Results when Using IN for Floating-Point</summary>
Status: confirmed<br />
Link: <a href="http://bugs.mysql.com/113298">http://bugs.mysql.com/113298</a> <br />
</details>
<h3>MariaDB (2 bugs)</h3>
<details>
<summary>Unexpected result when casting decimal in WHERE clause</summary>
Status: confirmed<br />
Link: <a href="https://jira.mariadb.org/browse/MDEV-33999">https://jira.mariadb.org/browse/MDEV-33999</a> <br />
</details>
<details>
<summary>Unexpected result for query with RIGHT JOIN and IS TRUE in where clause</summary>
Status: confirmed<br />
Link: <a href="https://jira.mariadb.org/browse/MDEV-33998">https://jira.mariadb.org/browse/MDEV-33998</a> <br />
</details>
<h3>H2 (2 bugs)</h3>
<details>
<summary>Potential issue when using ROUND</summary>
Status: confirmed<br />
Link: <a href="https://github.com/h2database/h2database/issues/3982">https://github.com/h2database/h2database/issues/3982</a> <br />
</details>
<details>
<summary>Unexpected result when using trigonomeric functions</summary>
Status: fixed<br />
Link: <a href="https://github.com/h2database/h2database/issues/3981">https://github.com/h2database/h2database/issues/3981</a> <br />
</details>
<h3>CockroachDB (2 bugs)</h3>
<details>
<summary>internal error: comparison overload not found (ge, unknown, unknown)</summary>
Status: confirmed<br />
Link: <a href="https://github.com/cockroachdb/cockroach/issues/128889">https://github.com/cockroachdb/cockroach/issues/128889</a> <br />
</details>
<details>
<summary>Unexpected result when using a record in WHERE filter</summary>
Status: fixed<br />
Link: <a href="https://github.com/cockroachdb/cockroach/issues/130649">https://github.com/cockroachdb/cockroach/issues/130649</a> <br />
</details>
<h3>ClickHouse (1 bugs)</h3>
<details>
<summary>Unexpected result when comparing IN expression and integer</summary>
Status: confirmed<br />
Link: <a href="https://github.com/ClickHouse/ClickHouse/issues/65316">https://github.com/ClickHouse/ClickHouse/issues/65316</a> <br />
</details>

</div>